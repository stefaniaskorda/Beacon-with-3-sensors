# Beacon-with-3-sensors

# 0. Context : 
More specifically, we have at our disposal an LDR photoresistor, a TMP36 temperature sensor and a PIR motion sensor.

# 1. The implementation : It will be done with Arduino and the code should give the beacon with the 3 above sensors the following functions:

* Every 10 s, a brightness check is performed.
* If it is dark, the beacon light (e.g. an LED) turns on gradually and stays on for 3 s. It then gradually turns off and stays off for 2 s (these 5 s can be considered negligible to the rest time calculations).
* Every 20 s, it is measured with a temperature sensor (eg TMP36) ambient temperature and displayed in the Serial Monitor, in the form:
Temp is x C
* Ιf motion is detected near the beacon, a direct notification is displayed on the Serial Monitor.

The Arduino editor was used to develop the code, while TinkerCad's 3D Simulator was used to test and simulate the beacon's functionality.

<img src = "https://github.com/stefaniaskorda/Beacon-with-3-sensors/blob/main/tinkercad_circuit.png" width = "528">
