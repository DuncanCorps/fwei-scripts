fwei-scripts
============

Scripts found useful by FWEI.

I hope that people find it useful, contribute improvements, and I chose the right licence.

While useful in their current form, they would benefit from improvements including, but not limited to;
* Independence from FWEI directory layout convention (which is saner than some, IMHO)
* Checks for installed software (e.g. `if which `_programName_` ; then `_mainBodyOfScript_` else echo `_programName_` is required but was not found on PATH ; fi`)
* Cleanup (e.g. removal of redundant code, or code which duplicates a better existing implementation or convention)
* Enhancement, including defensive measures (e.g. `mv-same` needs to handle multiple SOURCEs and a non-file DESTINATION)
* Documentation (each script should explain itself better!)
