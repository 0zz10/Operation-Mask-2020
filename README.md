# Operation Mask 2020

**Operation Name:** Opeartion-Mask-2020

**Action Order:** Mask is a MUST.

**Mission Data:** 2020-01-31 - unknown

**Operation Information:**
The 2019 novel coronavirus (2019-nCoV), also known as the Wuhan coronavirus, is a contagious virus that causes respiratory infection and has shown evidence of human-to-human transmission, first identified by authorities in Wuhan, Hubei, China, as the cause of the ongoing 2019–20 Wuhan coronavirus outbreak.

This operation is immediately taken into action to make necessary medical precaution for further virus transmission as well as medical treatment to current patients.

The following project is **a real-time temperature measurement/mask-wearing detection disease control system**, built on Raspberry Pi 4B, PiCamera, IR temperature sensor, Google Cloud Platform (AutoML Vision, Storage, Big Query, Pub/Sub, Cloud Functions), digital segment display, and LCD display. The programming tools are pythons and TensorFlow Lite.

**System Architect**
![System Architect](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/system%20architect.png)

The mask recognition is self-labelled over 300 mask images, fully trained by Google Cloud Platform AutoML Vision, and deployed locally on edge device Raspberry Pi 4B


**See [Final Report](https://github.com/0zz10/Operation-Mask-2020/blob/master/Final_Report.ipynb) for more information**

**Follow [Steps Instruction](https://github.com/0zz10/Operation-Mask-2020/blob/master/steps_instructions.ipynb) for Raspberry Set up, AutoML Preparation, and Project Reproducing**

**Demo Video**, Please visit https://youtu.be/RVai-bdd2Lc
![Demo](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Demo.gif)

**Demo Case:**
1. Not Wearing Mask/ Human Body Temperature Detected    
2. Wearing Mask (N95) / Human Body Temperature Detected 
3. Wearing Mask (medical mask) / Fever Detected         
4. Sample Images Test
5. Sample Video Test

Competitive Products: Brain++ AI Body Temperature Monitor System by MegVII
![Similar](http://n.sinaimg.cn/spider202025/640/w1280h960/20200205/e2f5-inzcrxs5862922.jpg)

<p align="center">
  <img height="300" src="http://n.sinaimg.cn/spider202025/640/w1280h960/20200205/e2f5-inzcrxs5862922.jpg">
</p>
*Souce:*
https://megvii.com/en/news/ID?news_id=111

http://m.thepaper.cn/renmin_prom.jsp?contid=5793853&from=renmin
