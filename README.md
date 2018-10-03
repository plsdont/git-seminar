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

    python setup.py install

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
      
     

### Build Requirements

#### GNU/Linux

-   Python 2.3 or more recent version
-   Python distutils (standard in most Python distros, separate package
    python-dev in Debian)
-   BlueZ libraries and header files

#### Windows

-   Microsoft Windows XP SP1 or Windows Vista/7/8/8.1
-   Visual C++ 2010 Express for build for Python 3.3 or newer
-   Visual C++ 2008 Express for build for Python 3.2 or older
-   In order to build 64-bit debug and release executables, Visual
    Studio 2008/2010 Standard Edition is required
-   Widcomm BTW development kit 5.0 or later (Optional)
-   Python 2.3 or more recent version

#### macOS

-   Python 2.3 or later
-   Xcode
-   PyObjc 3.1b or later
    

License
-------

> ff
