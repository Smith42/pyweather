pyweather
=========

A simple python script that finds the weather forecast for a stated location.

Powered by openweathermap.org.

Using pyweather
---------------

pyweather takes two arguments from the command line, and returns a weather forecast.

The arguments are the name of the city and the days that will be forecated.

Example: <code>$ pyweather 7 london</code>

The above example will return the forecast for London 7 days into the future. 

Resolving Dependencies
----------------------
This script requires python3, python3-requests, python3-sys and python3-time.

Python3 can be installed through your distrubution's package manager, or downloaded from 
[python's website](https://www.python.org/).

Python3-requests can be installed through pip:

<code>$ pip install requests</code>

Python3-requests also have installation instructions on their 
[website](http://docs.python-requests.org/en/latest/user/install/#install).

Installation
------------

To install pyweather:

<code>$ chmod +x ./pyweather && sudo cp ./pyweather /usr/local/bin/</code>

Licensing
---------

This script is [free software](http://gnu.org/philosophy/free-sw.html), licensed
under the terms of the MIT license. See [LICENSE](LICENSE) for more information.
