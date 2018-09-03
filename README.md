

<img src ="files/images/nova_logo.png" />

# Introduction to Programming
This repository contains a collection of Jupyter/IPython Notebooks introducing fundamental programming concepts in Python. These concepts are common to many programming languages, and can be applied in other languages with different syntax. The notebooks are intended to guide students in learning the basic functionality of programming in Python, as well as introduce some of the most useful Python libraries.

To begin make sure you have setup your programming environment correctly, in order to do this read the [getting started guide](#getting-started). After that you are ready to start working with through the [course material](#course-material), starting by reviewing the lecture material and then working through the core notebooks zero to thirteen. Finally some bonus material is provided about code style, databases, modules, and python philosophy.  

## Course Material

### Materials:
* [Class Slides](class_slides)
* [Some useful Cheat Sheets](cheat_sheets)

### Notebooks:
0. [Introduction to Jupyter Notebooks](00_introduction_to_jupyter_notebooks.ipynb)
1. [Hello World - first program](01_hello_world.ipynb)
2. [Datatypes, strings, numbers and variables](02_datatypes_strings_numbers_and_variables.ipynb)
3. [Lists, tuples, and sets](03_lists_tuples_and_sets.ipynb)
4. [If statements, and conditional logic](04_if_statements.ipynb)
5. [Loops, and user input](05_while_loops_and_user_input.ipynb)
6. [Dictionaries](06_dictionaries.ipynb)
7. [Functions introduction](07_introduction_to_functions.ipynb)
8. [More Functions](08_some_more_functions.ipynb)
9. [Classes and Object Oriented Programming](09_classes_and_OOP.ipynb)
10. [Handling Exceptions](10_exceptions.ipynb)
11. [Interfacing with external files](11_external_files.ipynb)
12. [Numpy library](12_numpy_library.ipynb)
13. [Matplotlib Library](13_matplotlib_library.ipynb)

### Bonus notebooks:
* [Bonus - Coding Style PEP8](bonus_coding_style_PEP8.ipynb)
* [Bonus - Databases and data persistence](bonus_databases_and_persistence.ipynb)
* [Bonus - Importing modules](bonus_importing_modules.ipynb)
* [Bonus - The Zen Of Python](bonus_the_zen_of_python.ipynb)



## Getting started
### 0. Setting up a Virtual Machine with a Linux distribution
Having the same working environment as the rest of the class will help you follow the practical classes and ensure everyone is on the same page throughout the exercises, as well as eliminate the risk of accidentally messing up system and or personal files when learning to use the terminal and finally helps me assisting you through your exercises.

This course will cover basic command line operations in Bash (which is the shell used in Linux distributions).

1. Download and install [Virtual Box](https://www.virtualbox.org/)

2. Download [Ubuntu Desktop 18.04.1 LTS](https://www.ubuntu.com/download/desktop).
3. Open Virtual Box and create your Virtual Machine using the downloaded .iso file (click on New - Top left corner). If you're not sure about which configurations to choose, use the recommended ones.
4. Launch your newly created virtual machine and proceed.


### 1. Install Python
If you have not yet installed Python the **Anaconda** distribution by [**Continuum Analytics**](http://www.continuum.io/) is highly recommended. Anaconda is a completely free enterprise-ready Python distribution for large-scale data processing, predictive analytics, and scientific computing. Anaconda includes an easy-to-use installer for almost every platform, drastically reducing the burden of setting up the environment. In addition it comes packaged with the most useful Python libraries.

Anaconda python can be downloaded from this webpage: [**Anaconda Python**](https://www.anaconda.com/download/)

### 2. Download the tutorial notebooks
If you are familiar with git version control and have git installed then you can download the relevant course notebooks by doing a git clone:

    git clone https://github.com/joaopfonseca/introduction_to_programming.git

Otherwise navigate to the following webpage (where you are reading this readme):

https://github.com/joaopfonseca/introduction_to_programming

And select `Clone or download`, then download the zip file and extract.

### 3. Running Jupyter Notebooks
Navigate to the directory of the unzipped or cloned course files, and open a _Terminal_, and type the following command:

    jupyter notebook

The notebook will launch in a browser from the present working directory.

### 4. Start learning
You are now setup to start working your way through the numbered notebooks in the Jupyter Notebook browser. Start with an introduction to Jupyter by selecting `00_introduction_to_jupyter_notebooks.ipynb` and work through in order.

If you are still curious after working through all the notebooks have a look at the extra notebooks for useful extra information.

## Minimum requirements
If you have installed the Anaconda 3.x distribution as described above you will have fulfilled the basic requirements necessary to begin working. Otherwise, please ensure you have the following installed before starting the course:

* Python 3.x (2.x would work as well)
* IPython 4.x (with **notebook support**) or Jupyter:
* matplotlib library
* NumPy library

To check if these are installed you can run the following:

* `python -V`
* `ipython -V`
* `pip show matplotlib`
* `pip show numpy`

N.B. these coursenotebooks are written in **Python 3**, if you are running Python 2, you might want to consider adding Python 3 to your system.

### Acknowledgements
This repository was adapted from `teach_python_in_notebooks` by [William Grimes](https://github.com/williamgrimes/teach_python_in_notebooks).

## License and Sharing Material
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
