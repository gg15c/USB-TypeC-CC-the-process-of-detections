# USB-TypeC-CC-the-process-of-detections

## Introduction
USB Type-C is widely used in modern technology. This brief note provides a basic process of the CC pins, and we have used a passive, an active, and a PD cable to show the electrical signal.
 
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

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/typeC_to_typeA.png" width="75%" height="75%" />

 <img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/typeC_to_typeA_unplung.png" width="75%" height="75%" />


## An active Type-C cable (Type-C to DisplayPort)

<img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/typeC_to_DP.png" width="75%" height="75%" />

<img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/typeC_to_DP_SBU.png" width="75%" height="75%" />


## An active Type-C cable (Type-C to PD charger)

<img src="https://raw.githubusercontent.com/gg15c/USB-TypeC-CC-the-process-of-detections/master/Img/typeC_to_PD.png" width="75%" height="75%" />


## Miscellaneous points

Q. What is the function of Ra?

A. The Ra allows the DFP to recognize the existence and orientation of a powered Type-C cable. For example, a mux or a redrive IC which was placed in the cable should connect to a power source, VCONN.

Q. What is the function of VCONN?

A. For example, a mux or a redrive IC which was placed in the cable should connect to a power source, VCONN.




## Reference
* http://kevinzhengwork.blogspot.com/2014/08/usb-type-c-configuration-channel-cc-pin.html

* https://www.microtest.com.tw/upload/download/USB-C%20introduction_ch.pdf

* https://www.usb.org/sites/default/files/D2T1-4%20-%20VESA%20DP%20Alt%20Mode%20over%20USB%20Type-C.pdf