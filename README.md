# Coding Challenge ML Eurosat Die Drei Fragezeichen

## Training Code
- ml_eurosat.ipynb creates the model and prediction CSV files for the TRACK 1.
- ml-eurosat-pre-trained.ipynb creates the model and prediction CSV files for the Track 2.

## Inference Code
Code to instantiate the model(s) and run inference on the test set.

## CSV Prediction Files
Two CSV files containing model predictions, one for each track. Please note that your model checkpoints (see below) should reproduce those results.

## Model Checkpoints
Two model checkpoints (one per track) that reproduce the results of the submitted CSV files.
- At least one checkpoint must reproduce a selected Kaggle submission. This checkpoint can be from either track.
- If your model checkpoints are too large to be included in the zip file, you can include a `checkpoints.md` file containing links to the checkpoints uploaded to OneDrive or a hoster of your choosing.

Participants are required to include the following materials in their submission packages via Canvas as a zip file (1 submission per group is sufficient):

- Separate files per track are allowed.
- 
- **Supporting Files:**
  - A `README.md` file with detailed instructions on how to run training and inference.
  - A `requirements.txt` file listing all dependencies and package versions required for the project (you do not need to include PyTorch). If you used a virtual environment, you can generate the file using pip.
