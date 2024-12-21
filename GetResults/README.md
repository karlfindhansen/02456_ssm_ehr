# Guide to get results
- The `smart_m_development.ipynb` is the final notebook containing the development and evaluation process of our model.
- We use the Mamba-ssm model in the notebook, which is a python library for the SSM model, that can only be run on GPU. 
- The model must therefore be run on google colab, which provides free GPU access.
- The notebook is divided into 3 parts:
  1. Model Definition.
  2. Data Preprocessing
  3. Model Development
  4. Model Training
  5. Model Evaluation

- This folder must therefore be uploaded to google colab, and the filepath must be set accordingly, to run the data provided in the data folder.
- The data must also be unzipped from the repository: https://github.com/gsn245/Selective_SSM_for_EHR_Classification and uploaded to the google colab environment.
