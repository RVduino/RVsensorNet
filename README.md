# RVsensorNet
Replace the LED lights type display in a typical RV/Motorhome with an BT capable Nexus7 OLED tablet. Sensor data will come from an Arduino-like sensor network using NRF24L01 and HC05 BT modules. 

Add a transmission temperature gage using the internal sensor loctaed in the NAG1 transmission valve body. The signal from this sensor is ported to pin 34 of the TCM located under the drivers seat. The gage is made from an ATMEGA328 uP and an OLED. Voltage from pin 34 is read through an analog input on the uP and scaled to rtead transmission temp on the OLED. This is a tiny but very bright and readable display. 
