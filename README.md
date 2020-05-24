# xDrip Glucose Watchface - for Tizen OS(Samsung) Smartwatches*¹ and Wear OS (former Android Wear) Smartwatches**²





   **-[Basics](#basic-glucose-functionaility)**

   **-[Different Functions](#multifunctional)**
   
   **-[Glucose Graph + AndroidAPS Statusline for Loop Info](#glucose-graph-and-androidaps-statusline-for-closed-loop-information)**
   
   **-[Ucolor Set](#choose-your-own-favourite-color-with-the-ucolor-colorset)**
   
   **-[Support](#contact)**
   
   **-[Future Projects](#future-projects)**

   **-[Special Thanks](#special-thanks)**

   **-[Additional](#additional)**

   **-[Watchmaker Profile](https://getwatchmaker.com/user/Bkd6tbYxr)**

![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/active_preset.png) ![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/active_graphview.png)




### GLUCOSE GRAPH & ANDROIDAPS STATUSLINE FOR CLOSED LOOP INFORMATION 

![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/4%20watches.png)

### Multifunctional
#### DISPLAY DEVICE AND SENSOR AGE + CHANGE GLUCOSEUNITS WITH A SINGLE TAP
#### (read watchface description for the depending tap actions)

![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/3%20watches%20.png)

### CHOOSE YOUR OWN FAVOURITE COLOR WITH THE BUILT-IN UCOLOR COLORSET

![myIMG](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/ucolor_set.png)


<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="UX3LKXVXQFPG6" />
<input type="image" src="https://www.paypalobjects.com/en_US/DK/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_DE/i/scr/pixel.gif" width="1" height="1" />
</form>


       
# Basic Glucose Functionaility

-  **{tXSGV} - _latest Glucose Reading_** 

   **This shows the last recieved Glucosevalue, 
   you can change the glucosunits from mmg/dl to mmol/L 
   on every watchface. (Only the marked Watchfaces in the WIKI
   are supporting this feature.**

-  **{tXDELTA} - _Delta_**

   **This is the last delta - change from last reading to current reading**
   
-  **{tTREND} - _Trendarrow_**

   **The Trendarrow is related to the delta value above it doesn't 
   show the predicited glucosetrend**

-  **{tXMINS} - _minutes left since last reading_**

   **The timestamp that gives you information about how much 
   time has left since the last glucosereading**
   
-  **Glucose Graph**

   **My Tasker project is adjusted to update values every 1 minute. 
   The Watchfaces itself are adjusted to fetch data on every watch 
   bright or when you click the depending Tap Action on the Watchface. 
   Some Watchfaces have scalable Graphs. f.e: [xDrip Scale Me](https://getwatchmaker.com/watch/sBJh9mqmYI)
   is scaleable from 1,5h, 3h and 6h** 

- **{tXNOISE} - _noiselevels_**
    
   **Current noise level for your sensorreadings**
   
- **{tXINSULIN} - _bolus-insulin_**

   **nsulin you added in xDrip for bolus**
   
- **{tXSAGE} * _sensor age_**

   **Current sensor age**
   
- **{tXDEVICE} - _xDrip+ source_**

   **Your xDrip source, _f.e.:G6 Native, Share, Follower, Nightscout _**

-  **{tXSLINE} - _AndroidAPS Statusline_**

   **For additional Closed Loop Information from AndroidAPS, this can be splitted in two seperate pieces just use {tXSLINE1} and {tXSLINE2} instead**

***





###  Contact:

#### **[G-Mail](<typ1.diafreddy@gmail.com>)**
#### **[Facebook](https://www.facebook.com/FREDERIKWAGNER311991)**
#### **[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7BVRLERC9NBYA&source=url)**

#### **If you find my project useful, I will appreciate if you donate me few bucks for further development or buy me a glass of beer or wine 🍷. Thanks for your support**







### Stay Healthy!! Watch Your Glucose ;)








***
### Future Projects
##### _these watchfaces display loop information from androidaps via nightscout. this is a tasker project which is currently under development._

### xDrip AndroidAPS Diabadass 
![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/androidaps%20diabdass.png)


### xDrip AndroidAPS Gradient Bubbles 
![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/mockup/androidaps%20gradient%20bubbles.png)


##### these watchfaces display loop information from androidaps via nightscout. this is a tasker project which is currently under development.





# Special Thanks

**At this point I would like to thank my friend [Jon Fawcett](https://github.com/jonfawcett) for providing me with the basic things. He wrote a guide to display the night scout values of an iOS loop to a Samsung smartwatch. If you want to know how to get this done, read on [here](https://github.com/jonfawcett/Nightscout-Tasker-Tizen-Watchface-Integration)**

***

**_Instructions in the [Wiki]( https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/wiki) or [here](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/wiki/1.1-Apps-&-Settings-(EN))_**



**-_at the moment only these watchfaces work: [xdrip Diabadass](https://getwatchmaker.com/watch/sHyeOJm5XKL), [xDrip Sugar Guardian](https://getwatchmaker.com/watch/sHJwuuKQtL), [xDrip Scale Me](https://getwatchmaker.com/watch/sBJh9mqmYI), [xDrip  Clean One](https://getwatchmaker.com/watch/sB1htvPmtI), [xDrip Galaxy Watch](https://getwatchmaker.com/watch/sBk62m8fKL), [xDrip Sugarlicious](https://getwatchmaker.com/watch/sH1Dt3mXKU) und [xDrip Glucose Quarantine](https://getwatchmaker.com/watch/sSJp9UdotU) 
  All other watchfaces will be adapted to the new manual in the next few weeks and will then be available in a new design._**
  




####  Additional

**-  *¹ _Supported : Tizen OS Smartwatches (Samsung): Samsung Gear Live, Samsung Gear Sport, Samsung Gear S2, Samsung Gear S3, Samsung Gear S3 Frontier, Samsung Galaxy Watch, Samsung Galaxy Watch Active 1/2. Check [this](https://getwatchmaker.com/)_**
**-  *² _Supported [Wear OS by Google](https://wearos.google.com/#find-your-watch) (former Android Wear) Smartwatches: check [this](https://getwatchmaker.com/)_**


