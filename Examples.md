# Examples of use #

**List USB connected devices
```
  DeviceManager dm = DeviceManager.getInstance();
  dm.createInstance();
  dm.scanDevices();
  dm.dump();
```**


---


**Print USB device description
```
 Iterator it = dm.getDeviceList().keySet().iterator();
 String devkey = (String)it.next();
 UsbDevice usbdev = (UsbDevice)dm.getDeviceList().get(devkey);
 System.out.println(usbdev.dump());
```**


---


