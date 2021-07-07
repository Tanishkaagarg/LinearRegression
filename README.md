STEP 1: Create an conda environment -> conda create -n mlops-LR python=3.7 -y

STEP 2: Activate the conda environment -> conda activate mlops-LR

STEP 3: Install the required libraries/packages -> pip install -r requirements.txt

STEP 4: To check the ML pipelines are working -> dvc repro

STEP 5: To check the metrics -> dvc metrics show

STEP 6: To invoke the service -> python app.py