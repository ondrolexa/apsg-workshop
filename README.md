# Python programming and its applications in structural geology

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ondrolexa/apsg-workshop/master)

## Schedule

| Time | Topic | Packages |
|-------|-------|----------|
|9:00-10:30|**Introduction to Python programming**|          |
|10:30-10:45|*Break*|          |
|10:45-12:15|**Scientific Python**|Numpy, matplotlib|
|12:15-13:15|*Lunch*|          |
|13:15-14:45|**Python for structural geology**|APSG|
|14:45-15:00|*Break*|          |
|15:00-16:00|**Working examples**|APSG|

## Software Installation

This workshop is taught using Python 3 and the "Scientific Stack", a set of core scientific computing packages written and maintained by various third parties.

### Python

The first step is to install Python on your computer. I will be teaching this course based on **Python 3.6**. If Python 3 is not on your system, you can either download an installer from [Python.org](http://python.org) or install a third-party distribution (see below). I recommend the latter, since these distributions are enhanced, containing most or all of the packages required for the course.

In addition to Python itself, we will be making use of several packages in the scientific stack. These include the following:

* [NumPy](http://www.numpy.org/ "NumPy &mdash; Numpy")
* [SciPy](http://www.scipy.org/ "SciPy.org &mdash; SciPy.org")
* [IPython](http://ipython.org/ "Announcements &mdash; IPython")
* [Pandas](http://pandas.pydata.org/ "Python Data Analysis Library &mdash; pandas: Python Data Analysis Library")
* [Matplotlib](http://matplotlib.org/ "matplotlib: python plotting &mdash; Matplotlib 1.2.1 documentation")

### All-in-one Scientific Python

Perhaps the easiest way to get a feature-complete version of Python on your system is to install the [Anaconda](http://continuum.io/downloads.html) distribution by Continuum Analytics. Anaconda is a completely free Python environment that includes includes almost 200 of the best Python packages for science and data analysis. Its simply a matter of downloading the installer (either graphical or command line), and running it on your system.

Be sure to download the Python 3.6 installer, by following the **Python 3.6 link** for your computing platform.

To install the packages required for this course, the easiest and safest way is to create a suitable environment by typing the following in your terminal:

    conda create -n tsk-python -c ondrolexa python=3 numpy scipy jupyter pandas matplotlib seaborn apsg

This creates a self-contained Python environment in your home directory (called `tsk-python`) that includes all the packages you will need, along with their dependencies. To use this environment at any time, type:

    conda activate tsk-python

To exit the `tsk-python` environment, you can switch it off via:

    conda deactivate

Alternatively, if you would rather not set up a Python environment on your machine, you may run the course materials using `binder` by clicking on the **launch binder** button at the top of this page.

## Downloading Course Materials

The final step is accessing the course materials. **If you are familiar with Git**, you can simply clone this repository:

    git clone https://github.com/ondrolexa/apsg-workshop.git

Otherwise, you may download a zip archive containing the course content. Near the top right-hand part of the repository main page, you should see a **Download ZIP** button.

Clicking this will initiate the download. Unzipping the file (or cloning the repo) will generate a directory called `apsg-workshop-master`, within which will be the same directory structure that you see at the top of the repository main page. 