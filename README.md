[![GitHub version](https://badge.fury.io/gh/fablab-ka%2Fopenscad2d.svg)](http://badge.fury.io/gh/fablab-ka%2Fopenscad2d)
[![Stories in Ready](https://badge.waffle.io/fablab-ka/OpenSCAD2D.png?label=ready&title=Ready)](https://waffle.io/fablab-ka/OpenSCAD2D)
[![Travis CI](https://api.travis-ci.org/fablab-ka/OpenSCAD2D.png)](https://travis-ci.org/fablab-ka/OpenSCAD2D)
[![Code Health](https://landscape.io/github/fablab-ka/OpenSCAD2D/master/landscape.svg?style=flat)](https://landscape.io/github/fablab-ka/OpenSCAD2D/master)
[![Coverage Status](https://coveralls.io/repos/fablab-ka/OpenSCAD2D/badge.svg)](https://coveralls.io/r/fablab-ka/OpenSCAD2D)
[![Documentation Status](https://readthedocs.org/projects/openscad2d/badge/?version=latest)](https://readthedocs.org/projects/openscad2d/?badge=latest)
[![Dependency Status](https://gemnasium.com/fablab-ka/OpenSCAD2D.svg)](https://gemnasium.com/fablab-ka/OpenSCAD2D)

OpenSCAD2D
==========

[![Join the chat at https://gitter.im/fablab-ka/OpenSCAD2D](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fablab-ka/OpenSCAD2D?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=fablab&url=https%3A%2F%2Fgithub.com%2Ffablab-ka%2FOpenSCAD2D&title=OpenSCAD2D&language=&tags=github&category=software)



OpenSCAD2D is a software for creating solid 2D CAD objects.

This Software is inspired by the ingenious 3D CAD Modeller [OpenSCAD](http://www.openscad.org/).

### Content

* General Information
    * [Dependencies](#Dependencies)
    * [Install](#Install)
    * [Screenshots](#Screenshots)
    * [TODO](#TODO)
* [API](https://github.com/fablab-ka/OpenSCAD2D/wiki/API)

#### Dependencies

* [Python 2.6 / Python 2.7](https://www.python.org/downloads/)
* [pywatch](https://github.com/cmheisel/pywatch)
* [pyqt4](http://www.riverbankcomputing.co.uk/software/pyqt/intro) ([Installer](http://sourceforge.net/projects/pyqt/files/PyQt4/PyQt-4.11.3/PyQt4-4.11.3-gpl-Py2.7-Qt4.8.6-x32.exe))
* [pyparsing](http://pyparsing.wikispaces.com/Download+and+Installation)
* [shapely](https://pypi.python.org/pypi/Shapely#downloads)

### Install

## Ubuntu

* sudo apt-get install python2.7 python2.7-dev python-shapely python-pyparsing
* sudo pip install -r requirements.txt --use-mirrors
* sudo ./install_pyqt4.sh

### Screenshots

![Image of First Union](https://raw.githubusercontent.com/fablab-ka/OpenSCAD2D/master/docs/first_union.png)

### TODO

* [ ] Language
    * [x] ~~Single Line Comments~~
    * [x] ~~Multi Line Comments~~
    * [x] ~~Basic Calculations~~
    * [ ] Variable assignment & lookup
    * [ ] Math functions (cos sin tan acos asin atan atan2 abs ceil concat cross exp floor ln len let log lookup max min norm pow rands round sign sqrt)
    * [ ] print statement
    * [ ] Datatypes
        * [x] ~~integer~~
        * [x] ~~float~~
        * [x] ~~boolean~~
        * [ ] string
    * [ ] Primitives
        * [x] ~~circle~~
        * [x] ~~rect~~
        * [ ] path
    * [ ] Attached Modifiers
        * [x] ~~translate~~
        * [x] ~~rotate~~
        * [x] ~~scale~~
        * [ ] Debugging Aids (% # ! *)
        * [ ] mirror
    * [ ] Scope Modifiers
        * [ ] translate
        * [ ] rotate
        * [ ] scale
        * [ ] hull
        * [x] ~~union~~
        * [x] ~~difference~~
        * [x] ~~intersection~~
        * [ ] combine
        * [ ] knapsack
        * [ ] assign
    * [ ] Modules
        * [ ] module definition
        * [ ] module call
        * [ ] module argument stack evaluation
    * [ ] Advanced Structures
        * [ ] if/else statement
        * [ ] basic loop
        * [ ] include statements
* [ ] Application Frame
    * [x] ~~auto reload file~~
    * [x] ~~commandline argument~~
    * [ ] Sexy UI
    * [ ] main menu 
        * [x] ~~load file~~
        * [x] ~~export SVG~~
        * [x] ~~exit~~
        * [ ] about
        * [ ] help
        * [ ] export DXF


