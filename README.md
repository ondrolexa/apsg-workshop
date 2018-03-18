Title:	Python programming and its applications in structural geology
Author: Ondrej Lexa
Date:	March 18, 2018
# Workshop materials

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

Python itself must be installed first and then there are many packages to install, and it can be confusing for beginners. If you use Linux or MacOS then you will have a default Python installed and you can use it. For Windows you have to install something. There are several options for setting up a nice Python development environment but the setup that is becoming "standard" is *Continuum Analytics* [Anaconda Distribution](http://continuum.io/downloads.html), which we will use during this workshop.

It is a free, easy-to-install package manager, environment manager and Python distribution with a collection of 1,000+ open source packages with free community support. Anaconda is platform-agnostic, so you can use it whether you are on Windows, macOS or Linux. You can learn more about Anaconda and conda by reading the [Anaconda Documentation pages](https://docs.anaconda.com/).",

Be sure to download the Python 3.6 installer, by following the **Python 3.6 link** for your computing platform.

To install the packages required for this course, the easiest and safest way is to create a suitable environment by typing the following in your terminal:

    conda create -n tsk-python -c ondrolexa python=3 numpy scipy jupyter pandas matplotlib seaborn apsg

This creates a self-contained Python environment in your home directory (called `tsk-python`) that includes all the packages you will need, along with their dependencies. To use this environment at any time, type:

    conda activate tsk-python

To exit the `tsk-python` environment, you can switch it off via:

    conda deactivate

Alternatively, if you would rather not set up a Python environment on your machine, you may run the course materials using [Binder](https://mybinder.org/) by clicking on the **launch binder** button at the top of this page.

## Downloading Course Materials

The final step is accessing the course materials. **If you are familiar with Git**, you can simply clone this repository:

    git clone https://github.com/ondrolexa/apsg-workshop.git

Otherwise, you may download a zip archive containing the course content. Near the top right-hand part of the repository main page, you should see a **Clone or download** button.

Clicking **Download ZIP** will initiate the download. Unzipping the file (or cloning the repo) will generate a directory called `apsg-workshop-master`, within which will be the same directory structure that you see at the top of the repository main page. 