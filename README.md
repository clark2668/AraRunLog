# AraRunLog
Log of ara calibration runs.

## Organization
- The repository is organized with a `source` and `logs` directory
- `source` contains all of the `.xls` files which are edited to produce the log files
- `logs` contains the tab-delimtied `.txt` files which are meant to be loaded into the SQL system

## Recommended Usage
- The easiest way to use this is to alter the `.xls` files for every station; this allows for easy cell manipulation
- Then you should export the file to the `.txt` format with tab separated values for import into the SQL system

## File Content
- The files contain four columns:
  - `run_num`: the run number to which the comment applies
  - `username`: the person adding the comment
  - `run_quality`: the type of run it is / why it's status is being modified from "normal"
  - `user_comment`: a user comment about the run
- This follows the paradigm laid out in the [run log proposal](http://ara.icecube.wisc.edu/wiki/index.php/Run_Log_Proposal).
