# Python Modules #
The prefix Py- is used to show that something is related to Python. Examples of the use of this prefix in names of Python applications or libraries include **Pygame**, a binding of SDL to Python (commonly used to create games), PyQt and PyGTK, which bind Qt and GTK to Python respectively; and PyPy, a Python implementation originally written in Python.

Libraries such as **NumPy**, **SciPy** and **Matplotlib** allow the effective use of Python in scientific computing, with specialized libraries such as Biopython and Astropy providing domain-specific functionality.
Python is commonly used in artificial intelligence projects and machine learning projects with the help of libraries like **TensorFlow**, **Keras**, **Pytorch** and **Scikit-learn**. As a scripting language with modular architecture, simple syntax and rich text processing tools, Python is often used for natural language processing.

## CPython ##
CPython is the reference implementation of the Python programming language. Written in C and Python, CPython is the default and most widely used implementation of the language.

CPython can be defined as both an interpreter and a compiler as it compiles Python code into bytecode before interpreting it. It has a foreign function interface with several languages including C, in which one must explicitly write bindings in a language other than Python.

## pip ##
pip is a de facto standard package-management system used to install and manage software packages written in Python. Many packages can be found in the default source for packages and their dependencies - Python Package Index (PyPI).
Most distributions of Python come with pip preinstalled.
First introduced as **pyinstall** in 2008 by Ian Bicking (the creator of the virtualenv package) as an alterative to easy_install, pip was chosen as the new name from one of several suggestions that the creator received on his blog post. According to Bicking himself, the name if an acronym for "Pip Installs Packages".

One major advantage of pip is the ease of its command-line interface, which makes installing Python software packages as easy as issuing a command:
    pip install some-package-name
Users can also easily remove the package:
    pip uninstall some-package-name

Most importantly pip has a feature to manage full lists of packages and corresponding version numbers, possible through a "requirements" file. This permits the efficient re-creation of an entire group of packages in a separate environment (e.g. another computer) or virtual environment. This can be achieved with a properly formatted file and the following command, where requirements.txt is the name of the file:

pip install -r requirements.txt
Install some package for a specific version python, where ${version} is replaced for 2, 3, 3.4, etc.:

pip${version} install some-package-name

## Anaconda ##
Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing (data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to simplify package management and deployment. The distribution includes data-science packages suitable for Windows, Linux, and macOS. It is developed and maintained by Anaconda, Inc., which was founded by Peter Wang and Travis Oliphant in 2012. As an Anaconda, Inc. product, it is also known as Anaconda Distribution or Anaconda Individual Edition, while other products from the company are Anaconda Team Edition and Anaconda Enterprise Edition, which are both not free.

Anaconda distribution comes with over 250 packages automatically installed, and over 7,500 additional open-source packages can be installed from PyPI as well as the conda package and virtual environment manager. It also includes a GUI, Anaconda Navigator, as a graphical alternative to the command line interface (CLI).

The big difference between conda and the pip package manager is in how package dependencies are managed, which is a significant challenge for Python data science and the reason conda exists.

When pip installs a package, it automatically installs any dependent Python packages without checking if these conflict with previously installed packages[citation needed]. It will install a package and any of its dependencies regardless of the state of the existing installation[citation needed]. Because of this, a user with a working installation of, for example, Google Tensorflow, can find that it stops working having used pip to install a different package that requires a different version of the dependent numpy library than the one used by Tensorflow. In some cases, the package may appear to work but produce different results in detail.

In contrast, conda analyses the current environment including everything currently installed, and, together with any version limitations specified (e.g. the user may wish to have Tensorflow version 2,0 or higher), works out how to install a compatible set of dependencies, and shows a warning if this cannot be done.

### Anaconda Navigator ###
Anaconda Navigator is a desktop graphical user interface (GUI) included in Anaconda distribution that allows users to launch applications and manage conda packages, environments and channels without using command-line commands. Navigator can search for packages on Anaconda Cloud or in a local Anaconda Repository, install them in an environment, run the packages and update them. It is available for Windows, macOS and Linux.

The following applications are available by default in Navigator:
- JupyterLab: is the next-generation user interface for Project Juypter. It offers all the familiar building blocks of the classic Jupyter Notebook (notebook, terminal, text editor, file browser, rich outputs, etc.) in a flexible and powerful user interface. The first stable release was announced on February 20, 2018.
- Jupyter Notebook
- QtConsole[18]
- Spyder
- Glue
- Orange
- RStudio
- Visual Studio Code
  
## Python Enhancement Proposal (PEP) ##

## OpenPyxl ##

## Pygame ##

## PySpark ##

## PyTorch ##

## Project Jupyter ##
Project Jupyter is a non-profit organization created to "develop open-source software, open-standards, and services for interactive computing across dozens of programming languages". Spun-off from IPython in 2014 by Fernando Pérez, Project Jupyter supports execution environments in several dozen languages. Project Jupyter's name is a reference to the three core programming languages supported by Jupyter, which are **Julia**, **Python** and **R**, and also a hommage to Galileo's notebooks recording the discovery of the moons of Jupiter. Project Jupyter has developed and supported the interactive computing products Jupyter Notebook, JupyterHub, and JupyterLab, the next-generation version of Jupyter Notebook.
