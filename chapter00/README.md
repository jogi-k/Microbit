# Installation

We will need a version of Python 3.4 for the workshop. Below are instructions on how to install the environment and other necessary tools.

## Windows

You can download Python for Windows [from this site] (https://www.python.org/downloads/). After downloading the `* .msi` file, launch it (double-click on it) and follow the instructions. Be sure to remember the path (directory) where you installed Python. It will be needed soon!

Pay attention to one thing: on the other side of the installer called "Customize" scroll down to the bottom and select "Add python.exe to the path", just like in the picture below:

![screenshot]: (img/1.png) 

## Linux
It is very likely that you already have Python installed with your system. To make sure (and check its version) open the console and enter the following command:
`` Sh
$ python3 --version
Python 3.4.3
`` `
Do not have Python? Or maybe you would like to install another version of it, in this case do it the following ways:

### Debian or Ubuntu

Type the following command in the console:
`` Sh
$ sudo apt-get install python3.4
`` `

### Fedora (up to 21)

Use the following command in the console:
`` Sh
$ sudo yum install python3.4
`` `
Fedora (22+)

Use the following command in the console:
`` Sh
$ sudo dnf install python3.4
`` `
### openSUSE

Use the following command in the console:
`` Sh
$ sudo zypper install python3
`` `
### OS X

Go to https://www.python.org/downloads/release/python-343/ and download the Python installer:

1. Download a file named Mac OS X 64-bit / 32-bit installer,
2. Double-click on python-3.4.3-macosx10.6.pkg to start the installer.

Make sure the installation is successful - open Terminal and run python3:
`` Sh
$ python3 --version
Python 3.4.3
`` `
In case of any doubt or if something went wrong and you do not know what to do next - just ask the person who runs the course. Sometimes not everything goes as it should and the best way out of the situation is to ask for help from someone more experienced.
