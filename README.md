# USB-TypeC-CC-the-process-of-detections

## Introduction
USB Type-C is widely used in modern technology. This brief note provides a basic process of the CC pins, and we have used a passive, a active, and a PD cable to show the electrical signal.
 
## USB Type-C spec 

* The terms

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/DFP_persp.jpg" width="100%" height="100%" />


* DFP CC pins terminations
 
 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/DFP_CC.jpg" width="100%" height="100%" />


* The voltage on UFP CC pins

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/UFP_CC.jpg" width="100%" height="100%" />

* The DPF/UFP model

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/DFP_UFP_model.jpg" width="100%" height="100%" />


* The DRP model

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/DRP_Model.jpg" width="100%" height="100%" />

* The CC pin cable model

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/CC_pin_cable_model.jpg" width="100%" height="100%" />


## A passive Type-C cable (Type-C to Type-A)

111








## Result

I was plugging a USB dongle, trying to verify the spec.

* A full speed device plug-in
 <img src="https://raw.githubusercontent.com/gg15c/USB-2.0-the-process-of-detections/master/Img/usb_detect.png" width="75%" height="75%" />

* The initial process of a full speed device
 <img src="https://raw.githubusercontent.com/gg15c/USB-2.0-the-process-of-detections/master/Img/usb_detect_1.png" width="75%" height="75%" />
 <img src="https://raw.githubusercontent.com/gg15c/USB-2.0-the-process-of-detections/master/Img/usb_detect_2.png" width="75%" height="75%" />

* A high speed device plug-in

 <img src="https://raw.githubusercontent.com/gg15c/USB-2.0-the-process-of-detections/master/Img/usb_high_speed_1.png">


## Miscellaneous points

How to distinguish a high-speed device or a full-speed device?

=> Both of them pull a resistor on D+ line, but the high-speed device will generate a signal on the D- to notify the host.



## Reference
* https://www.usb.org/document-library/usb-20-specification
