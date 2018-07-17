# QR-Code
A real-time QR Code scanning program using webcam and Python 3

## Dependencies
There are 3 dependencies for this project:
1. ZBar 
2. pyzbar
3. OpenCV 
4. imutils

Before installing anything I would prefer you to make virtual env using your favourite tool like conda, pipenv etc.

### Installing Zbar
Installing ZBar for Ubuntu can be accomplished with the following command:

```console
foo@bar:~$ sudo apt-get install libzbar0
```

### Installing pyzbar
You can simply use pip to install pyzbar

```console
foo@bar:~$ pip install pyzbar
```

### Installing OpenCV
[Here](http://cyaninfinite.com/tutorials/installing-opencv-in-ubuntu-for-python-3/) is a step by tutorial showing you how to install OpenCV 3 on Python 3. Just follow the tutorial.


### Installing imutils
Only after installing OpenCV install imutils as it depends on it.

```console
foo@bar:~$ pip install imutils
```

## Running the application

Check whether you webcam is accessible by running the **webcam.py** program.

```console
foo@bar:~$ python webcam.py
```

Run the program by using python

```console
foo@bar:~$ python custom_qr.py
```


Results,

![No QR Code. Webcam window](https://raw.githubusercontent.com/meticulousCraftman/QR-Code/master/images/img1.png)

![QR Code Scanning](https://raw.githubusercontent.com/meticulousCraftman/QR-Code/master/images/img2.png)

## Reference
You can find a complete tutorial on this [here](https://www.pyimagesearch.com/2018/05/21/an-opencv-barcode-and-qr-code-scanner-with-zbar/).
