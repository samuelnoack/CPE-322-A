# Lab 5
# Paho-MQTT

This lab was performed with a headless Raspberry Pi 4 Model B running Raspian OS. This lab set up a Paho-MQTT server to share information across terminal windows. The details of this lab can be found [here](https://github.com/kevinwlu/iot/tree/master/lesson5)

## sudo apt update & installing mosquitto
![](images/1.PNG)

## mosquitto_sub -h localhost -v -t "\$SYS/#"
![](images/2.PNG)

## service mosquitto status & netstat -tln
![](images/3.PNG)

## sudo pip-install -U paho-mqtt && git clone [this](https://github.com/eclipse/paho.mqtt.python.git)
![](images/4.PNG)

## python3 client.py
![](images/5.PNG)

## python3 pubcpu.py (publish)
![](images/6.PNG)

## python3 subcpu.py (subscribe)
![](images/7.PNG)
