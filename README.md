# MRKL_synthetic_data
This repository contains all of the artificial data used for the experiments described in MKRL white paper:
https://www.ai21.com/blog/jurassic-x-crossing-the-neuro-symbolic-chasm-with-the-mrkl-system

The repository is divided into folders, containing the neccassiry data to replicate the experiments described in the white paper, and are numbered accordingly.

Each data file is in jsonlines format, containing the columns: 
- **prompt**: the text to be evaluated by the model.
- **completion**: the correct text prediction for the model.
- **execution**: the correct evaluation of the completion formula done by a calculator.

Example:
{"prompt":"How much is 27395 plus 87971 plus 25658?","execution":141024.0,"completion":"X=(27395+87971+25658)"}

Some of the files contain extra columns which may be used to further stratify the data. Those columns are not required to replicate any of the experiments desribed in the white paper, but enable a more elaborate analysis.
