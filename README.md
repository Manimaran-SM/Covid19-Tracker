<h1 align="center">
  <img src="https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/virus.gif" height="200px" width="400px" alt="FAKE NEWS"><br>
  Covid-19 Tracker
</h1>

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![GUI Framework](https://img.shields.io/badge/Framework-TKinter-red)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/LICENSE)

# Overview:
## Introduction
>* Coronaviruses are a large family of viruses that are known to cause illness ranging from the common cold to more severe diseases such as Middle East Respiratory Syndrome (MERS) and Severe Acute Respiratory Syndrome (SARS).
>* A novel coronavirus (COVID-19) was identified in 2019 in Wuhan, China. This is a new coronavirus that has not been previously identified in humans.This course provides a general introduction to COVID-19 and emerging respiratory viruses and is intended for public health professionals, incident managers and personnel working for the United Nations, international organizations and NGOs. As the official disease name was established after material creation, any mention of nCoV refers to COVID-19, the infectious disease caused by the most recently discovered coronavirus.

## Tkinter
  >* The tkinter package (“Tk interface”) is the standard Python interface to the Tk GUI toolkit. Both Tk and tkinter are available on most Unix platforms, as well as on Windows systems. (Tk itself is not part of Python; it is maintained at ActiveState).Running python -m tkinter from the command line should open a window demonstrating a simple Tk interface, letting you know that tkinter is properly installed on your system, and also showing what version of Tcl/Tk is installed, so you can read the Tcl/Tk [documentation](https://docs.python.org/3/library/tkinter.html) specific to that version.
  >* tkinter is all you really need, but a number of additional modules are available as well. The Tk interface is located in a binary module named _tkinter. This module contains the low-level interface to Tk, and should never be used directly by application programmers. It is usually a shared library (or DLL), but might in some cases be statically linked with the Python interpreter.In addition to the Tk interface module, tkinter includes a number of Python modules, tkinter.constants being one of the most important. Importing tkinter will automatically import tkinter.constants, so, usually, to use Tkinter all you need is a simple import statement:
~~~
import tkinter (or) from tkinter import *
~~~

## BeautifulSoup
  >* Beautiful Soup is a library that makes it easy to scrape information from web pages. It sits atop an HTML or XML parser, providing Pythonic idioms for iterating, searching, and modifying the parse tree.
  >* Beautiful Soup is a Python package for parsing HTML and XML documents (including having malformed markup, i.e. non-closed tags, so named after tag soup). It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
  >* Beautiful Soup was started by Leonard Richardson, who continues to contribute to the project and is additionally supported by Tidelift, a paid subscription to open-source maintenance.

## Limitation
  >* It restricts to information gathered from the particular webiste rather than searching throughout the internet.  


## System_Configuration
>* Graphic card: NVIDIA GeForce GTX1050
>* CPU: Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
>* RAM: 8GB
>* Disksapce: 1TB

## Procedure
>* Click clone/download
>* If you github desktop click open in desktop hit the clone button. 
>* If you use download zip, then extract the zip file  
>* If you want to use HTTPS say (https://github.com/Manimaran-SM/Covid19-Tracker.git),  then use the command
``` 
$ git clone https://github.com/Manimaran-SM/Covid19-Tracker.git
```
>* After completing the above steps, You must have PyCharm IDE or Python IDLE to execute this code.
>* run the [covid_app.py](https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/covid_app.py) file.

## Prerequisite
Install request with:

```
pip install request
```
Install beautifulsoup4 with:

```
pip install beautifulsoup4
```
Install matplotlib with:

```
pip install matplotlib
```
Install panda with:

```
pip install panda
```

## Working:
>* while the [covid_app.py](https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/covid_app.py) file is opened and executed, Request are sent to a particular website.
>* This is the [website](https://www.worldometers.info/coronavirus/) https://www.worldometers.info/coronavirus/
>* then required data is gathered from the website using beautiful soup.
>* Using Python Tkinter, User-friendly GUI is created to quickly go through the current impact stats.

## Sample Output:
![image1](https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/output1.png)
![image2](https://github.com/Manimaran-SM/Covid19-Tracker/blob/master/output2.png)
## Note:
>* Given commands works only for windows.
>* Python IDE and Following packages must be installed in system.

## Documentation:
Refer the documentation for more info,
  1) [Tkinter](https://docs.python.org/3/library/tkinter.html)
  2) [Beautiful soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  3) [Request](https://requests.readthedocs.io/en/master/)
  4) [matplotlib](https://matplotlib.org/)
