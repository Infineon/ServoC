# ServoC
library  to control the micro servo sg90 motor without using the traditional Arduino Servo library.

The library has been tested to accurately control the sg90 motor for all angles with a precision of 5 degrees, still if you're experiencing isssues, try changing the values of min_pulse_width and max_pulse_width variabless defined in the source CPP file.

**Why a custom lib:**

 To make a universal Servo lib which works on generalised functions/commands and is thus irrespective of the MCU used.

