# Image-Browser
## Image Browser using tkinter

### About the Browser
**This browser works as the a displayer for the Stored Graphical Images.**
>1. It is used for handling various file formats.
>2. Basic Viewing operations such as zooming and creating pan icon.
>3. Can have a full screen display.
>4. Can make a direct exit using Exit menu.

### Features Used

**Tkinter**

Tkinter is Python's de-facto standard GUI package. Know more on [Tkinter_Intro](https://www.tutorialspoint.com/python/python_gui_programming.htm)

*Installation*

    sudo apt-get install python3-tk

*Use*

    import tk
    from tkinter import *

**PIL**
Python Imaging Library (newest version Pillow) is a free library that helps in opening , manipulating and handling of different file formats in python. Some of the file formats supported are PPM, PNG, JPEG, GIF, TIFF, and BMP. It is also possible to create new file decoders to expand the library of file formats accessible.[Know more](https://www.pythonforbeginners.com/pil/)

*Installation*

    sudo apt-get install pip3
    pip3 install PIL

*Use*

    from PIL import ImageTk,Image

**os**
The OS module in Python provides a way of using operating system dependent functionality. The functions that the OS module provides allows you to interface with the underlying operating system that Python is running on – be that Windows, Mac or Linux.
[Know More](https://www.geeksforgeeks.org/os-module-python-examples/)

*Use*

    import os

### Result

The user can run the [main program](https://github.com/Ratna04priya/Image-Browser/blob/master/model.py) and can browse , inputs the image file and gets a file dialog where the user can browse the image file  and click on open , which shows the selected image with mentioned functionalities.

### Scope

This program can be used in various ways 
>` User takes the image input file of any extension and use them in other purpose
> Like adding buttons which may run the other big programs in backend like analysing the data, etc.


