# Operation Mask 2020

**Operation Name:** Opeartion-Mask-2020

**Action Order:** Mask is a MUST.

**Mission Data:** 2020-01-31 - unknown

### Project Information:
The 2019 novel coronavirus (COVID-19), previously known as 2019-nCoV, is a contagious virus that causes respiratory infection and has shown evidence of human-to-human transmission, first identified by authorities in Wuhan, Hubei, China, as the cause of the ongoing 2019–20 Wuhan coronavirus outbreak.

This operation is immediately taken into action to make necessary medical precaution for further virus transmission as well as medical treatment to current patients. Cost optimization is applied to this protable edge system, this open-sourced repository can be repulicated for those fighters with all the best wishes. The [total hardware expenditure](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/01 Shopping Carts.png) is under $200, five times cheaper compared to the infrared thermometer.

The following project is **a real-time temperature measurement/mask-wearing detection disease control system**, built on Raspberry Pi 4B, PiCamera, IR temperature sensor, Google Cloud Platform (AutoML Vision, Storage, Big Query, Pub/Sub, Cloud Functions), digital segment display, and LCD display. The programming tools are pythons and TensorFlow Lite.

### System Architect
![System Architect](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/system%20architect.png)

This design is an end-to-end medical solution integrated with temperature detection, face recognition, edged-computing, real-time data transmission, and video streaming via Raspberry Pi and Google Cloud Platform.

### System Evaluation
![System Architect](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Evaluation.png)
The Machine Learning model uses total **301 images datasets** with **41 labelled masks**, trained by 274 labelled data, and tested by 27 images. The evaluation of mask-recognition model gives **precision of 97.5%**

### Demo
**Demo Video**, Please visit https://youtu.be/RVai-bdd2Lc
![Demo](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Demo.gif)

**Demo Scenarios:**
1. Not Wearing Mask/ Human Body Temperature Detected
2. Wearing Mask (N95) / Human Body Temperature Detected 
3. Wearing Mask (medical mask) / Fever Detected         
4. Sample Images Test
5. Sample Video Test

### Appendix
#### See [Final Report](https://github.com/0zz10/Operation-Mask-2020/blob/master/Final_Report.ipynb) for more information

#### Follow [Steps Instruction](https://github.com/0zz10/Operation-Mask-2020/blob/master/steps_instructions.ipynb) for Raspberry Set up, AutoML Preparation, and Project Reproducing**

#### Competitive Products
Brain++ AI Body Temperature Monitor System by MegVII, released on February 7, 2020 (One week after **Operation Mask 2020** released)
<p align="center">
  <img height="300" src="http://n.sinaimg.cn/spider202025/640/w1280h960/20200205/e2f5-inzcrxs5862922.jpg">
</p>
*Souce:*
https://megvii.com/en/news/ID?news_id=111
http://m.thepaper.cn/renmin_prom.jsp?contid=5793853&from=renmin
