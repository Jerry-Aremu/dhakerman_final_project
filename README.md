# dhakerman_final_project
AutoML Sentiments prediction using AutoGluon Framework

### Introduction
This will with streamlit and Autogluon framwork


### Business objective
to predict property sentiment

### Environment Setup
create an environment ... conda create --name (project_name) python=3.9 ...

Activate the environment ... conda activate the environment ... Install packages in the environment ... NB:This is for windows (Mac users please see the documentation or other relevant materials for more details) pip install torch==1.13.1+cpu torchvision==0.14.1+cpu -f https://download.pytorch.org/whl/cpu/torch_stable.html pip install autogluon streamlit jupyter
Test your installation as follows

..... on the terminal type :python and it will show something like this; (redzone_proj) C:\redoneproj\Telco_customer_churn>python Python 3.9.16 (main, Jan 11 2023, 16:16:36) [MSC v.1916 64 bit (AMD64)] on win32 Type "help", "copyright", "credits" or "license" for more information.

            from autogluon.tabular import TabularDataset, TabularPredictor .... if that works,then your installation for autogluon is working

And then for streamlit, (finalprojenv) C:\Users\Omistaja\OneDrive\Documents\data_RedZone\workspace_data\datahackman_finalproject\hackerman_project>streamlit hello

Welcome to Streamlit. Check out our demo in your browser.

Local URL: http://localhost:8501 Network URL: http://192.168.100.20:8501

Ready to create your own Python apps super quickly? Head over to https://docs.streamlit.io

May you create awesome apps!


### Project Structure

|--README.md
|--images
|--data
|--main.py
|--main.ipynb
|--experimentation.ipynb
|--streamapp.py

### Data ingestion

### Exploratory Data Analysis

### Features Engineering or Processing

### Model Building

### Model Evaluation

### Model Deployment
deployment is carried out on streamlit