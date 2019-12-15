---
layout:     post
title:      IMU Sensor
author:     Shenxiu Wu
tags: 		sensors
subtitle:  	Some Short Description of Post
category:   sensors
---
<!-- Start Writing Below in Markdown -->

<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Weaving in between cars in a game on your phone, keeping a quadcopter drone afloat despite changing winds, vacuuming your house with a robot, and translating your precise movements when wearing a VR headset all have one thing in common. They each use sensors, specifically an IMU (Inertial Measurement Unit), in order to function properly.
</font></p>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Before we look at IMUs in particular, let’s start more broadly. A sensor is an electronic device used in concert with other electronics designed to detect changes in an environment, such as light, sound or movement. The sensor then passes that information back to the electronic devices to which it is connected.</font></p>
<br>
### How does an IMU work?
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
An IMU provides 2 to 6 DOF (Degrees of Freedom), which refers to the number of different ways that an object is able to move throughout 3D space. The maximum possible is 6 DOF, which would include 3 degrees of translation (flat) movement across a straight plane/along each axis (front/back, right/left, up/down) and 3 degrees of rotational movement across the x, y and z axes/about each axis.</font></p>
<br>
<div align="center"><img width="300" height="300" src="/images/toolbox/sensors/imu2.jpg"></div>
<br>

### 3 Main Types of Motion Sensor of IMU
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
An IMU is a specific type of sensor that measures angular rate, force and sometimes magnetic field. IMUs are composed of a 3-axis accelerometer and a 3-axis gyroscope, which would be considered a 6-axis IMU. They can also include an additional 3-axis magnetometer, which would be considered a 9-axis IMU. Technically, the term “IMU” refers to just the sensor, but IMUs are often paired with sensor fusion software which combines data from multiple sensors to provide measures of orientation and heading. In common usage, the term “IMU” may be used to refer to the combination of the sensor and sensor fusion software; this combination is also referred to as an AHRS (Attitude Heading Reference System).Most IMU includes accelerometer, gyroscope and magnetometer</font></p>
<br>
#### Accelerometer: 
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
The most commonly used type of motion sensor is the accelerometer. It measures acceleration (change of velocity) across a single axis, like when you step on the gas in your car or drop your phone. Accelerometers measure linear acceleration in a particular direction. An accelerometer can also be used to measure gravity as a downward force. Integrating acceleration once reveals an estimate for velocity, and integrating again gives you an estimate for position. Due to the double integration and the state of today’s technology, an accelerometer is not a recommended method of distance estimation.</font></p>
<br>
#### Gyroscope: 
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
While accelerometers can measure linear acceleration, they can’t measure twisting or rotational movement. Gyroscopes, however, measure angular velocity about three axes: pitch (x axis), roll (y axis) and yaw (z axis). When integrated with sensor fusion software, a gyro can be used to determine an object’s orientation within 3D space. While a gyroscope has no initial frame of reference (like gravity), you can combine its data with data from an accelerometer to measure angular position.</font></p> 
<br>
#### Magnetometer: 
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
A magnetometer, as the name suggests, measures magnetic fields. It can detect fluctuations in Earth’s magnetic field, by measuring the air’s magnetic flux density at the sensor’s point in space. Through those fluctuations, it finds the vector towards Earth's magnetic North. This can be fused in conjunction with accelerometer and gyroscope data to determine absolute heading. As you’ve seen, IMUs are used to measure acceleration, angular velocity and magnetic fields, and, when combined with sensor fusion software, they can be used to determine motion, orientation and heading. They’re found in many applications across consumer electronics and the industrial sector.</font></p> 

<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
As you’ve seen, IMUs are used to measure acceleration, angular velocity and magnetic fields, and, when combined with sensor fusion software, they can be used to determine motion, orientation and heading. They’re found in many applications across consumer electronics and the industrial sector.Below picture shows Wireless Inertial Measurement Units (IMU): A set of customized wireless IMU system includes 8 measurement nodes. 
</font></p>
<br>

<div align="center"><img width="600" height="300" src="/images/toolbox/sensors/imu1.jpg"></div>



<!--<img align="right" src="/images/toolbox/sensors/IMU.jpg"/>-->
<!--An IMU is a specific type of sensor that measures angular rate-->

<!--<div align="center"><img width="150" height="150" src="/images/wireless IMU.jpg"></div>-->
<!--
![wireless IMU](/images/wireless IMU.jpg)
-->
<!--
<div style="text-align: center"> 
<img src="/images/wireless IMU.jpg"/> 
</div>
-->


<br><br>
### Pediatric Knee Exoskeleton with IMU 
<br>
<div align="center">
<iframe width="550" height="300"  src="https://www.youtube.com/embed/tY8Uc9pHUWg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen> </iframe>
</div>
<br><br>
<!--
Some of the information contained in this web site includes intellectual property covered by both issued and pending patent applications. It is intended solely for research, educational and scholarly purposes by not-for-profit research organizations. If you have interest in specific technologies for commercial applications, please contact us [here](/contact.html).
-->

