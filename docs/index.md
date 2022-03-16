---
binder_popup: "[binder-link]{:target='_blank'}"
binder_button: "[![Launch Binder](https://mybinder.org/badge_logo.svg)][binder-link]{:target='_blank'}"
colab_popup: "[colab-link]{:target='_blank'}"
colab_button: "[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][colab-link]{:target='_blank'}"
notebook_button: "[![Download Notebook](../badges/jupyter.svg)][notebook-link]"
github_button: "[![View on Github](../badges/github.svg)][repo-link]"
zipball_button: "[![Download Zip](../badges/zip.svg)][zipball-link]"
tarball_button: "[![Download TarGz](../badges/tgz.svg)][tarball-link]"
terminal_popup: "[terminal-link]{:target='_blank'}"
---

{{ page.binder_button }}&nbsp;
{{ page.colab_button }}&nbsp;
{{ page.notebook_button }}&nbsp;
{{ page.github_button }}&nbsp;
{{ page.zipball_button }}&nbsp;
{{ page.tarball_button }}&nbsp;
![last updated][last-updated-badge]

**A Tufts University Data Lab Workshop**\
Written by {{ site.author }}

[![datalab.tufts.edu](../badges/datalab.svg)](https://sites.tufts.edu/datalab)&nbsp;
[![@TuftsDataLab](../badges/twitter.svg)](https://twitter.com/intent/follow?screen_name=tuftsdatalab)

Slides: [tufts.box.com/v/{{ site.slides }}](https://tufts.box.com/v/{{ site.slides }})\
Live offerings: [go.tufts.edu/workshops](https://go.tufts.edu/workshops)\
Contact: <datalab-support@elist.tufts.edu>

---
## Table of Contents {#toc}

- [Workshop Overview](#overview)
- [Part 1/2: Working with Python on the Command Line](#part-1)
    - [Launching a Virtual Terminal Instance (Recommended)](#virtual-terminal)
    - [Launching a Conda-Enabled Console using a Local Anaconda or Mambaforge Installation](#local-terminal)
- [Part 2/2: Using an Interactive Python Notebook Environment](#part-2)
    - [Running the Notebook using a Virtual JupyterLab Instance (Recommended)](#binder)
    - [Running the Notebook using Google Colab](#colab)
    - [Running the Notebook using a Local Anaconda Installation](#anaconda)
    - [Running the Notebook using a Local Mambaforge Installation](#mambaforge)
- [Additional Resources](#resources)

---
## Workshop Overview {#overview}

This is a hands-on workshop designed to introduce you to the wonderful world of programming and get you acquainted with the popular and easy-to-use programming language Python. The [first part](#part-1) of the workshop involves hands-on exercises using a command-line based Python interpreter and is intended to be completed at an instructor-guided session. The [second part](#part-2) of the workshop is composed of an interactive Python notebook with built-in exercises and solutions. The notebook is suitable for self-guided study and covers the following:

- Basic **arithmetic** and **string manipulation**
- Working with **lists**, **dictionaries**, and **tuples**
- What are **functions** and how to write your own
- Using **loops** and **list comprehensions**
- Control flow with **conditional** statements
- The difference between **copies** and **views**
- Reading technical **documentation**
- **Importing** and using Python **libraries**

The notebook is designed to be run in a pre-configured cloud-computing environment either via [Binder](#binder) or [Google Colab](#colab) and does not require the installation of any software. Use of [Binder](#binder) is recommended as it provides a JupyterLab interface and allows for an experience similar to using a local installation. It is also possible to run the workshop notebook using a local [Anaconda](#anaconda) or [Mambaforge](#mambaforge) installation. Instructions on how to install Anaconda or Mambaforge are available here: [go.tufts.edu/installingPython](https://go.tufts.edu/installingPython)

---
## Part 1/2: Working with Python on the Command Line {#part-1}

### Launching a Virtual Terminal Instance (Recommended) {#virtual-terminal}

[![Launch Terminal](../badges/terminal.svg)]{{ page.terminal_popup }}

1. Click on the [**Launch Terminal**]{{ page.terminal_popup }} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab. After a few minutes, a **Terminal** instance will launch.
4. To launch a Python interpreter, type `python` and press <kbd>Enter</kbd> or <kbd>Return</kbd>.

---
### Launching a Conda-Enabled Console using a Local Anaconda or Mambaforge Installation {#local-terminal}

1. If you have Anaconda or Mambaforge installed, you can launch a Conda-Enabled Terminal or Prompt as follows:
    - **Windows (Anaconda)**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
    - **Windows (Mambaforge)**: *Start > Mambaforge > Mambaforge Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
2. Ensure the last line of text in the Terminal or Prompt begins with `(base)`.
    - *If this is not the case, use a [__Virtual Terminal__]{{ page.terminal_popup }} instead.*
3. To launch a Python interpreter, type `python` and press <kbd>Enter</kbd> or <kbd>Return</kbd>.

---
## Part 2/2: Using an Interactive Python Notebook Environment {#part-2}

### Running the Notebook using a Virtual JupyterLab Instance (Recommended) {#binder}

{{ page.binder_button }}

1. Click on the [**Launch Binder**]{{ page.binder_popup }} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab. After a few minutes, a **JupyterLab** instance will launch.
4. If the workshop notebook does not automatically open, *double-click* on `{{ site.file }}` in the file browser on the left.

---
### Running the Notebook using Google Colab {#colab}

{{ page.colab_button }}

1. Click on the [**Open in Colab**]{{ page.colab_popup }} button above. The Google Colab interface will open in a new tab.
2. If you are not already signed into your Google account, click on ***Sign In*** in the upper-right and sign in with your Google credentials. **You must be signed in with a Google account to be able to run notebooks in Google Colab.**
3. **Optional:** To retain any changes you make to this notebook, save a copy of the notebook to your Google Drive by clicking the ***Copy to Drive*** button or selecting ***File > Save a copy in Drive***. This will save the notebook to the `Colab Notebooks` directory in your Google Drive. Once the saved copy pops up, close the original notebook and use the copy going forward. Feel free to rename the copy if desired. Any changes made to your personal copy will be automatically saved.

*You might also see a message warning you that this notebook was not authored by Google and hence might contain malicious code. You can trust Data Lab notebooks, so click __Run Anyway__. But when running other third-party notebooks, you should review the code beforehand.*

---
### Running the Notebook using a Local Anaconda Installation {#anaconda}

{{ page.notebook_button }}

1. Click on the [**Download Notebook**][notebook-link] button above to download the workshop notebook.
2. Create a designated directory for this workshop and move the downloaded `{{ site.file }}` notebook there.
3. Launch **Anaconda Navigator** via the Start Menu (*Windows*) or from Applications (*macOS*).
    - **Windows**: *Start > Anaconda3 > Anaconda Navigator*
    - **macOS**: *Applications > Anaconda Navigator*
4. Launch **JupyterLab** using the corresponding ***Launch*** button.
5. JupyterLab will launch in a web browser. (A new tab will be generated if a browser is already open.)
6. Within the JupyterLab file explorer on the left, navigate to the directory containing the `{{ site.file }}` notebook.
7. Once you are in the correct directory, *double-click* on `{{ site.file }}` in the file browser to open the workshop notebook.

---
### Running the Notebook using a Local Mambaforge Installation {#mambaforge}

{{ page.zipball_button }}&nbsp;
{{ page.tarball_button }}

1. Launch **Terminal** (*macOS/Linux*) or **Mambaforge Prompt** (*Windows*).
    - **Windows**: *Start > Mambaforge > Mambaforge Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
2. Run the following commands by typing or pasting the command into the console and then pressing <kbd>Enter</kbd> or <kbd>Return</kbd>.
    - Download and extract the workshop materials:\
      `curl -Lo - https://github.com/tuftsdatalab/{{ site.repo }}/archive/workshop.tar.gz | tar -xzf -`
    - Navigate into the extracted directory: `cd {{ site.repo }}-workshop`
    - Create a new environment for the workshop: `mamba env create -f environment.yml`
    - Activate the workshop environment: `conda activate {{ site.env }}`
    - Open the workshop notebook in JupyterLab: `jupyter lab {{ site.file }}`
3. JupyterLab will launch in a web browser. (A new tab will be generated if a browser is already open.)
4. If the workshop notebook does not automatically open, *double-click* on `{{ site.file }}` in the file browser on the left.
5. **Do not close the console!** Closing the console will also terminate JupyterLab. Leave the console running in the background.

---
## Additional Resources {resources}

- Kaggle Python Course: <https://www.kaggle.com/learn/python>
- W3Schools Python Tutorial: <https://www.w3schools.com/python>
- Google's Python Class: <https://developers.google.com/edu/python>
- Official Python Tutorial: <https://docs.python.org/3/tutorial>

Software Carpentry Lessons
- Programming with Python: <https://swcarpentry.github.io/python-novice-inflammation>
- Plotting and Programming in Python: <http://swcarpentry.github.io/python-novice-gapminder>


[binder-link]: https://mybinder.org/v2/gh/tuftsdatalab/{{ site.repo }}/binder?urlpath=lab/tree/{{ site.file }}
[colab-link]: https://colab.research.google.com/github/tuftsdatalab/{{ site.repo }}/blob/workshop/{{ site.file }}
[notebook-link]: https://cdn.jsdelivr.net/gh/tuftsdatalab/{{ site.repo }}@workshop/{{ site.file }}
[repo-link]: https://github.com/tuftsdatalab/{{ site.repo }}
[zipball-link]: https://github.com/tuftsdatalab/{{ site.repo }}/archive/workshop.zip
[tarball-link]: https://github.com/tuftsdatalab/{{ site.repo }}/archive/workshop.tar.gz
[last-updated-badge]: https://img.shields.io/github/last-commit/tuftsdatalab/{{ site.repo }}?label=last%20updated
[terminal-link]: https://mybinder.org/v2/gh/tuftsdatalab/terminal/binder?urlpath=terminals/1
