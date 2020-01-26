For xDrip you need of course only xDrip profile and the task
For AAPS you need both xDrip profile / task and AAPS profile / task.

As a reminder AAPS / AndroidAPS) is used to build a closed-loop with your CGM sensor. if you have AAPS so far
not used then you only need the TASK and the profile of xDrip. Everything that has to do with AAPS you can ignore.

What you need:

Apps from the Playstore:

-Tasker 3.59 € https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en 

-AutoNotification https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification&hl=en_US 

-AutoNotification Unlock Key 2.39 € https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification.unlock&hl=en 

-Watchmaker https://play.google.com/store/apps/details?id=slide.watchFrenzy 

-Watchmaker Premium 6.99 € https://play.google.com/store/apps/details?id=slide.watchFrenzy.premium 

Whether you have a Samsung Smartwatch with Tizen OS or a Wear OS by Google Smartwatch. The apps from the Playstore you need in any case.
All prices are payable only once. NO ABO!


If you use a Samsung Smartwatch you will also get one of these two apps from the Galaxy Store.

For the Samsung watch models GearS2, Gear S3 and Galaxy Watch (All versions) after installation you can find and select the Watchmaker 
Watchface like all other Watchfaces in the 
Watchface overview on the watch or in the Galaxy Wearable App:
 
-Watchmaker Companion 2.49 €
http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzy

For the new models Galaxy Active and Galaxy Active 2:

-Watchmaker Companion 2.99 €
http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzyw

For the Wear OS by Google Smartwatches, after you install the Watchmaker app on your smartphone, you will be able to scroll down the
Playstore on your smartwatch. Here you will find the Watchmaker Watchface installs it, then you can find it as usual directly from the 
clock in the Watchfaceübersicht and select odewr of course from the Wear App on the smartphone.

ALL PRICES ARE FROM 03.11.2019
THESE PRICES WERE NOT RAISED BY ME

You need to turn off the automatic battery optimization for your smartphone. Tips can be found here. www.dontkillmyapp.com After that, 
you'll need to turn off automatic battery optimization for all apps you've installed in the guide.

Settings and permissions for AutoNotification, Tasker, and Watchmaker:

The first thing you do now in your smartphone: Settings / Apps / Autonotification then permissions. There activate all switches.
So you do the same for Watchmaker: Settings / Apps / Watchmaker / Permissions
Activate all switches here as well
If you have all the apps installed on your smartphone, you first open AutoNotification.
 Your smartphone will start when you ask or ask for permissions when you quit AutoNotification but please accept it.
 Please also disable the battery optimization!
There you press on "Notification Interception" then on "Ignore Apps"
Here you have to check all apps except xDrip + and AAPS
You have already granted the permissions at the beginning. Another permission activates her while you set up Tasker.
AutoNotification is now set up

Very important so that Tasker gets the necessary data from AutoNotification you have to turn this on, once you have activated since then also equal all rights for Tasker equal.
I am using a Samsung smartphone with One UI when using another smartphone, this step may differ.
In addition you go in your Smartphone on Settings / Apps here you click on top right on the 3 points and click on "special access". Here you can see a list of entries that is important for the data transfer. it's about the entries

-Battery Optimize Optimize Switches for AutoNotification and Tasker DEACTIVATE
-Device Administrator Apps ENABLE Switch for Tasker
-Do Not Disturb permission to enable tasker switch
-System change settings ACTIVE switch for Tasker
-Access Notifications ACTIVATE switch for AutoNotification and Tasker
-Allow apps to save data Disable the AutoNotification and Tasker switches
-Access to usage data ACTIVATE switch for Tasker

Then go to Settings / Accessibility below "Installed Services" below scroll down and activate Tasker.

Remaining Tasker permissions:
Next, open Tasker. For Tasker to work properly, please first turn the language over to English. To activate the change, press the 
3 dots on the top right to open the menu, then on Exit Tasker, then your Tasker will open directly again.
To abbreviate the whole I have created screenshots that should explain everything with questions.
To do this, after you open Tasker, click on the 3 dots in the upper right corner. The menu opens. You click on "More" then on 
"Android Settings" here you will find several entries that bring you to the permissions. You click on each entry one after the other.
Then you activate the permission by activating a switch or pressing a button. Is different for each entry. 
If you do not know how to find pictures here. https://imgur.com/gallery/HIDsbm1 
Then Tasker is ready.

Now that all apps are set up, you can now import the required Tasker profiles and tasks. You have to be careful to import 
everything in the right order. Always first the task and then the associated profile.
You click on the link for the task, then an internet page opens. On this you will find a green button with the inscription
"IMPORT" if you pressed it you will be forwarded to Tasker. Here you will be asked if you want to import the task or the
profile and then activate it immediately. You click on both "YES" You do that with everyone



1. FIRST IMPORT xDrip+ Task: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Task%3AxDrip%2B%2FWatchmaker+VARS

2. xDrip+ Profile: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Profile%3AxDrip%2B%2FWatchmaker

3. FIRST IMPORT AndroidAPS Task: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Task%3AAndroidAPS%2FWatchmaker+VARS

4. AndroidAPS Profile: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Profile%3AAndroidAPS%2FWatchmaker


Now all tasks and profiles are imported and activated. 
Open Tasker and click on the tab "TASKS" at the top then "VARS xDrip ........" at the bottom there is a "Play-Button" press it and 
pay attention to the green dots that appear next to the variables. Press the Back button on the top left and then do the same with 
"VARS AAPS ......." Afterwards you have to end both xDrip and AAPS once. In addition you go in the Smartphone on 
Settings / Apps / AAPS there you press on "Stop force" You do the same for xDrip + as well. Settings / Apps / xDrip + "Force stop"
ATTENTION DOES NOT MAKE THIS DURING A SENSOR WARM UP THIS MAY CAUSE PROBLEMS !!!!!
After doing this for both apps, please open it once.

Now all variables should be displayed successfully. Take a look.
Open Tasker and click on the tab in the upper right corner
"VARS" if you have only imported the xDrip TASK and the xDrip profile then you will find 9 entries here.
If you have imported the TASKS and profiles for xDrip and AAPS then there are 38.

If this is not the case, repeat the process with the play button again.

FOR TIME SMARTWATCHES IMPORTANT!
You still need to make a few adjustments on the clock. To do this, tap twice on the Watchface. Now the settings open. You can tell 
by the fact that an arrow appears on the left and right. Go to the right to the last synchsonized Watchfaces and to the left to the 
settings.
Here you will find the necessary Bildder to make the right settings. https://imgur.com/P3iLEOY

You´ll find my selfmade Watchfaces in Watchmaker on my profile. Here is a link for it:
https://getwatchmaker.com/user/Bkd6tbYxr 


Thank you for the interest and have fun with that. 


If you want to buy me a coffee through PayPal:

https://www.paypal.me/diafreddy 



Add variables in Watchmaker:

To build your own Watchface do the following:
Open Watchmaker and click on the 3 dots in the top right corner and then on "NEW WATCH"
Then you see a "plus button" presses it and then you choose "TEXT". Now you can add the first variable. Tasker variables are always
written in capital letters and in this format {t ....}. For the glucose value, type in {tGLUCOSE} and press OK the ad has now been 
added to the Watchface. Below is a list of all the variables you can use to add values from xDrip + and AAPS.

Here in the Watchmaker Wiki you will also find everything you need to know to build Watchfaces. 
Have a look https://watchmaker.haz.wiki/  


List of all Variabels:

xDrip+:
xDrip +:
{tGLUCOSE} 			glucose value with trend arrow
{tGLUCOSE11} 		glucose value without trend arrow
{tBGTIME} 			Time stamp of the glucose value
{} TDelta} 			Delta
{tDELTAA} 			Delta as a number without the words "delta:" and "mg / dl"

AAPS:
{tAVtERAGE}
{tAAPSGLUCOSE} 		Glucose value without trend arrow
{tAVERAGES}			 15 minutes average
{tAVERAGEL}			 40 minutes average
{tPUMPSTATUS} 		pump status
{tAAPSTIME}			 Time stamp of the glucose value
{tBASAL}
{tBASALRATE}			 basal rate
{tBASALPROFILE}		 basal profiles
{tTBR} 				basal rate status
{tIOB} 				insulin on board
{tCOB} 				Carbs On Board
