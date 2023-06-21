## Diarization scoring for CodaLab

This is a preliminary version of d_score adapted for CodaLab

### Components 
`reference_data` contains truth data in rttm files. 

`scoring_program` contains the adapted d_score program

* `metadata` contains the command to be run on CodaLab

* `d_score` contains the program for d_score. 
    * `evaluate.py` checks that the submission data matches the truth data, which is a folder of rttms.


### Requirements
A folder of rttm files.

### Instructions
To run locally, use the command in `scoring_program/metadata` 