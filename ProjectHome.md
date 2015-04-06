## Java library for USB portable devices ##

### Description ###

Jusbpmp is a Java library that allows to communicate with portable USB players (supporting MSC or MTP) on Linux or Windows.

It offers features like sending and reading files to / from the USB device, device folder management, MTP metadata management.

### Quick Install and Use ###

> (1) copy jar file to your application lib directory

> (2) copy native library files to your application running directory or in the java.library.path

### v0.1.5 Release Notes ###

> Fixes some bugs on file transfer notifications and metadata.

### v0.1.4 Release Notes ###

> Fixes few bugs on file transfer notifications and metadata.

### v0.1.3 Release Notes ###

> Allow to check if USB device is connected

> Allow to release a device if not used


### v0.1.2 Release Notes ###

> (1) Improved USB device detection

> (2) Linux / Windows compatible version



### v0.1.1 Release Notes ###

> (1) This is only a Linux compatible version

> (2) Tested on Ubuntu 8.04

> (3) Not thread safe

> (4) libjpmp.so depends on libstdc++, libusb, libmtp, libhal and libhal-storage

> (5) jpmp-0.1.1.jar was compiled with jdk 1.6.0\_10