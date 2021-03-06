# Lidar Examples


Requires the following Python packages to be installed:

* [pyserial](http://www.athenian-robotics.org/pyserial/)  
* [plot.ly](http://www.athenian-robotics.org/plotly/) 
* [pyFirmata](http://www.athenian-robotics.org/pyfirmata/) 

## Garmin Lidar Lite v3

* The Lidar Lite can be purchased [here](https://www.sparkfun.com/products/14032).

* The specs and wiring diagrams are 
[here](http://static.garmin.com/pumac/LIDAR_Lite_v3_Operation_Manual_and_Technical_Specifications.pdf).

* The Arduino Library is [here](https://github.com/garmin/LIDARLite_v3_Arduino_Library).

## ADAFRUIT VL53L0X TIME OF FLIGHT DISTANCE SENSOR

* The VL53L0X can be purchased [here](https://www.adafruit.com/products/3317).

* The tutorial is [here](https://learn.adafruit.com/adafruit-vl53l0x-micro-lidar-distance-sensor-breakout).


### Usage 
```bash
$ lidar_reader.py --port cu.usbmodem1451 
```

```bash
$ plot_lidar.py --port cu.usbmodem1451 
```

### CLI Options

| Option         | Description                                        | Default |
|:---------------|----------------------------------------------------|---------|
| -s, --serial   | Arduino serial port                                | ttyACM0 |
