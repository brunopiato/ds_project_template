# Data Science Project Template

This repository is a template to Data Science Projects with the main folder structure, files and directories I need to a DS Project. It was made based on other data scientists templates and on the CRISP-DS projects Life Cycle.

<img src="https://www.proglobalbusinesssolutions.com/wp-content/uploads/2017/12/data-mining.jpg" alt="CRISP-DM Framework"/>

<br>

## The folder structure
The directories structure is as follows:

```
.
├── data                        <- Data used in the project
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── docs                        <- A default Sphinx project; see sphinx-doc.org for details
├── models                      <- Models used in production
├── notebooks                   <- Notebooks used to explore and generate models
├── README.md                   <- The top-level README for developers using this project.
├── references                  <- Data dictionaries, manuals, and all other explanatory materials.
│   └── folder_structure.txt
├── reports                     <- Generated analysis as HTML, PDF, LaTeX, PNG, JPG, etc.
│   └── figures
├── requirements.txt            <- The requirements file for reproducing the analysis environment, e.g.
│                                  generated with 'pip freeze > requirements.txt' or 'pipreqsnb' and 'pipreqs'
└── src                         <- Source code for use in this project.
    ├── data                    <- Scripts to download or generate data
    │   ├── __init__.py
    │   └── make_dataset.py
    ├── features                <- Scripts to turn raw data into features for modeling
    │   ├── build_features.py
    │   └── __init__.py
    ├── __init__.py             <- Makes src a Python module
    ├── models                  <- Scripts to train models and then use trained models to make
    │   │                          predictions
    │   ├── __init__.py
    │   ├── predict_model.py
    │   └── train_model.py
    └── visualization           <- Scripts to create exploratory and results oriented visualizations
        ├── __init__.py
        ├── plot_settings.py
        └── visualize.py
```
<br>

## The directories
### Data

### Docs

### Models

### Notebooks

### References

### Reports

### Src




It is based on Dave Ebbelaar's ds porject template [Dave's DS Project Template](https://github.com/daveebbelaar/data-science-template) which was based on 
[Cookie Cutter Data Science](https://drivendata.github.io/cookiecutter-data-science/).
