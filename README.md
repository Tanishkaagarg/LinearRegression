STEP 1 - Create an conda environment

'''bash
conda create -n mlops-LR python=3.7 -y

STEP 2 - Activate the conda environment

'''bash
conda activate mlops-LR

STEP 3 - Install the required libraries/packages 

'''bash
pip install -r requirements.txt

STEP 4 - Download the Dataset from - https://drive.google.com/file/d/1ktKkE7M0KGtWvX2-RUVtOAynC-4v8Z-2/view?usp=sharing

STEP 5 - 
'''bash
dvc repro

STEP 6 - 
'''bash
dvc metrics show