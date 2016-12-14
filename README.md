# arduino
Reference Design 2 channel EKG  with Arduino Uno and Analog Device amplifier to generate RAW EKG data fed into Medtrics MaaS service
Medtrics API can consumer raw input with given parameters of ADC sample frequency and scaling factor
# Reference Design Spec:
  * RS232 baudrate : 9600bps ~ 600 (16bit)Hz (samples/s) - must higher than ADC sample frequency to ensure no data loss
  * Input Analog Voltage = 3.3V   
  * 10 bit ADC input range = (0-1023) or scaling factor= ~3.22mV/unit (this is ADC resolution)     
  * ADC sample frequency = 250Hz  
  ![Alt text](https://github.com/medtricsio/arduino/blob/master/schematic.jpg?raw=true "Schematics")

