# Operation Mask 2020

**Operation Name:** Opeartion-Mask-2020

**Action Order:** Mask is a MUST.

**Mission Data:** 2020-01-31 - unknown

### 1. Purpose:
The 2019 novel coronavirus (COVID-19), previously known as 2019-nCoV, is a contagious virus that causes respiratory infection and has shown evidence of human-to-human transmission, first identified by authorities in Wuhan, Hubei, China, as the cause of the ongoing 2019–20 Wuhan coronavirus outbreak.
<p align="center">
  <img height="500" src="https://github.com/globalcitizen/2019-wuhan-coronavirus-data/blob/master/data-sources/dxy/data/latest-animation.gif?raw=true">
</p>

This operation is immediately taken into action to make necessary medical precaution for further virus transmission as well as medical treatment to current patients. Cost optimization is applied to this protable edge system, this open-sourced repository can be repulicated for those fighters with all the best wishes. The [total hardware expenditure](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Shoppingcarts.png) is under $200, five times cheaper compared to the infrared thermometer.

The following project is **a real-time temperature measurement/mask-wearing detection disease control system**, built on Raspberry Pi 4B, PiCamera, IR temperature sensor, Google Cloud Platform (AutoML Vision, Storage, Big Query, Pub/Sub, Cloud Functions), digital segment display, and LCD display. The programming tools are pythons and TensorFlow Lite.

### 2. System Architect
![System Architect](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/system%20architect.png?raw=true)

This design is an end-to-end medical solution integrated with temperature detection, face recognition, edged-computing, real-time data transmission, and video streaming via Raspberry Pi and Google Cloud Platform.

### 3. System Evaluation
![System Architect](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Evaluation.png?raw=true)
The Machine Learning model uses total **301 images datasets** with **41 labelled masks**, trained by 274 labelled data, and tested by 27 images. The evaluation of mask-recognition model gives **precision of 97.5%**.

### 4. Demo
![Demo](https://github.com/0zz10/Operation-Mask-2020/blob/master/Images/Demo.gif)

**Demo Video**, Please check the full episode that I produced about this operation at https://youtu.be/RVai-bdd2Lc <br>
| Time Clips     | Scenarios of Demo Video | Results  |
| :-------: |:-------------:| :-----:|
| 02:40 | Video Streaming and Temperature Detection set up | ✓ |
| 02:50| Not Wearing Mask/ Human Body Temperature Detected | ✓ |
| 03:00  | Wearing Mask (N95) / Human Body Temperature Detected |  ✓ |
| 03:15 | Wearing Mask (medical mask) / Fever Detected    |    ✓ |
| 03:25 | Sample Images Test    |✓|
| 03:30 | Sample Video Test    |✓ |


### 5. Appendix
#### See [Final Report](https://github.com/0zz10/Operation-Mask-2020/blob/master/Final_Report.ipynb) for more information.

#### Follow [Steps Instruction](https://github.com/0zz10/Operation-Mask-2020/blob/master/steps_instructions.ipynb) for Raspberry Set up, AutoML Preparation, and Project Reproducing.

#### Competitive Products
Brain++ AI Body Temperature Monitor System by MegVII, released on February 7, 2020 (One week after **Operation Mask 2020** released)
<p align="center">
  <img height="350" src="http://n.sinaimg.cn/spider202025/640/w1280h960/20200205/e2f5-inzcrxs5862922.jpg">
</p>

*Souce:* <br>
https://megvii.com/en/news/ID?news_id=111 <br>
http://m.thepaper.cn/renmin_prom.jsp?contid=5793853&from=renmin
