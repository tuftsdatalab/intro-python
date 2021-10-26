---
binder_popup: "[binder-link]{:target='_blank'}"
binder_button: "[![Launch Binder](https://mybinder.org/badge_logo.svg)][binder-link]{:target='_blank'}"
colab_popup: "[colab-link]{:target='_blank'}"
colab_button: "[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)][colab-link]{:target='_blank'}"
notebook_button: "[![Download Notebook](../badges/jupyter.svg)][notebook-link]"
github_button: "[![View on Github](../badges/github.svg)][repo-link]"
zipball_button: "[![Download Zip](../badges/zip.svg)][zipball-link]"
tarball_button: "[![Download TarGz](../badges/tgz.svg)][tarball-link]"
console_popup: >-
    (https://console.python.org/python-dot-org-console/){:target="_blank" onClick="window.open('https://console.python.org/python-dot-org-console/','_blank','height=300,width=745'); return false;"}
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
- [Part 2/2: Using an Interactive Python Notebook Environment](#part-2)
    - [Using Binder (virtual JupyterLab) to Run the Notebook (Recommended)](#binder)
    - [Using Google Colab to Run the Notebook](#colab)
    - [Running the Notebook using a Local Anaconda Installation](#anaconda)
    - [Running the Notebook using a Local Mambaforge Installation](#mambaforge)

---
## Workshop Overview {#overview}

This is a hands-on workshop designed to introduce you to the wonderful world of programming and get you acquainted with the popular and easy-to-use programming language Python.

---
## Part 1/2: Working with Python on the Command Line {#part-1}

[![Launch Python Interpreter](../badges/python.svg)]{{ page.console_popup }}

Click on the [**Launch Python Interpreter**]{{ page.console_popup }} button above to launch an online version of the command-line based Python interpreter.\
If that does not work in your browser, use the online interpreter available on the official Python website: [python.org/shell](https://www.python.org/shell/){:target="_blank"}

If you have Anaconda or Mambaforge installed, you can launch a locally hosted Python interpreter as follows:

1. Launch **Terminal** (*macOS/Linux*) or a **Conda-Enabled Prompt** (*Windows*).
    - **Windows (Anaconda)**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
    - **Windows (Mambaforge)**: *Start > Mambaforge > Mambaforge Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
2. Type `python` and press <kbd>Enter</kbd> or <kbd>Return</kbd>.

---
## Part 2/2: Using an Interactive Python Notebook Environment {#part-2}

### Using Binder (virtual JupyterLab) to Run the Notebook (Recommended) {#binder}

{{ page.binder_button }}

1. Click on the [**Launch Binder**]{{ page.binder_popup }} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab. After a few minutes, a **JupyterLab** instance will launch.
4. If the workshop notebook does not automatically open, *double-click* on `{{ site.file }}` in the file browser on the left.

---
### Using Google Colab to Run the Notebook {#colab}

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

1. Click on the [**Download Zip**][zipball-link] or [**Download TarGz**][tarball-link] button above to download an archive containing the workshop materials.
2. Extract the contents of the downloaded archive to a suitable location and rename the extracted directory if desired.
3. Launch **Terminal** (*macOS/Linux*) or the **Mambaforge Prompt** (*Windows*).
    - **Windows**: *Start > Mambaforge > Mambaforge Prompt*
    - **macOS**: *Applications > Utilities > Terminal*
4. Navigate to the directory containing the extracted workshop materials from within the console.
5. Create a new environment for the workshop: `mamba env create --file environment.yml`
6. Activate the workshop environment: `conda activate {{ site.env }}`
7. Open the workshop notebook in JupyterLab: `jupyter lab {{ site.file }}`
8. JupyterLab will launch in a web browser. (A new tab will be generated if a browser is already open.)
9. If the workshop notebook does not automatically open, *double-click* on `{{ site.file }}` in the file browser on the left.


[binder-link]: https://mybinder.org/v2/gh/tuftsdatalab/{{ site.repo }}/binder?urlpath=lab/tree/{{ site.file }}
[colab-link]: https://colab.research.google.com/github/tuftsdatalab/{{ site.repo }}/blob/workshop/{{ site.file }}
[notebook-link]: https://cdn.jsdelivr.net/gh/tuftsdatalab/{{ site.repo }}@workshop/{{ site.file }}
[repo-link]: https://github.com/tuftsdatalab/{{ site.repo }}
[zipball-link]: https://github.com/tuftsdatalab/{{ site.repo }}/archive/workshop.zip
[tarball-link]: https://github.com/tuftsdatalab/{{ site.repo }}/archive/workshop.tar.gz
[last-updated-badge]: https://img.shields.io/github/last-commit/tuftsdatalab/{{ site.repo }}?label=last%20updated
