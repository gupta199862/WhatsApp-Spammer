# WhatsApp-Spammer
Windows GUI based Automated spammer for WhatsApp.
## Getting started
### Installing Python3
You need to have Python 3 installed on your PC. If you don't, all you need to do is go to [https://www.python.org/downloads/](https://www.python.org/downloads/) and download the latest version of Python 
OR You could go to [https://anaconda.org/](https://anaconda.org/) and download Anaconda.
### Installing Selenium
#### Pip install:
```shell
pip install selenium
```
#### Conda install:
```shell
conda create --name newenv
conda activate newenv
conda install selenium
```
### Downloading Chrome webdriver
You need to download Chrome webdriver, corresponding to your version of Google Chrome. Go to [http://chromedriver.chromium.org/downloads](http://chromedriver.chromium.org/downloads) and download the suitable version.
## Running the application
Move into the directory containing the application.
Eg:
```shell
cd Desktop
cd WhatsApp Spammer
```
Now type:
```shell
python Run.py
```
to launch the application. 
You need to have an active internet connection and you need to scan the QR code within 20 seconds after pressing on the spam button for it to function.

## Application GUI
![alt text](https://github.com/neeru1207/WhatsApp-Spammer/blob/master/files/GUI.png)

## Working
This application uses Selenium web automation. Based on the data entered by the user, the application opens a web browser and once the user logs into his/her WhatsApp Web, finds the target and spams the message the desired number of times.
This is purely for educational purpose and is not intended to be used for other purposes.
