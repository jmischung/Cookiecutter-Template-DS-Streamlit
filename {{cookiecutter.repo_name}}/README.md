{{cookiecutter.project_name}}
=============================

{{cookiecutter.description}}


## Getting Started

### Prerequisites

Ensure that you have Python 3.6 or later installed on your machine.

### Set Up

1. Create `conda` env from requirements:  

	`conda create --name <env> --file requirements.txt`
	
### Running the App

To run the Streamlit app, open a terminal, navigate to the directory containing `app.py`, and run the following command:  

	`streamlit run app.py`
	
The app will be served at `http://localhost:8501` by default.  

## Directory Structure

```
streamlit_app/
│
├── app.py # Main Streamlit app file
│
├── requirements.txt # Required libraries and their versions
│
├── data/ # Data storage folder (raw, processed, etc.)
│   ├── raw/
│   ├── processed/
│   └── ...
│
├── models/ # Trained models and related files
│   ├── model_1/
│   ├── model_2/
│   └── ...
│
├── notebooks/ # Jupyter notebooks
│   ├── notebook_1.ipynb
│   ├── notebook_2.ipynb
│   └── ...
│
├── scripts/ # Data processing and model training scripts
│   ├── data_preparation.py
│   ├── train_model.py
│   └── ...
│
├── utils/ # Utility functions and classes
│   ├── init.py
│   ├── helpers.py
│   └── ...
│
├── components/ # Streamlit components (custom widgets, plots, etc.)
│   ├── init.py
│   ├── custom_plot.py
│   └── ...
│
└── .gitignore # Git ignore file to exclude files/directories from version control
```
