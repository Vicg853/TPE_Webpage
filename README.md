<div align="center" 
# POTAGER AUTOMATIQUE
![](https://github.com/Vicg853/TPE_Webpage/blob/8623e1b4afd346fe05b9452273d181ea8939a131/IMG_20190531_100248349_HDR.jpg)
</div>

### _A smart garden for a school project..._
... The project consists of the idea of a smart garden that would take care of a few lettuces. Sadly, most of the code, more specifically backend code that managed the decisions and the two ESP32 is lost. But the front-end webpage code with the project's video, images, and explanation is saved, and the website is live (the website is in French, as it was a French school) 

### Tecnologies used
- Node-Red on IBM Cloud, to make the decisions based on the conditions
- C++ to code the two ESP32 systems, using MQTT and Wi-Fi libraries to manage communication
- HTML, CSS, and JS on the client-side website: the website was used to explain the project, show the making of video and to see the live collected data
- C# and Xamarin framework to make a monitoring mobile app

A shortened version of the explanation in the webpage: for the project, two wooden boxes were made, the two, containing dirt and lettuces seeds at the start. The difference between these two boxes is, that, one of them, would maintain its initial build state, and let the lettuces grow naturally, meanwhile, the other one, would be smart.
The smart part of the box, contained two ESP32 connect to the Wi-Fi network and would send data to the code hosted on IBM Cloud. The data gathered was about: 
- soil moisture, 
- air moisture, 
- air temperature, 
- daylight/UV intensity and 
- rain status. 

An other sensor that didn't really did nothing in the actual garden, but helped us to monitor everything, was an I.P. camera that helped us look out for the growth of our little lettuces 🥬🥬

The data collected, plus the weather data got from the Cloud, was used to predict and control the actuators on the "little farm", these actions were: 
- closing or opening an acrylic roof, placed on top of the garden, controlled by two servo motors (for example in case of rain, that could damage the lettuces as they are fragile),
- turning on or off a UV light (for example, to maintain photosynthesis during the night, or help on cloudy days) and
- open or close a solenoid valve, to irrigate the lettuces (in the case for example, where the soil/air moisture is to low and the forecast points out that there is a low chance of rain in the 

As it was mainly a science project, to make the decision of what to use, we made some research about it, so:
- Why the two gardens: one where the very main objective was realized (making a smart garden), and one to compare, and give proof that the smart garden may be beneficial in plant growth, or maybe that it is not...
- Why to ESP32: one for the sensor and data gathering handling, one for actuators control
- Why these sensors and actuators: these are the most important things to look out for and control in a plant growth
- Why lettuce among all other plants: lettuces are very fragile and sensitive plants and need constant attention and care, so, if the garden works with these plants, it probably would work well with other, maybe more tolerant plants 
- - - -

#### The results?
This readme is getting more scientific info than code info, but let's just check the results of the project:
* In the end, the project worked, not at 100%, but it worked and proved its performance
* We ended up with some problems in the middle of the test and monitoring phase: the wooden casing of the electronics part, broke, and come water got in, but, we solved the problem by reinforcing the structure and protection against water. As well we had some energy supply issues, where one of the project's power supplies was making a part of the school building to go dark two times 😅
* In the end, around 7 to 8 weeks, the lettuces in the natural garden (not smart), didn't even present signals of growth, in the meanwhile, the smart garden, had just started presenting some little baby lettuces with around 1cm height
* Arriving at the end of the project, near the presentation date (3 to 4 weeks after), the natural garden, had some little lettuces that had grown, to about 1cm just as the starting of the smart one, and the smart one, had grown to about 6cm to 7cm. Which proved that they were growing faster. The smart one also presented a high number of little lettuces

- - - -

## Access
Access the [project's webpage](http://potagerautomatique.herokuapp.com/)
- - - -

## Some photos
![](https://github.com/Vicg853/TPE_Webpage/blob/94d7f2c4289a00a08c1e43cd578d03ccde1862a6/IMG-20190605-WA0009.jpg)
![](https://github.com/Vicg853/TPE_Webpage/blob/94d7f2c4289a00a08c1e43cd578d03ccde1862a6/IMG-20190623-WA0001.jpg)
![](https://github.com/Vicg853/TPE_Webpage/blob/94d7f2c4289a00a08c1e43cd578d03ccde1862a6/IMG-20190806-WA0002.jpg)

##License
_MIT_
