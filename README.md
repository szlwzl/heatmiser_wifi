## Heatmiser WiFi - python library

### Overview
A [Heatmiser](http://www.heatmiser.com/) WiFi Thermostat communication tool and library for python.

Supported Heatmiser Thermostats are DT, DT-E, PRT and PRT-E.

The main class of the library is Heatmiser. It supports retrieval of all Thermostat parameters as a dictionary. It also supports setting of some (but not all) of the Thermostat parameters. 

### Supported platforms
The application is written in Python and has been successfully tested with Python version 2.7 and 3.4.

Both Windows and Linux has been tested successfully. Mac OS X has not been tested, but should work as well.

### Installation
No installation required. Just download heatmiser_wifi.py and include it in your project.
  
### Using
To list all parameters write:

    python heatmiser_wifi.py -c <pincode> <themostat_ip_address> -l 

It is also possible to read and write specific parameters. For instructions, write:

    python heatmiser_wifi.py -h

See the the main() function in heatmiser_wifi.py for basic usage of the Heatmiser class.
 
### Author and license
This application is written by Joel Eriksson and is licensed under the GNU Public License.

### Version history

**1.1.0** (January 14, 2016)
* Support for reading / writing specific parameters from command line

**1.0.0** (November 11, 2015)
* First release