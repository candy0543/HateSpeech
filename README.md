# HateSpeech

Data
Preprocessing text file
Pre-process external files to generate training, development and test sets.

$ python -m src.data.make_dataset <dataset_file>
Parameters:

dataset_file: hate speech dataset (.csv) + binary labels (hate, not-hate), e.g. "DynamicallyHateDataset.csv".
The files must be inside:

$./data/raw/
Output:

$./data/processed/
