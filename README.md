# NeuronalProject2018
<h1 align="center">NAC</h1>
<p align="center">Neuron Automatic Classification</p>
<p align="center">Tool for automatic classification of biological neural signals.</p>

## Table of contents

- [Descritption](#description)
- [User installation](#user-installation)
  - [Dependencies](#dependencies)
  - [Windows](#windows)
  - [MacOS and UNIX](#macos-unix)
- [Source code](#source-code)
- [Customer](#customer)
- [Contact](#contact)
- [Usefull links](#usefull-links)

<a name="description"></a>
## Description 

Electrophysiological data for two distinct populations of neurons were collected by several research teams with common experimental measurements and parameters. The goal of the project is to find a way to automatically classify neurons from these data with the best possible prediction rate. This alternative would have several advantages such as avoiding the use of transgenic animals.

A dataset is made available to students with the category (1 or 2) of each neuron. Ideally a supervised learning method is envisaged using the **Caret library** and the **R software** but also using the **Python language** and the **Scikit-Learn library**. Any other solution can be considered and this can be discussed with the group of students.

<a name="user-installation"></a>
## User installation 

<a name="dependencies"></a>
#### Dependencies : 
- Python2.7
- Sckiti-leran: sklearn
- Matlplotlib
- Tkinter

<a name="windows"></a>
#### Windows :
Just unpack the file : Classification-Neuronale.zip 
and run LaClassificationNeuronale.exe

<a name="macos-unix"></a>
#### MacOS and UNIX :
Before use the script you need to install some packages:  
  -python2.7 (if you are on MacOS)  
  -pip  
  -numpy  
  -scipy  
  -scikit-learn  
  -matplotlib  
  -Tkinter  

For the first time, open a terminal and use these command :
<pre><code>     sudo apt-get install python2.7
     python get-pip.py
     pip install -U numpy,scipy,scikit-learn
     python -m pip install matplotlib
     apt-get install python-tk</code></pre>

If you already have a working installation of any of these packages :
  <pre><code>     pip -review --auto
     sudo apt-get update && apt-get upgrade</code></pre>

<a name="source-code"></a>
## Source code 
You can check the latest source swith the command :
<pre><code>     git clone https://github.com/Debcottais/NeuronalProject2018</code></pre>

<a name="customer"></a>
## Customer 
André Garenne (andre.garenne@u-bordeaux.fr), Team MNEMOSYNE, laboratory IMN

<a name="contact"></a>
## Contact

***Author :***  
  Blais Benjamin : ben.blais@laposte.net  
  Cottais Déborah : d.cottais1@gmail.com  
  De Oliveira Lila : lila.de-oliveira@etu.u-bordeaux.fr  
  Jouan Clément : jouan.clement@hotmail.fr  
  Thouvenin Arthur : athouvenin@outlook.fr


<a name="usefull-links"></a>
## Usefull links

- Scikit-Learn : [Sklearn](http://scikit-learn.org/stable/index.html# "Link to Scikit-Learn website")
  - SVM from Scikit-Learn : [SVM](http://scikit-learn.org/stable/modules/svm.html "Link to SVM documentation from Sklearn")
  - Neural Network from Scikit-Learn : [Neural Network](http://scikit-learn.org/stable/modules/neural_networks_supervised.html "Link to Neural Network documentation from Sklearn")
  
- Playlist of youtube videos which explain how scikit-learn work (by Sentdex) : [Scikit-learn Machine Learning with Python and SKlearn](https://www.youtube.com/watch?v=URTZ2jKCgBc&list=PLQVvvaa0QuDd0flgGphKCej-9jp-QdzZ3 "Scikit-learn Machine Learning with Python and SKlearn")
