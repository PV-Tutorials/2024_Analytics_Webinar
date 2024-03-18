![tutorialpromo](images/tutorial_banner.PNG)

# PVSC50 Python Tutorial
Welcome! The goal of this tutorial is to introduce attendees to the
[pvlib python](https://pvlib-python.readthedocs.io/) package for modeling
production of PV systems. The tutorial is divided into 5 sections and several
appendicies.

## Tutorial Summary:
* **Introduction**: Introduction to the tools being demoed
* **Tutorial 1**: PVAnalytics demo (~15 minutes)
* **Tutorial 2**: RDTools demo (~30 minutes)
* **Tutorial 3**: SDT demo (~30 minutes)

## Tutorial Setup
These tutorials are made with [Jupyter](https://jupyter.org), which is a
browser based interactive Python notebook that allows you to run the tutorials
in the cloud without any additional setup.

#### Installing Requirements
When using Google Colaboratory, you must uncomment the first cell that installs
the tutorial requirements.

    !pip install -r https://raw.githubusercontent.com/PV-Tutorials/2024_Analytics_Webinar/requirements.txt

### Jupyter Books

The full tutorial is hosted as a [Jupyter book](https://jupyterbook.org/intro.html).
This book has navigation, search, and can be used to launch each book in Colaboratory.

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](<https://pv-tutorials.github.io/2024_Analytics_Webinar/index.html>)

### My Binder

The tutorials will remain available on GitHub, and you can run
the tutorial anytime in [Binder](https://mybinder.org) by clicking the
following link:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PVSC-Python-Tutorials/PVSC50/main)

### Locally

You can also run the tutorial locally with
[miniconda](https://docs.conda.io/en/latest/miniconda.html) by following thes
steps:

1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

1. Clone the repository:

   ```
   git clone https://github.com/PV-Tutorials/2024_Analytics_Webinar.git
   ```

1. Create the environment and install the requirements. The repository includes
   a `requirements.txt` file that contains a list the packages needed to run
   this tutorial. To install them using conda run:

   ```
   conda create -n oss_webinar jupyter -c pvlib --file requirements.txt
   conda activate oss_webinar
   ```

1. Start a Jupyter session:

   ```
   jupyter notebook
   ```

1. Use the file explorer in Jupyter lab to browse to `2024_Analytics_Webinar`
   and start the first Tutorial.


### Licensing

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
