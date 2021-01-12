[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/intro-python/main?urlpath=lab/tree/intro-python.ipynb){:target="_blank"}&nbsp;
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/intro-python/blob/main/intro-python.ipynb){:target="_blank"}&nbsp;
[![View on Github](https://tuftsdatalab.github.io/badges/github.svg)](https://github.com/tuftsdatalab/intro-python)&nbsp;
[![Download Zip](https://tuftsdatalab.github.io/badges/zip.svg)](https://github.com/tuftsdatalab/intro-python/zipball/main)&nbsp;
[![Download TarGz](https://tuftsdatalab.github.io/badges/tgz.svg)](https://github.com/tuftsdatalab/intro-python/tarball/main)&nbsp;
![download size](https://img.shields.io/github/repo-size/tuftsdatalab/intro-python?label=download%20size)&nbsp;
![last updated](https://img.shields.io/github/last-commit/tuftsdatalab/intro-python?label=last%20updated)

**A Tufts University Data Lab Workshop**\
Written by Uku-Kaspar Uustalu

[![datalab.tufts.edu](https://tuftsdatalab.github.io/badges/datalab.svg)](https://sites.tufts.edu/datalab)&nbsp;
[![@TuftsDataLab](https://tuftsdatalab.github.io/badges/twitter.svg)](https://twitter.com/intent/follow?screen_name=tuftsdatalab)

Python resources: [go.tufts.edu/python](https://sites.tufts.edu/datalab/python/)\
Questions: <datalab-support@elist.tufts.edu>\
Feedback: <uku-kaspar.uustalu@tufts.edu>

Workshop slides: [tufts.box.com/v/intro-python](https://tufts.box.com/v/intro-python)\
Live offerings: [go.tufts.edu/workshops](https://sites.tufts.edu/datalab/workshops/)

---
This is a hands-on workshop designed to introduce you to the wonderful world of programming and get you acquainted with the popular and easy-to-use programming language Python. The w workshop is designed to be run in a pre-configured cloud-computing environment either via [Binder](https://mybinder.org/) or [Google Colab](https://colab.research.google.com/) and does not require the installation of any additional software. We recommend using Binder as it provides you with a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) interface and allows for an experience similar to running the workshop using a local Python installation. If you are interested in installing Python on your computer and running the workshop locally, please see the [Installing Python](#install) section for instructions. Tufts affiliates should also note that the software required to run this workshop is also installed on all Tufts public computers and the [TTS Virtual Lab](https://vdi.it.tufts.edu/){:target="_blank"}.

This workshop is intended for use in a live instructor-guided session. However, the interactive notebook included in [Part 2](#part-2) is also suitable for self-guided study. Please check the [Data Lab workshop schedule](https://sites.tufts.edu/datalab/workshops/) for upcoming live offerings of this workshop.

---
## Table of Contents

- [Installing Python (Optional)](#install)
- [Part 1: Working with Python on the Command Line](#part-1)
- [Part 2: Using an Interactive Notebook Environment](#part-2)
    - [Using Binder to Run the Notebook (Recommended)](#binder)
    - [Using Google Colab to Run the Notebook](#colab)
    - [Running the Notebook Locally on Your Computer](#local)

---
## Installing Python (Optional) {#python}
If you are completely new to Python, the easiest way into the Python ecosystem is to install [Anaconda](https://www.anaconda.com/). It is a custom Python distribution that is designed for data science, comes bundled with an extremely useful package manager called [Conda](https://docs.conda.io/en/latest/), and has most packages you would ever need already preinstalled. Once you have installed Anaconda, you will have most of the tools you need for your Python data science journey and you will be ready to go. No additional setup or configuration will be needed until you are experienced enough to implement fairly advanced workflows.

If you know what you are doing or you do not want to install multiple gigabytes of Python packages you might never use, you should look into [Miniconda](https://docs.conda.io/en/latest/miniconda.html). It is a watered-down version of Anaconda that only includes Python, the Conda package manager, and the packages required for basic functionality. It does not come bundled with various data science libraries, allowing you to configure your Python environnement as you like.

- Anaconda installation instructions (recommended): [docs.anaconda.com/anaconda/install](https://docs.anaconda.com/anaconda/install/)
- Miniconda installers: [docs.conda.io/en/latest/miniconda](https://docs.conda.io/en/latest/miniconda.html)

---
## Part 1: Working with Python on the Command Line {#part-1}

[![Launch Python Interpreter](https://tuftsdatalab.github.io/badges/python.svg)](https://console.python.org/python-dot-org-console/){:target="_blank" onClick="window.open('https://console.python.org/python-dot-org-console/','_blank','height=300,width=745'); return false;"}

Click on the [**Launch Python Interpreter**](https://console.python.org/python-dot-org-console/){:target="_blank" onClick="window.open('https://console.python.org/python-dot-org-console/','_blank','height=300,width=745'); return false;"} button above to launch an online version of the command-line based interactive Python interpreter. If that does not work in your browser, use the online interpreter available on the official Python website: [python.org/shell](https://www.python.org/shell/){:target="_blank"}

If you have Anaconda or Miniconda installed, you can launch a locally hosted Python interpreter as follows:

1. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
    - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
2. Type `python` and press **Enter/Return**.

---
## Part 2: Using an Interactive Notebook Environment {#part-2}

### Using Binder (virtual JupyterLab) to Run the Notebook (Recommended) {#binder}
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/intro-python/main?urlpath=lab/tree/intro-python.ipynb){:target="_blank"}&nbsp;

You can launch an online [Binder](https://mybinder.org/) instance with a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) interface pre-configured for this workshop as follows:

1. Click on the [**Launch Binder**](https://mybinder.org/v2/gh/tuftsdatalab/intro-python/main?urlpath=lab/tree/intro-python.ipynb){:target="_blank"} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab. After a few minutes, a JupyterLab instance will launch.
4. If the workshop notebook does not automatically open, *double-click* on **intro-python.ipynb** in the file browser on the left.

---
### Using Google Colab to Run the Notebook {#colab}
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/intro-python/blob/main/intro-python.ipynb){:target="_blank"}&nbsp;

Google account holders can launch the workshop notebook in the [Google Colab](https://colab.research.google.com/) interactive Python notebook environment as follows:

1. Click on the [**Open in Colab**](https://colab.research.google.com/github/tuftsdatalab/intro-python/blob/main/intro-python.ipynb){:target="_blank"} button above. The Google Colab interface will open in a new tab.
2. If you are not already signed into your Google account, click on *Sign In* in the upper-right corner and sign in with your Google credentials. **You must be signed in with a Google account to be able to run notebooks in Google Colab.**
3. *Optional:* If you want to retain any changes you make to this notebook, you should save a copy of the notebook to your Google Drive. This can be done by clicking the *Copy to Drive* button or selecting *File > Save a copy in Drive*. The notebook will be saved to the *Colab Notebooks* folder in your Google Drive. Once the saved copy pops up, close the original file and use the copy for the rest of the workshop. Feel free to rename the copy if desired. Any changes you make to your personal copy will automatically be saved.

*You might also see a message warning you that this notebook was not authored by Google and hence might contain malicious code. You can trust Data Lab notebooks, so click __Run Anyway__. But when running other third-party notebooks, you should review the code beforehand.*

---
### Running the Notebook Locally on your Computer {#local}
[![Download Zip](https://tuftsdatalab.github.io/badges/zip.svg)](https://github.com/tuftsdatalab/intro-python/zipball/main)&nbsp;
[![Download TarGz](https://tuftsdatalab.github.io/badges/tgz.svg)](https://github.com/tuftsdatalab/intro-python/tarball/main)

If you have Anaconda or Miniconda installed, you can launch the workshop notebook locally as follows:

1. Click on the [**Download Zip**](https://github.com/tuftsdatalab/intro-python/zipball/main) or [**Download TarGz**](https://github.com/tuftsdatalab/intro-python/tarball/main) button above to download an archive containing the workshop materials.
2. Extract the contents of the downloaded archive to a suitable location and rename the extracted folder if desired.
3. Launch JupyterLab either from the **command line** or via **Anaconda Navigator**.
    - From the **command line**:
        1. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
            - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
            - **macOS**: *Applications > Utilities > Terminal*
        3. *Optional:* If you are using Miniconda or have modified your base Anaconda environment, create and activate a new environment for this workshop using the included **environment.yml** file as follows:
            1. Navigate to the folder containing the extracted workshop materials from within the console.
            2. Create a new environment for the workshop: `conda env create -f environment.yml`
            3. Activate the workshop environment: `conda activate intro-python`
        2. Type `jupyter lab` and press **Enter/Return** to launch JupyterLab.
    - Using **Anaconda Navigator** (unmodified Anaconda installations only):
        1. Launch Anaconda Navigator via the Start Menu (*Windows*) or from Applications (*macOS*).
            - **Windows**: *Start > Anaconda3 > Anaconda Navigator*
            - **macOS**: *Applications > Utilities > Terminal*
        2. Launch **JupyterLab** using the corresponding *Launch* button.
4. JupyterLab will open in a web browser. (A new tab will be generated if a browser is already open.)
5. Within the JupyterLab file explorer on the left, navigate to the location of the downloaded **intro-python.ipynb** notebook.
6. Once you are in the correct directory, *double-click* on **intro-python.ipynb** in the file browser to open the workshop notebook.
