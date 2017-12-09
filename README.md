# Domoticz-RAVEn-Plugin
Python plugin alternative to the built in RAVEn Zigbee power consumption monitor

## Key Features

* Creates two Domoticz devices per RAVEn
  1. 'Usage' that tracks current usage
  2. 'Total' that tracks total usage

## Installation

Python version 3.4 or higher required & Domoticz version 3.7xxx or greater.

To install:

* Go in your Domoticz directory, open the plugins directory and create a new one.
* Go in this new folder and run: git pull https://github.com/dnpwwo/Domoticz-RAVEn-Plugin.git at the command line
* Restart Domoticz.
In the web UI, navigate to the Hardware page. In the hardware dropdown there will be an entry called "RAVEn Zigbee energy monitor".

## Configuration

'Serial Port': Dropdown to select the Serial Port the RAVEn is plugged into
'Debug': When true the logging level will be much higher to aid with troubleshooting, when set to 'Logging' a 'plugin.log' file will be created in the plugin folder with debug information.

## Change log

1.4.0:  Initial upload version
