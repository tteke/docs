..
  AUTO-GENERATED by extract_odm_strings.py! DO NOT EDIT!
  If you want to add more details to a command, create a
  .rst file in arguments_edit/<argument>.rst

.. _dem-gapfill-steps:

dem-gapfill-steps
`````````````````

**Options:** *<positive integer>*

Number of steps used to fill areas with gaps. Set to 0 to disable gap filling. Starting with a radius equal to the output resolution, N different DEMs are generated with progressively bigger radius using the inverse distance weighted (IDW) algorithm and merged together. Remaining gaps are then merged using nearest neighbor interpolation. Default: ``3``

.. include:: ../arguments_edit/dem-gapfill-steps.rst

`Learn to edit <https://github.com/opendronemap/docs#how-to-make-your-first-contribution>`_ and help improve `this page <https://github.com/OpenDroneMap/docs/blob/publish/source/arguments_edit/dem-gapfill-steps.rst>`_!
