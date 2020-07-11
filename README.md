#  Cookiecutter Template: Repeatable Data Analysis with Notebooks 

A [cookiecutter template](https://cookiecutter.readthedocs.io/en/1.7.2/) for simple data analysis.

Full details and walk-through over at [**Practical Business Python:  Building a Repeatable Data Analysis Process with Jupyter Notebooks** ](http://pbpython.com/notebook-process.html) on the background and how to use this cookiecutter template.

## Folder structure

This template will jumpstart your data science projects with the following predictable organizational file structure:

```bash
.
├── 1-Data_Prep.ipynb  # Data prep notebook
├── 2-EDA.ipynb        # Final analysis notebook
├── data               # Categorized data files
│   ├── external       # External data files  
│   ├── interim        # Working folder
│   ├── processed      # Cleaned and ready to use
│   └── raw            # Unmodified originals
└── reports            # Final reports
```

## Installation

To use Cookiecutter, you must have it installed along with Python 3. Once you have Python installed, the recommended way to install Cookiecutter is as follows. Install to the current user's folder, upgrade if available:

```bash
$ pip3 install -U --user cookiecutter
```

## Usage

Then in the folder you want to *contain* the project you're starting, run the template as follows, answering the questions as relevant to your project:

```bash
$ cookiecutter https://github.com/talkpython/pbp_cookiecutter        
project_name [project_name]: data_journalism_project
directory_name [data_journalism_project]: 
description [More background on the project]: Research into latest news trends.
```

Now, in this example, we'll have a folder `data_journalism_project` with the structure described above ready to get to work!
