Title: Piston Motion with Python and matplotlib
Date: 2017-09-15 20:40
Modified: 2017-09-15 20:40
Category: Python
Tags: python, matplotlib, animation
Slug: piston-motion
Authors: Peter D. Kazarinoff
Summary: An animation of piston motion created with Python and matplotlib

# Piston Motion with Python and matplotlib

Piston motion is one of the classic dynamic types of motion that belong to a category of 4-bar motion. Piston motion is the type of motion that the piston in a cylinder of a car engine goes through as the crankshaft rotates. 

## Set up a python virtual environment

To start this process, we will set up a virtual environment on python. 

Real Python has a good [introduciton to virtual environments](https://realpython.com/blog/python/python-virtual-environments-a-primer/) and why to use them.

Using the terminal:
```
$ mkdir piston_motion
$ cd piston_motion
$ mkvirtualenv piston_motion -p python3
```

Now that we have the a new clean virtual environment with Python 3 installed, we need to install the necessary packages
```
$ workon piston_motion
(piston_motion) $ pip install numpy
(piston_motion) $ pip install matplotlib
(piston_motion) $ pip freeze
cycler==0.10.0
matplotlib==2.0.2
numpy==1.13.1
pyparsing==2.2.0
python-dateutil==2.6.1
pytz==2017.2
six==1.10.0
```

Now start coding the python file in your favorite text editor

```
import numpy as np
import matplotlib.pyplot as plt
```

