[![View on Github](https://tuftsdatalab.github.io/badges/github.svg)](https://github.com/tuftsdatalab/intro-python)&nbsp;
![last updated](https://img.shields.io/github/last-commit/tuftsdatalab/intro-python?label=last%20updated)&nbsp;
[![datalab.tufts.edu](https://tuftsdatalab.github.io/badges/datalab.svg)](https://sites.tufts.edu/datalab)&nbsp;
[![@TuftsDataLab](https://tuftsdatalab.github.io/badges/twitter.svg)](https://twitter.com/intent/follow?screen_name=tuftsdatalab)

**A Tufts University Data Lab Workshop**\
Written by Uku-Kaspar Uustalu

Python resources: [go.tufts.edu/python](https://sites.tufts.edu/datalab/python/)\
Questions: <datalab-support@elist.tufts.edu>\
Feedback: <uku-kaspar.uustalu@tufts.edu>

Workshop slides: [tufts.box.com/v/intro-python](https://tufts.box.com/v/intro-python)\
Live offerings: [go.tufts.edu/workshops](https://sites.tufts.edu/datalab/workshops/)

---
This is a hands-on workshop designed to introduce you to the wonderful world of programming and get you acquainted with the popular and easy-to-use programming language Python. The workshop is designed to be run in a cloud-computing environment and does not require the installation of any additional software. Please see the [Workshop Environment](#environment) section if you are interested in installing Python on your computer and running the workshop locally.

Note that this workshop is intended for use in a live instructor-guided session. However, the interactive notebook included in [Part 2](#part-2) is also suitable for self-guided study. Please check the [Data Lab workshop schedule](https://sites.tufts.edu/datalab/workshops/) for upcoming live offerings of this workshop.

---
## Table of Contents

- [Workshop Environment](#environment)
- [Part 1: Working with Python on the Command Line](#part-1)
- [Part 2: Using an Interactive Notebook Environment](#part-2)
    - [Using Binder to Run the Notebook (reccomended)](#binder)
    - [Using Google Colab to Run the Notebook](#colab)
    - [Running the Notebook Locally on Your Computer](#local)

---
## Workshop Environment {#environment}
This workshop is designed to be run in a pre-configured cloud-computing environment either via [Binder](https://mybinder.org/) or [Google Colab](https://colab.research.google.com/). We recommend using Binder as it provides you with a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) interface and allows for an experience similar to running the workshop using a local Python installation. If you are interested in installing Python on your computer and running the workshop locally, please see below for instructions. Tufts affiliates should also note that the software required to run this workshop is also installed on all Tufts public computers and the [TTS Virtual Lab](https://vdi.it.tufts.edu/){:target="_blank"}.

### Installing Anaconda {#anaconda}
If you are completely new to Python, the easiest way into the Python ecosystem is to install [Anaconda](https://www.anaconda.com/). It is a custom Python distribution that is designed for data science, comes bundled with an extremely useful [package manager](https://docs.conda.io/en/latest/), and has most packages you would ever need already preinstalled. Once you have installed Anaconda, you will have most of the tools you need and you will be ready to go. No additional setup or configuration will be needed until deep into your Python and data science journey.

To install Anaconda, please follow these instructions and accept all the default options: [docs.anaconda.com/anaconda/install](https://docs.anaconda.com/anaconda/install/)

### Installing Miniconda {#miniconda}
If you know what you are doing or you do not want to install multiple gigabytes of Python packages you might never use, you should look into [Miniconda](https://docs.conda.io/en/latest/miniconda.html). Miniconda is a watered-down version of Anaconda that only includes Python, the Conda [package manager](https://docs.conda.io/en/latest/), and the packages required for basic functionality. It does not come bundled with various data science libraries, allowing you to configure your Python environnement as you like.

You can download a suitable Minicona installer from here: [docs.conda.io/en/latest/miniconda](https://docs.conda.io/en/latest/miniconda.html)

Because Miniconda does not come reconfigured with the packages required for this workshop, you will need to create a new environment for this workshop as follows:

1. Download the [**environment.yml**](https://cdn.jsdelivr.net/gh/tuftsdatalab/intro-python@master/binder/environment.yml) file that specifies the workshop environment.
2. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
    - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
3. Navigate to the location of the **environment.yml** file. If it is in the *Downloads* folder, you can do: `cd downloads`
4. Create a new environment for the workshop: `conda env create -f environment.yml`
5. Activate the workshop environment: `conda activate intro-python`

---
## Part 1: Working with Python on the Command Line {#part-1}

[![Launch Python Interpreter](https://tuftsdatalab.github.io/badges/python.svg)](https://console.python.org/python-dot-org-console/){:target="_blank" onClick="window.open('https://console.python.org/python-dot-org-console/','_blank','height=300,width=745'); return false;"}

Click on the [**Launch Python Interpreter**](https://console.python.org/python-dot-org-console/){:target="_blank" onClick="window.open('https://console.python.org/python-dot-org-console/','_blank','height=300,width=745'); return false;"} button above to launch an online version of the command-line based interactive Python interpreter. If that does not work in your browser, use the online interpreter available on the official Python website: [python.org/shell](https://www.python.org/shell/){:target="_blank"}

If you have Anaconda/Miniconda installed, you can launch a locally hosted Python interpreter as follows.

1. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
    - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
2. Type `python` and press **Enter/Return**.

---
## Part 2: Using an Interactive Notebook Environment {#part-2}

### Using Binder (virtual JupyterLab) to Run the Notebook {#binder}
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/intro-python/master?urlpath=lab/tree/intro-python.ipynb){:target="_blank"}&nbsp;

Follow the instructions below to launch an online version of the [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) interface pre-configured for this workshop.

1. Click on the [**Launch Binder**](https://mybinder.org/v2/gh/tuftsdatalab/intro-python/master?urlpath=lab/tree/intro-python.ipynb){:target="_blank"} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab. After a few minutes, a JupyterLab instance will launch.
4. To open the workshop notebook, *double-click* on **intro-python.ipynb** in the file browser on the left.

### Using Google Colab to Run the Notebook {#colab}
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/intro-python/blob/master/intro-python.ipynb){:target="_blank"}&nbsp;

Follow the instructions below to launch the workshop notebook in the [Google Colab](https://colab.research.google.com/) interactive Python notebook environment. *Note that a Google account is required to run notebooks in Google Colab.*

1. Click on the [**Open in Colab**](https://colab.research.google.com/github/tuftsdatalab/intro-python/blob/master/intro-python.ipynb){:target="_blank"} button above. The Google Colab interface will open in a new tab.
2. If you are not already signed into your Google account, click on *Sign In* in the upper-right corner and sign in with your Google credentials. **You must be signed in with a Google account to be able to run notebooks in Google Colab.**
3. *Optional:* If you want to retain any changes you make to this notebook, you should save a copy of the notebook to your Google Drive. This can be done by clicking the *Copy to Drive* button or selecting *File > Save a copy in Drive*. The notebook will be saved to the *Colab Notebooks* folder in your Google Drive. Once the saved copy pops up, close the original file and use the copy for the rest of the workshop. Feel free to rename the copy if desired. Any changes you make to your personal copy will automatically be saved.

*You might also see a message warning you that this notebook was not authored by Google and hence might contain malicious code. You can trust Data Lab notebooks, so click __Run Anyway__. But when running other third-party notebooks, you should review the code beforehand.*

### Running the Notebook Locally on your Computer {#local}
[![Download Notebook](https://tuftsdatalab.github.io/badges/jupyter.svg)](https://cdn.jsdelivr.net/gh/tuftsdatalab/intro-python@master/intro-python.ipynb)

If you have installed Anaconda or Miniconda as specified in the [Workshop Environment](#environment) section, you can lauch the workshop notebook locally as follows.

1. Click on the [**Download Notebook**](https://cdn.jsdelivr.net/gh/tuftsdatalab/intro-python@master/intro-python.ipynb) button above to download the workshop notebook. It is recommended you create a designated folder for this workshop and move the notebook there.
2. Launch JupyterLab either from the **command line** or via **Anaconda Navigator**.
    - From the **command line**:
        1. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
            - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
            - **macOS**: *Applications > Utilities > Terminal*
        2. Type `jupyter lab` and press **Enter/Return**.
    - Using **Anaconda Navigator**:
        1. Launch Anaconda Navigator via the Start Menu (*Windows*) or from Applications (*macOS*).
            - **Windows**: *Start > Anaconda3 > Anaconda Navigator*
            - **macOS**: *Applications > Utilities > Terminal*
        2. Launch **JupyterLab** using the corresponding *Launch* button.
3. JupyterLab will open in a web browser. (A new tab will be generated if a browser is already open.)
4. Within the JupyterLab file explorer on the left, navigate to the location of the downloaded **intro-python.ipynb** notebook.
5. Once you are in the correct directory, *double-click* on **intro-python.ipynb** in the file browser to open the workshop notebook.
