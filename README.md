# ddp-python-client

* Base on (https://github.com/hharnisc/python-meteor) project.

* The python code -- ddp-python.py  -- establish connection with Meteor server running on the localhost. At the same time establish connection with DHT11 temerature/humidity sensor connected to the device pin 4(Raspberry Pi B+ device).

* The python code -- simpletest.py  -- is maden for debbuging the DHT11 sensor and show the data on console again the sensor is connected to the pin 4(Raspberry Pi B+).


* Installation 

* $ pip install python-meteor

### How to set and run  ###

* To receive the temperature 

* Merely download at the raspberry pi device the script and run the python file. 

* At current state you need to wait first the meteor server based on (https://github.com/InternetThings/RaspberryPi-Gateway) to be runned first.
