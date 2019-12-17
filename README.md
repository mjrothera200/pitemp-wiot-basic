# Raspberry PI Temperature with Watson IoT - Basic MQTT 

The goal of this project is to provide a very simple method of getting started with Watson IoT and an MQTT client using a real sensor.  I have selected a DHT11 Temperature and Humidity sensor given the simplicity of how to wire the solution.  Please follow the instructions to wire your DHT11 Temperature Sensor here:

**Special thanks for the code already included in this repository that helps read the sensor values from the DHT11**
https://github.com/szazo/DHT11_Python.git

# Step 1:  Wire the DHT 11 Sensor to your PI

Follow the instructions here:
https://www.instructables.com/id/DHT11-Raspberry-Pi/

Some hints:
1.  You can do this with simply the DHT11 and 3 Female to Female jumper wires
2.  If you hold the raspberry pi such that the USB inputs are on the right and the Pins are on the top:
	a.  Wire the first pin on the bottom row to the VCC of the DHT11 - This is 3.3V power
	b.  Wire the second pin on the top row to the ground (GND) of the DHT11 - this is the ground 
	c.  Wire the third pin on the 6th pin on the bottom row to the DATA of the DHT11 - this is GPIO Pin 17

# Step 2:  Verify the DHT 11 is working properly

Run the following command to verify that you are receiving values:

```console
python dht11_example.py
```

Verify that the temperature and humidity readings are displayed.

# Step 3:  Sign up for IBM Cloud and Create an IoT Service

# Step 4:  Create a Device Type called "pitemp"

# Step 5:  Create a new Device called "pi1"

# Step 6:  Customize your Configuration Values in the Python Script

# Step 7:  Run the Program
 

```console
python iot-temp.py
```

# Step 8:  Monitor Results in Watson IoT


#License

This project is licensed under the terms of the MIT license.
