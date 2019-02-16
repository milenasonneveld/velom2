# Vélo M² documentation

Here you can find the Open Hardware documentation of the People Pedal Power, the system that makes energy out of bikes.

There are 3 chapters,
1. The bike stand
2. The electric conversion
3. The energy moitoring

To find out more about the Vélo M² project and other project, visit www.velom2.be.

First the overview of the system. In words, we are harvesting the energy from statinary bikes. The energy is converted to regular AC power. We also monitor the energy flow wit the Open Energy Monitoring system.
The bike stands we designed fit regular bikes. The bike wheel drives an electric motor with converts the mecanical energy into electric energy.
The DC power is conducted through a diode and through a current sensor. Then the different cables are connected to the supercapacitor. This is the common point. From the supercapacitor we draw the power for the solar inverter that converts the fluctuating DC power to regular AC power.
We monitor the power befor the common point. An Arduino takes in the values of the current and voltage and transfers it to a Raspberry Pi that logs the data. An app on the smartphone allows to visualse the data.  

![alt text](https://github.com/milenasonneveld/velom2/blob/master/PPP_schema_drawing.png)
