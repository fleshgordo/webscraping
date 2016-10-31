# Webscraping

Interactive Python jupyter notebook for web scraping stuff. It covers a basic Python crash course for beginners and advances quite fast to web scraping techniques, tips and tricks, while using the Selenium and BeautifulSoup library.

Tutorial is in German (sorry).

## Installation

### Installation Mac
~~~
sudo easy_install pip
sudo pip install jupyter
sudo pip install selenium
sudo pip install tweepy
sudo pip install bs4
~~~

### Installation Linux
~~~
sudo apt-get install python-pip
sudo pip install jupyter
sudo pip install selenium
sudo pip install tweepy
sudo pip install bs4
~~~

### Notes on python2 and python3

The interactive notebook is written for python2, hence they won't work if your notebook is interpreting them in python3. To install python2 for jupyter follow this procedure in terminal:

~~~
python2 -m pip install --upgrade ipykernel # install the kernel package for Python 2
python2 -m ipykernel install # register the Python 2 kernelspec
~~~
