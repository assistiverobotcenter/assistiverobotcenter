---
layout:     post
title:      Customized High Torque Density Actuator 
author:     Shenxiu Wu
tags: 		sensors
subtitle:  	Some Short Description of Post
category:  sensors
---
<!-- Start Writing Below in Markdown -->

<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Quasi-direct drive actuation is a new paradigm of robot actuation design that leverages high torque density motors with low ratio transmission mechanism. The benefits of the quasi-direct drive include a simplified mechanical structure, reduced mass and volume, and highly backdrivability. To enable the quasi-direct drive actuation paradigm, it is crucial to design high torque density motors. Our custom designed BLDC motors optimize the mechanical structure, topology, and electromagnetic properties as shown in Fig 1(a). To maximize torque density, it adopts an outer rotor, pancake (flat, shorter aspect ratio) and concentrated winding structure with more pole pairs. It has a higher coil space factor (more winding set in certain space), single strand winding, smaller gaps between adjacent the rotor and use high-temperature resistive magnetic materials to reduce stator iron loss. To minimize rotary inertia, unlike conventional BLDC motors that place windings around rotors, our rotor only consists of the permanent magnet and rotor cover while the winding is attached to stators. Through the lightweight design of outer rotor, the motor rotary inertia can be minimized. Our motor also makes the back electromotive force more sinusoidal, therefore the field-oriented control becomes easy and the control become more precise and has higher efficiency. Fig 1(b) shows our motor operation range (torque-velocity performance), it has a similar continuous torque-velocity performance with Maxon EC flat 505592, but the weight is less than one-third of it (Our motor weights 174g vs. Maxon’s 600g). Through the electromagnetic and mechanical optimization which uses high-temperature resistant materials and scientific wiring, our motor has higher overdrive and heat dispassion ability to overdrive to 2 Nm peak torque in 5 seconds. </font></p>
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Based on brushless motor design principle, motor with larger air gap radius can generate higher torque density. Therefore, choosing a motor with similar air gap radius for torque density comparison can more accurately reflect the performance of the motor design. Fig. 1© and Table. 1 shows the continuous torque density versus air gap radius distribution of our motor and commercial ones. The plot of specific continuous torque against air gap radius demonstrates a linear trend among the commercial products (Maxon, Allied, and Parker), but our motor and T-motor U series become apparent and have better performance. T-motor U series had high torque density performance in and proofed the type of this motor can be used for the high torque and precision servo control. While our motor has better performance in both torque density and control. T-motor series was originally designed for aircraft usage, it should be designed as flying saucer type to match the propeller, chasing for higher power density and mainly working under speed control. Our motor is customized for. It has higher torque density and easier for sine wave field-oriented control due to its mechanical and electromagnetic optimization (flatter design, more pole pairs, higher inductance and higher coil space factor).</font></p>
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
To accommodate the volume and mass requirement for portable knee exoskeleton design and maximum the package factor (motor and gear weight divide total actuator weight), we customized a fully-integrated direct-drive smart actuator, as shown in Fig 1(d). The weight is 484g weight and it included high torque density flat outer-rotor motor, 14 bits high accuracy magnetic encoder, 10-60 V wide range input driver and motor controller. Besides, the low-level control loop is implemented in the driver-control system and can realize basic control methods, included position, velocity, and current control. Thanks to the built-in electronics and sensors, the actuator actual position, current, velocity, and impedance can be directly measured and regulated without any additional components. High-level control devices can send a command to read and write the real-time information actuator through the CAN bus communication protocol. </font></p>
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
With a nominal voltage of 42 V, the actuator reaches a nominal speed of 4000 RPM. Without using heat sink and cooling, it can output over 0.67 Nm torque continually. Unlike robot joints, for walking assistance, exoskeleton actuators only need to offer high output torque intermittently during each whole gait cycle. So, the actuator can easily work as overload mode and output more than 2 Nm during knee exoskeleton torque assistance control. By connecting to the bi-directional cable transmission structure with 8:1 gear ratio, the whole actuation system can offer enough output torque with very low reduction ration, which will reduce impedance and enhance backdrivebility, and make the system intrinsically safe. </font></p>
<br>

<div align="center"><img width="400" height="400" src="/images/toolbox/actuators/motor_2.jpg"></div>
<p style="text-indent:2em"><font face="Arial" color = "black" size="2" style="line-height: 1.1">
Fig 1. Customized high torque density motor and fully-integrated direct-drive actuator. (a) Overview of our customized outer rotor brushless DC motor. A series of mechanical structure, topology, and electromagnetic properties optimization make the motor high torque density performance; (b) Operating a range of our motor. The maximum velocity under this working condition is about 4000 rpm, the red area shows the motor continuous operation range, the pink area shows the motor 5 seconds overloaded operation range, the white area shows the motor can work in very short-term operation. The diagram shows the actuator has high overload ability; (c) Our motor design possesses the highest specific continuous torque in the motor series with 35-40 mm air gap radius; (d) Overview and exploded view of the custom designed fully-integrated lightweight direct-drive actuator for knee exoskeleton.</font></p>

<br>

### High Torque Density Actuator System
<br>
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Our custom designed compact rotary actuator system developed to drive the joints on an wearable exoskeleton or other mechanical structure for robot joints. It includes precise gear reduction system, state of the art brushless servo motors, 20-bits high accuracy magnetic encoder circuits, communication networks and powerful power electronics. All these are performance matched components which are integrated in an extremely compacted space. With state of the art high bandwidth field oriented control (FOC), the actuator system can provides very high dynamic range and smooth torque control.</font></p>
 
<p style="text-indent:2em"><font face="Arial" color = "black" size="4" style="line-height: 1.1">
Thanks to a series of mechanical, topological and electromagnetical motor optimization and high integration components manufacturing and assembling, compared with other commercial integrated servo solutions, our custom designed actuator system has an obviously advantages in high torque and power density.</font></p>
<br>
<div align="center"><img width="400" height="400" src="/images/toolbox/actuators/motor_3.jpg"></div>


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

<br>
### High torque density actuation test
<br>
<div align="center">
<iframe width="550" height="300"  src="https://www.youtube.com/embed/hh9O8kyhsyU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen> </iframe>
</div>
<br><br>
<!--
Some of the information contained in this web site includes intellectual property covered by both issued and pending patent applications. It is intended solely for research, educational and scholarly purposes by not-for-profit research organizations. If you have interest in specific technologies for commercial applications, please contact us [here](/contact.html).
-->

