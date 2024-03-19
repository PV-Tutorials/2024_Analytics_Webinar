![tutorialpromo]

# OSS Webinar Python Tutorial
Welcome! The goal of this tutorial is to introduce attendees to the following packages:
* PVAnalytics[https://pvanalytics.readthedocs.io/en/stable/]
* RdTools[https://rdtools.readthedocs.io/en/stable/]
* Solar-Data-Tools[https://solar-data-tools.readthedocs.io/en/documentation-sphinx/]

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

### Running PVAnalytics

The following file(s) relate to the PVAnalytics tutorials:

- 'pvanalytics-slideshow.ipynb' : This tutorial gives an example pipeline for pre-processing an AC power data stream.
- 'pvanalytics-irradiance-qa.ipynb' : This tutorial gives an example pipeline for pre-processing an irradiance data stream. 
- 'pvanalytics-temperature-qa.ipynb' : This tutorial gives an example pipeline for pre-processing a temperature data stream. 
- 'pvanalytics-wind-speed-qa.ipynb' : This tutorial gives an example pipeline for pre-processing an wind speed data stream. 

Please run all tutorials to generate the associated pickle files in the /data/ folder, which contain the final processed time series.

### Running RdTools

The following file(s) relate to the RdTools tutorials:

- 'RdTools Tutorial.ipynb' : This tutorial gives an overview of using RdTools to estimate inverter-level degradation and soiling for Solar Data Prize system 2107.

In order to run the RdTools tutorial, please run the associated PVAnalytics notebooks to generate the pickle files containing the processed, filtered time series data.

### Running Solar-Data-Tools

The following file(s) relate to the Solar-Data-Tools tutorials:

- 'solar-data-tools-demo.ipynb' : This tutorial gives an overview of using Solar-Data-Tools to preprocess solar data streams, estimate degradation, and perform loss factor analysis.

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
   this tutorial. The requirements file pins versions to those shown in the demo.
   This ensures you will get the same results as were presented in the webinar, but
   we encourage you to check out the latest versions of all the packages for the most
   up to date functionality. To install them using conda and pip run:

   ```
   conda create --name rdtools_demo python==3.10 notebook==6.48
   conda activate oss_webinar
   pip install -r requirements.txt
   ```

1. Start a Jupyter session:

   ```
   jupyter notebook
   ```

1. Use the file explorer in Jupyter lab to browse to `2024_Analytics_Webinar`
   and start the first Tutorial.


### Licensing

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
