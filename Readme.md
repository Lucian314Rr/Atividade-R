Analog Reading CM230
================
Lucian Pierre
06/04/2021


There are conductivimeters that use digital measures and others that use
analog measures for the calculation of water conductivity, the digital
ones allow a very approximate measurement by the devices that will be
coupled to it for IOT communication, however the analog behind an error
of your AD converter, making it difficult the correct reading by this
iot device.

This package is used to calculate the conductivity reading of
conductivimeters using the analog base, taking into account a series of
readings obtained by sampling, a form of approximation was generated,
reducing the error brought by the microcontroller AD. The reading is
given in us / cm3 microsimens per cubic centimeter, the input must be
entered in mv, milli volts, it is also necessary to calibrate the
conductivity meter to make its use feasible.

## Directions for use:

Using a multimeter or the analog pin of the microcontroller, check the
voltage that the analog output of the conductivimeter presents, with it
in your hands, enter the value in the function and the reading value
will be the presented conductivity, the same can be done in the micro
controller.

## We have: 

Reading &lt;200us/cm3 = drinking water 

Reading&gt; 200us/cm3 = non-drinking water
