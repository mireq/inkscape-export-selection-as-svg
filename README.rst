=====================================
Export selection from inkscape as svg
=====================================

Install
-------

Copy `export_selection.inx` and `export_selection.py` to inkscape extensions
directory.

On linux in most cases just run `mkdir -p ~/.config/inkscape/extensions;cp export_selection* ~/.config/inkscape/extensions`

Usage
-----

Open Extensions / Export / Export selection as svg, set path and click to
save, or map this extension to keyboard shortcut.

Usage from commandline
----------------------

`inkscape --actions="select-by-id:object_id; verb:sk.linuxos.export_selection.noprefs" --batch-process input.svg`


Screenshots
^^^^^^^^^^^

.. image:: https://raw.github.com/wiki/mireq/inkscape-export-selection-as-svg/img/inkscape.png?v2020-04-04
