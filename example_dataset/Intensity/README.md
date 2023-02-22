### Example Intensity Dataset

...

Assumptions:
- ....


Output Format:
- csv file that can be read as a pandas dataframe
- dataframe should have two columns; `sequence` and `irt`
- the `sequence` column is a string and `irt` is a floating point number
- sequences have a variable length, they are not padded

Total number of data examples is `X`. They are split in the following files:
- `file_train_.csv`: Training data with `X` ~ X%
- `file_val.csv`: Validation data with `Y` ~ Y%
- `file_test.csv`: Test data with `Z` ~ Z%
- `file_train_val.csv`: Training and Validation data with `A` ~ A%. This can be used to do a custom train/val split, otherwise the predefined split above can be used.

The folders `n` and `m` contain two different data splits for further exploration.