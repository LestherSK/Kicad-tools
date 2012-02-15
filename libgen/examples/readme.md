libgen - Examples
===========================================================

Here are a few example files that would help to realize the use of the libgen too.
They can be used to build the parts as per the usage specified.

z8.xml
-------
This is an example of the **Z8F1621** *PDIP* type chip.

To create the Library use `python ../libgen.py z8.xml z8.lib`

This would create the lib file. This example helps to realize the use of the 
*Pin Names* and *Etype*.

conn8.xml
----------
This is an exmple of **8-pin Molex connector** generated with a *Single In-line* `SIP` Package. 

To create the Library use `python ../libgen.py conn8.xml conn8.lib`

This would create the lib file. This example helps to realize the use of the 
`PIN_N="8"` attribute to create the pins on the package automatically. 
This attibute is useful in creating diffrent type of connectors quickly.

qfp64.xml
----------
This is an example of **Generic 64-Pin QFP chip** generated with `QUAD` Package.

To create the Library use `python ../libgen.py qfp64.xml qfp64.lib`

This would create the lib file. This example helps to realize the use of the 
'QUAD' packages.


Designed By
-----------
**A.D.H.A.R Labs Research,Bharat(India)**

Abhijit Bose [info@adharlabs.in](mailto:info@adharlabs.in)

[http://adharlabs.in](http://adharlabs.in)


 License
--------
Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported

[CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)

[Full Text](http://creativecommons.org/licenses/by-nc-sa/3.0/legalcode)

