---
title: Snips Voice Interaction Base Kit
category: Grove/LED
bzurl: 
oldwikiname: 
prodimagename:
surveyurl: 
sku: 105020074
tags:
---

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/main_wiki.jpg)


This kit is the starter development kit for Snips Platform. The voice assistant is installed on the Raspberry Pi with the Seeed ReSpeaker 2-Mics Pi HAT, so that developers can easily get the development kit up and running and experience the Snips assistant with the Grove modules. The kit includes two Grove modules, Grove - Temperature & Humidity Sensor and Grove - Relay, which makes it possible to obtain environmental data and control the device’s ON and OFF states via voice commands.


<p style="text-align:center"><a href="https://www.seeedstudio.com/Snips_Voice_Interaction_Base_Kit.html" target="_blank"><img src="https://github.com/SeeedDocument/wiki_english/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>


## Feature 

- Out of the box ai development kit
- Easy to assemble
- Voice assistant

## Partlist

|Category|Part Name|Quantity|
|---|---|---|
|**Electronics**|Raspberry Pi3 B+|1|
||ReSpeaker 2-Mics Pi HAT|1|
||Grove – Relay|1|
||Grove - Temperature&Humidity Sensor (SHT31)|1|
||Speaker 6Ω 2W|1|
||MicroSD Card|1|
||Power adapter with Micro USB connector|1|
||Grove cable|2|
|**Acrylic**|Acrylic Base panel |1|
||Acrylic Protective cover for Relay|1|
||Acrylic Table stand |2|
|**Assembly components**|6mm,M2 full thread black hex nylon spacer |3|
||12mm,M2 full thread black hex nylon spacer |5|
||25mm,M2 full thread black hex nylon spacer |3|
||6mm,M2.5 full thread black hex nylon spacer |4|
||5mm,M2 carbon steel phillips screw |22|
||5mm,M2.5 nylon phillips screw |8|
||10mm,M3 carbon steel phillips screw|4|
||6mm,M2 full thread black hex nylon spacer |3|
||Blue rope|1|
||Screw driver|1|





## Quick Starter Guide

This guide shows the basic steps to build the out-of-the-box application. For more in-depth development technical documentation, please visit [https://docs.snips.ai/](https://docs.snips.ai/)


### Assembly steps:

The following picture is the overview of the assembly parts.

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s1.jpg)

---
Here the assembly parts are mounted on the base panel.


![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s2.jpg)

---

Then, all the electronic parts are mounted on the board.

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s3.jpg)

---

After that mount the Acrylic Protective cover on top of the Grove -Relay.


![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s4.jpg)

---

These 2 parts are used to make the Kit into a table stand.

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s5.jpg)


---

This is how it looks when the above 2 parts are connected to the base panel.

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s6.jpg)


---

Finally, its ready to play with Snips. 

![](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/img/s7.jpg)



The kit provides two ways of placement. It can either be placed on a horizontal surface as a stand or can be hung on a wall using wires or thread.
Please be careful with the Relay when the kit is powered on since the working voltage will be high.


###　Start playing!

- 1. Power the kit by the default power adapter in the kit or use a 5V-2A DC adapter with a Micro USB connector.

- 2. The next step is installing the Snips assistant into the Raspberry Pi. To save your setup time, the MicroSD card in the kit has been flashed with the full functional system image, which means the Snips assistant is ready for your trigger words. We strongly suggest you to study the step by step installation guide by visiting : https://docs.snips.ai/getting-started/quick-start-raspberry-pi and learn the sam tool in command line.

- 3. Trigger the assistant by saying “Hey-snips”, and follow the command:


Command	| Action
---|---
What’s the temperature?	| Responds with the current temperature
What’s the humidity? |	Responds with the current humidity
Turn the relay on.	| The relay closes and the red LED turns on.
Turn the relay off.	| The relay opens and the red LED turns off.


## Resource

- **[PDF]** [User manual](https://github.com/SeeedDocument/Snips_Voice_Interaction_Base_Kit/raw/master/res/User%20manual.pdf)