---
layout: post
title: "Constraints & Requirements"
date: 2018-10-30 11:00:00 +0800
categories: [log]
---


|Spec #|D/W|Date added/modified|Description|Specifications|Responsibility|Test|
|:---------|:------|:-----------|:-----------|:-----------|:------------|:-----------|
|1         |D      |2018-10-31  |Simple operation of watercraft|**(specify controls)**|Selwyn|-|
|2         |D      |2018-10-31  |Streamlined bodyshape|Reduce drag as much as possible.<br> Achieve drag coefficient < 0.3|Selwyn|-|
|3         |D      |2018-10-31  |Able to carry a heavy payload|Max payload weight = 10 kg|Selwyn|Add weights|
|4         |W      |2018-10-31  |Able to be seen from afar|**(How far is far, state lighting conditions)**|Elvis|Simple majority voting|
|5         |W      |2018-10-31  |Swappable sensor modules|(Suggested usage of "keying")|Elvis|Check whether data connection is common|
|6         |W      |2018-10-31  |Can return to original resting position when capsized.|-|Selwyn|Test it in a rasin/basin/pool with a prototype|
|7         |D      |2018-10-31  |Electronics insulated from water|(meters, IP rating, hours of immersion)|Selwyn|Test it in a rasin/basin/pool with a prototype|
|8         |D      |2018-10-31  |Able to provide real time feedback for sensor data|Delay < 500ms (State frequency etc.)|Glenn|Test it with Arduino before attaching to submarine. (Test in air and underwater)|
|9         |D      |2018-10-31  |(State Required Operating Speed m/s)|**(Stating of range possible)**|Glenn|-|
