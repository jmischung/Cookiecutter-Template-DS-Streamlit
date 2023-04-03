# Cookiecutter Template | Data Science Streamlit App

A minimal data science Streamlit app project structure.

This template is designed to provide a starting point for creating data science Streamlit apps, and it includes a general project structure for organizing data, notebooks, scripts, models, and Streamlit components.

### Starting a New Project
---  

1. Ensure `cookiecutter` is installed.
2. In the directory where the project is to be located, run `cookiecutter https://github.com/YourGitHubUsername/Cookiecutter-Template-Data-Science-Streamlit-App`

<br>


### Running the App Locally
---

After setting up your project using the cookiecutter template and installing the required dependencies listed in the `requirements.txt` file, you can run the Streamlit app locally by navigating to the project directory in your terminal and executing the following command:

`streamlit run app.py`  


This will start the Streamlit app, and you can access it via the URL provided in the terminal output (usually `http://localhost:8501`).  

<br>

### Default Project Structure
---  

This structure is meant for personal organization. If this project is meant to be stored and/or shared publicly, a license should be added.

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