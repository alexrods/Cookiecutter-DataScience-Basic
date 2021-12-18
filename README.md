# Cookiecutter Data Science Basic

*Template for Data Science projects structure*

## Requirements

- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html)
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html)


        pip install cookiecutter


or

    conda install -c conda-forge cookiecutter

## Create a new project

In a folder where you want your project generated:


    cookiecutter https://github.com/alexrods/Cookiecutter-DataScience-Basic.git

## Resulting directory structure

```
{{ cookiecutter.project_slug }}/
├── LICENSE
├── README.md       <- The top-level README for developers using this project.
├── data
│   ├── processed   <- The final, canonical data sets for modeling.
│   └── raw         <- The original, immutable data dump.
├── enviroment.yml  <- The requirements file for reproducing the analysis environment.
├── models          <- Trained and serialized models, model predictions, or model summaries.
│
└── notebooks       <- Jupyter notebooks. Naming convention is a number (for ordering),
                    the creator's initials, and a short `-` delimited description, e.g.
                    `1.0-jqp-initial-data-exploration`.
```

## Credits

This project was created following a class to [jvelezmagic](https://github.com/jvelezmagic) and his repository [cookiecutter conda data science](https://github.com/jvelezmagic/cookiecutter-conda-data-science).

