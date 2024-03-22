# adeeptpicarpro

## Table of Contents
1. [General Info](#general-info)
2. [Hardware Prerequisites](#hardware-prerequisites)
3. [Technologies](#technologies)
4. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)
6. [Licence](#licence)

### General Info
***
Adeepipicarpro is a Python package specifically crafted to facilitate the management of various functionalities inherent to the Adeept Picar Pro robot. This package is based on the official library provided by Adeept. These functionalities encompass the precise control of movement, servo motor operation, data display on its screen, illumination management, and supervision of sensors including accelerometers and line trackers.

This project is currently under active development. Please feel free to contribute or provide feedback. Detailed installation instructions, comprehensive usage examples, and other pertinent information will be added in due course.

### Hardware Prerequisites
***
1. **Raspberry Pi**: The robot is compatible with several versions of Raspberry Pi, including Raspberry Pi 3B, Raspberry Pi 3B+, and Raspberry Pi 4.
2. **Adeept PiCar-Pro Robot Kit**: This kit includes all the necessary components to assemble the robot, including the chassis, motors, sensors, and controller board.
 
For further information on prerequisites, please consult the following pages:

1. [Page 1: Product List](https://www.adeept.com/learn/tutorial-344.html)
2. [Page 2: Setting Up the Robot Hardware](https://www.adeept.com/learn/tutorial-361.html)
3. [Page 3: Installing and Configuring Raspberry Pi System](https://www.adeept.com/learn/tutorial-348.html)
4. [Page 4: View or Edit the Code Program in Raspberry Pi](https://www.adeept.com/learn/tutorial-349.html)

These pages offer comprehensive details regarding the hardware prerequisites and setup procedures specific to the Adeept Picar Pro robot. Feel free to explore the entire tutorial course on the website for further insights.

### Technologies
***
A list of technologies used within the project:

* [Python](https://www.python.org): Version 3.12.0
* [Adeept Picar Pro Library](https://github.com/adeept/adeept_picarpro): Version latest
* [luma.oled](https://pypi.org/project/luma.oled/): Version  3.13.0
* [luma.core] (https://pypi.org/project/luma.core/): Version 2.4.2
* [openCV] (https://pypi.org/project/opencv-python/): Version 4.9.0.80
* [adafruit-pca9685] (https://pypi.org/project/Adafruit-PCA9685/): Version 1.0.1
* [rpi_ws281x](https://pypi.org/project/rpi-ws281x/1.1.3/): Version 1.1.3
* [mpu6050-raspberrypi](https://pypi.org/project/mpu6050-raspberrypi/): Version 1.2
* [RPi.GPIO] (https://pypi.org/project/RPi.GPIO/) Version 0.7.1
* [time] (https://pypi.org/project/python-time/) Version 0.3.0
* [future] (https://pypi.org/project/future/) Version 1.0.0
* [sys] (https://pypi.org/project/os-sys/) Version 2.1.4
* [threading] (https://pythonprogramming.net/threading-tutorial-python/) Version latest
* [imutils] (https://pypi.org/project/imutils//) Version 0.5.4
* [numpy] (https://pypi.org/project/numpy/) Version 1.26.4
* [os] (https://pypi.org/project/os-sys/) Version 2.1.4
* [datetime] (https://pypi.org/project/DateTime/) Version 5.5
* [importlib] (https://pypi.org/project/importlib/) Version 1.0.4
* [flask] (https://pypi.org/project/Flask/) Version 3.0.2
* [flask_cors] (https://pypi.org/project/Flask-Cors/) Version 4.0.0

### Installation
***
To get started with adeeptpicarpro, follow these instructions for installation:

1. **Install from PyPI**
You can install adeepipicarpro directly from PyPI using pip. First, make sure you have Python and pip installed on your system.
```
$ pip install adeeptpicarpro
```
2. **Install From Github**
Alternatively, you can install the package from its GitHub repository. This method is useful if you want to get the latest development version or if you plan to contribute to the project.

* Clone the Repository: First, clone the adeepipicarpro repository to your local machine
```
$ git clone https://github.com/Rodrig0at/Car-Robot.git
```
* Navigate to the Directory: Navigate into the adeepipicarpro directory.
```
$ cd adeeptpicarpro
```
* Install the Package: Install the package using the provided setup script.
```
$ python setup.py install
```
3. **Verify Installation**
Once installed, you can verify that adeeptpicarpro is correctly installed by importing it in a Python environment.
```
import adeeptpicarpro
```

## Collaboration
***
To collaborate with our project, follow these steps:

* Fork the repository on GitHub.
* Make your desired changes in your forked repository.
* Submit a pull request with a clear description of your changes.
* We welcome contributions from the community to improve our project and make it even better!

## FAQs
***
1. **What is adeeptpicarpro?**
*adeeptpicarpro is a Python package designed to assist in controlling the functionalities of the Adeept Picar Pro robot.*

2. **What functionalities does adeeptpicarpro offer?**
*Adeeptpicarpro facilitates control over various aspects of the Adeept Picar Pro robot, including:*
* *Robot movement.*
* *Servo motor control.*
* *Screen information display.*
* *Led control.*
* *Line tracker.*
* *Acceleration sensing.*
*Additional functionalities may be added over time to enhance the capabilities of Adeeptpicarpro.*

3. **Where can I find more information about the Adeept Picar Pro robot and Adeept library?**
*For comprehensive information regarding the Adeept Picar Pro robot and the Adeept library, it is recommended to visit the official Adeept website. Additionally, users can consult the documentation provided with the robot or explore online resources such as forums and community discussions for further insights and support. Below are pertinent links for reference:*

- [Official Adeept Website](https://www.adeept.com/)
- [Adeept Picar Pro Documentation and Downloads](https://www.adeept.com/learn/detail-50.html)
- [Adeept Picar Pro GitHub Repository](https://github.com/adeept/adeept_picarpro/)
- [Official Raspberry Pi Website](https://www.raspberrypi.org/downloads/)

*These sources offer extensive documentation, including setup procedures, operational guidelines, and troubleshooting assistance, ensuring a thorough understanding of the Adeept Picar Pro ecosystem.*

### Licence
***
This project is licensed under the terms of the MIT license.




