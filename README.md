Seminar
=======


The PyBluez module allows Python code to access the host machine's Bluetooth
resources.

| Linux  | Raspberry Pi | macOS | Windows |
| ------ | ------------ | ----- | ------- |
|        |              |       |         |




Contributors Wanted
-------------------

**This project is not under active development.** Contributions are strongly
desired to resolve compatibility 


Examples
--------

```python
# simple inquiry example

```

Contact
-------

Please file bugs to the [issue tracker][bugs]. Questions can be asked on the
[mailing list][ml] hosted on Google Groups, but unfortunately it is not very
active.

[bugs]: https://github.com/pybluez/pybluez/issues
[ml]: http://groups.google.com/group/pybluez/


Installation
------------

Use pip (there are also binaries for Windows platform on PyPI or here - [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pybluez)):

    pip install 

For experimental Bluetooth Low Energy support(only for Linux platform -
for additional dependencies please take look at:
[ble-dependencies](https://bitbucket.org/OscarAcena/pygattlib/src/45e04060881a20189412681f52d55ff5add9f388/DEPENDS?at=default)):

    pip install 

For source installation:

    python 

for Bluetooth Low Energy support:

    pip install 

Configuration
------------

Use 

    $ cp -r /home/pi/.node-red /home/pi/git-raspi/piconfig-seminar


Node-red Restore Flow

    $ sudo cp -r /home/pi/git-raspi/piconfig-seminar/node-red/.node-red/* /home/pi/.node-red
 

Node-Red
------------
Install

[Node-red Install](https://nodered.org/docs/hardware/raspberrypi):

Run

    $ node-red-start

Auto start on boot

    $ sudo systemctl enable nodered.service

Node-red Restore Flow

    $ sudo cp -r /home/pi/git-raspi/piconfig-seminar/node-red/.node-red/* /home/pi/.node-red

InfluxDB
------------
Run

    $ 

Check DB size

    $ sudo du -sh /var/lib/influxdb/data/staticsensor

Delete data in measurements

     DELETE FROM "sensor_1"
     DELETE FROM "sensor_2"  


Chronograf

    $ sudo wget https://dl.influxdata.com/chronograf/nightlies/chronograf_nightly_armhf.deb
    $ sudo dpkg -i chronograf_nightly_armhf.deb
    $ sudo systemctl start chronograf

Grafana
------------
Run

    $ 

Plugin

     grafana-cli plugins install neocat-cal-heatmap-panel
     grafana-cli plugins install briangann-gauge-panel
     grafana-cli plugins install natel-discrete-panel
     grafana-cli plugins install mtanda-heatmap-epoch-panel
     grafana-cli plugins install savantly-heatmap-panel
     grafana-cli plugins install vonage-status-panel
     grafana-cli plugins install grafana-simple-json-datasource
     grafana-cli plugins install bessler-pictureit-panel
     grafana-cli plugins install grafana-piechart-panel
     grafana-cli plugins install grafana-worldmap-panel
     grafana-cli plugins install btplc-status-dot-panel  
      

### Build Requirements

#### GNU/Linux

-   Python 2.3 or more recent version

#### Windows

-   Microsoft Windows XP SP1 or Windows Vista/7/8/8.1

#### macOS

-   Python 2.3 or later
    

License
-------

> ff
