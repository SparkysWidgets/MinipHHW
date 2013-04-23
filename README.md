Welcome To: MinipH Hardware Repo!!
================================


##### Note: This is for the LeoPhi Hardware Version 1 Branch

MinipH Hardware Design Files in EAGLE. Not much to say, there are some custom parts will add Library after I clean it up!

Schematic Info
-------------------------
##### Basic schematic is spilt into sections

- Charge Pump section
- Analog Front End - pH gain and offset stages
- 12bit ADC

Board Layout Info
-------------------------
##### Form Factor based on Dangerous Prototypes SoB 50mmx50mm PCB size

- Standard 2.54mm pitch header and Grove style connector
- Guard ring on pH input stage, care must be taken in layout here


Errata
-------------------------

##### Just a quick list of current issues
- Gain may need a bit of boosting (33K instead of 47K) at lower input voltages (VCC < 3.3)
- Silkscreen is small and hard to read in some portions

Firmware
-------------------------

- Take a look in [MinipH's Firmware Repo](https://github.com/SparkysWidgets/MinipHBFW) For Arduino!
- Check out my USB pH interface[LeoPhi](http://www.sparkyswidgets.com/Projects/LeoPhi.aspx) for a powerful and easy to use USB PH Probe interface!

Basic Usage
-------------------------

Usage of MinipH example code is very easy. There are only a few commands, but that doesnt mean you cant augment this further.

####Some of the commands are:
- I : Calibration and general Info dump
- C7 : set pH7 Calibration point
- C4 : set pH7 Calibration point

License Info
-------------------------

<p>This is a fully open source project released under the CC BY license</p>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width: 0px;" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">MinipH</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="www.sparkyswidgets.com" property="cc:attributionName" rel="cc:attributionURL">Ryan Edwards, Sparky's Widgets</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.<br />
Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="/projects/MinipH.aspx" rel="dct:source">http://www.sparkyswidgets.com/projects/MinipH.aspx</a>