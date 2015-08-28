# Pyforms

Pyforms is a Python 2.7.x and 3.x cross-enviroment framework to develop GUI applications, which promotes modular software design and code reusability with minimal effort.

### It offers
* A Python layer of Desktop forms, based on PyQt, OpenGL and other libraries.
* A Python layer that allow applications to run on Desktop GUI, Web and terminal without requiring code modifications.
* A group of rules and methodologies that help the developer maintaining his code short, clean, reusable and readable. 

![Diagram](https://raw.githubusercontent.com/UmSenhorQualquer/pyforms/master/docs/pyforms.png?raw=true "Screen")

Example of an application running in the Desktop, Web and Terminal enviroments:

![Application-Example](https://raw.githubusercontent.com/UmSenhorQualquer/pyforms/master/docs/example.png?raw=true "Screen")


## Installation

### Requirements

* [setuptools] (https://pypi.python.org/pypi/setuptools)
* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [PyQt4](http://www.riverbankcomputing.co.uk/software/pyqt/download)
* [PyOpenGL](http://pyopengl.sourceforge.net/) [Optional - Only used by some Controls]
* [VisVis](https://code.google.com/p/visvis/) [Optional - Only used by some Controls]
* [Numpy](http://www.numpy.org/) [Optional - Only used by some Controls]
* [Python opencv](http://opencv.org/) [Optional - Only used by some Controls]


### Ubuntu 14

* setuptools: ```sudo apt-get install python-setuptools```
* Opengl: ```sudo apt-get install python-opengl```
* OpenCV: ```sudo apt-get install python-opencv```
* PyQt4: ```sudo apt-get install pyqt4-dev-tools python-qt4```
* PyQt4 OpenGL Widget [Optional]: ```sudo apt-get install python-qt4-gl```
* Pyforms: ```sudo pip install pyforms```
* VisVis: ```sudo pip install visvis```

### Mac OSx

* Install python and its tools using [Homebrew] (http://brew.sh)
* [Scientific Python on Mac OS X 10.9+ with homebrew | Jörn's Blog](https://joernhees.de/blog/2014/02/25/scientific-python-on-mac-os-x-10-9-with-homebrew/)
* [Installing scientific Python on Mac OS X | Lowin Data Company](http://www.lowindata.com/2013/installing-scientific-python-on-mac-os-x/)
* run ```sudo python setup.py install```

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.