---
permalink: /projects/2016-11-5-4th-compitition
title: "4th International UAV Innovation Grand Prix"
author_profile: false
layout: compress
---

<h1>The 4th International Unmanned Aerial Vehicle(UAV) Innovation Grand Prix (UAVGP)</h1>
<h1>中航工业杯第四届无人机大赛</h1>
<!-- <img src="../images/favicon-16x16.png" alt="项目A" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/> -->

<!-- 添加空行： -->
<br>


## Competition description
<!-- 下面的内容，分成3个部分，第一部分是项目背景介绍，第二部分是项目内容介绍，第三部分是项目成果展示。 要求：文字往中间聚拢一些，不要太宽。-->
<!-- <div style="text-align: justify"> -->
- [The 4th International Unmanned Aerial Vehicle(UAV) Innovation Grand Prix (UAVGP)](http://www.uavgp.com.cn/En/) was sponsored by [Goertek Inc.](http://www.goertek.com/en/index.html) and [Aviation
Industry Corporation of China (AVIC)](http://www.avic.com/en/index.shtml). 

- Open-sourced resources: **Github**: [SIA-UAVGP](https://github.com/SIA-UAVGP)

- In **rotary-wing UAV(JX) group**, the competition is designed as a "**Precision Agriculture**" scenario --– Fruit trees in a farm are suffering from pests and disease, and the various pests have different resistances against particular pesticides. Agriculture and forestry experts will send rotary-wing UAVs to successfully eradicate all the pests by screening for effective pesticide type and spraying targeted pests.

<img src="../images/uavgp2016_rule.png" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>

<img src="../images/uavgp2016.jpg" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>

- "Precision Agriculture" examines precise and efficient operation of a rotary-wing UAV in
autonomous takeoff and landing, obstruction avoidance, crop disaster identification, automatic
program operation, pesticide replenishment and spray.



## System Structure

The drone, called `SIA Sparrowhawk`, is created using [DJI Spreading Wings S1000+ Octocopter](https://www.dji.com/spreading-wings-s1000) as the basic platform, [pixhawk](http://pixhawk.org/) as the controller of the drone and [Intel NUC](https://www.intel.com/content/www/us/en/products/boards-kits/nuc.html) as the companion computer to deal with Computer Vision problems and send position and velocity commands.

The [MAVROS](https://dev.px4.io/en/ros/mavros_installation.html) package enables MAVLink extendable communication between the companion computer (**Intel NUC**) running ROS and MAVLink enabled autopilots (**pixhawk**).


<img src="../images/uavgp2016_system_structure_hardware.PNG" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>

<img src="../images/uavgp2016_system_structure_software.PNG" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>

## 3 PX4 Controller Structure

<img src="../images/uavgp2016_PX4_structure.PNG" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>

<img src="../images/uavgp2016_Project_structure.PNG.PNG" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>


## 4 Competition Result
My group won the **first prize**.
<img src="../images/uavgp2016_score.jpg" style="width:40%; max-width: 800px; display: block; margin: 0 auto;"/>



## 5 Videos

[Preliminary (预赛)](http://v.youku.com/v_show/id_XMzIwNzgyNTU4NA==.html?spm=a2h3j.8428770.3416059.1#paction)
<embed src="http://player.youku.com/player.php/sid/XMzIwNzgyNTU4NA==/v.swf" quality="low" width="498" height="510" align="middle" allowScriptAccess="always" allowFullScreen="true" mode="transparent" type="application/x-shockwave-flash">

[Final（决赛）](http://v.youku.com/v_show/id_XMzIwNzgzODQ5Mg==.html?spm=a2h3j.8428770.3416059.1)
<embed src="http://player.youku.com/player.php/sid/XMzIwNzgzODQ5Mg==/v.swf" quality="low" width="498" height="510" align="middle" allowScriptAccess="always" allowFullScreen="true" mode="transparent" type="application/x-shockwave-flash">








