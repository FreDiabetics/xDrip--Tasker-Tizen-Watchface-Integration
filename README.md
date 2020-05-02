# xDrip + Watchmaker Project - xDrip Glucose - via Watchmaker + Tasker on your Samsung * or Android Wear *² smartwatch 

- [Watchmaker Profil](https://getwatchmaker.com/user/Bkd6tbYxr)
- [Apps](#apps-aus-dem-playstore)  
- [Wear OS](#android-wear)
- [Berechtigungen](#permissions)
- [English Version](#english) or scroll down 

    
*im moment funktionieren nur die Watchfaces: [xdrip Diabadass](https://getwatchmaker.com/watch/sHyeOJm5XKL), [xDrip Sugar Guardian](https://getwatchmaker.com/watch/sHJwuuKQtL), [xDrip Scale Me](https://getwatchmaker.com/watch/sBJh9mqmYI), [xDrip Clean One] Alle anderen werden in den nächsten Wochen auf diese neue Anleitung angepasst und sind dann aiuch verfügbar.

![myimg](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/glucose_quarantine_preset_1_tap_actions.png) ![myimgb](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/Watchfaces/content/pictures/glucose_quarantine_preset_2_graphview_xtrastatusline.png)

**Zuerst muss die aktuellste xDrip Nightly installiert werden die gibts [hier](https://github.com/NightscoutFoundation/xDrip/releases)**
    
Danach muss der lokale Broadcast aktivieren werden,
das geht in den Einstellungen im Menü "Inter-App Einstellungen" 
[hier](https://imgur.com/gallery/Se9Psgp) ist zu sehen wie das geht. 


## Apps aus dem Playstore 


**Bitte alle herunterladen und installieren.**

-    [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=de) ~ 3.59€ **einmalig**

-    [AutoApps](https://play.google.com/store/apps/details?id=com.joaomgcd.autoappshub)

-    [AutoTools](https://play.google.com/store/apps/details?id=com.joaomgcd.autotools) (Nur über die App AutoApps zu kaufen, muss gekauft werden) ~ 2,79€ **einmalig**

-    [Watchmaker](https://play.google.com/store/apps/details?id=slide.watchFrenzy)

-    [Watchmaker Premium](https://play.google.com/store/apps/details?id=slide.watchFrenzy.premium) ~ 6.99€ **einmalig**


Nachdem alle Apps gedownloadet sind, wird Auto Apps geöffnet, 
hier kauft ihr jetzt die AutoTools Lizenz für 2.79€. 
Öffnet Tasker und AutoTools einmal und bestätigt bitte alle Berechtigungen nach denen geragt wird.
Es wird auch eine Aufforderung zur Abschaltung der Akku-Optimierung angezeigt, meist aber erst wenn ihr die App über den Zurück button wieder beendet.
Wenn ihr eine Smartwatch von Samsung benutzt dann braucht ihr zusätzlich noch eine dieser beiden Apps aus dem Galaxy Store.
     
     -Watchmaker Companion 2.99€ http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzyw


## Android Wear






## Permissions


Nachdem alle Apps nun erfolgreich installiert wurden müssen diese
noch die notwendigen Berechigungen bekommen um alles von A nach B 
zu transportieren.

Das geht hier:
Einstellungen >Apps > Spezieller Zugriff.
Hier sind mehrere Menüpunkte zu beachten.

Wichtig sind folgende Punkte:
- Akku-Verbrauch optimieren       -_Schalter für AutoTools, Watchmaker, Tasker deaktivieren_
- Geräteadministrator-Apps         -_Schalter für Tasker aktivieren und bestätigen_
- Am-Anfang anzeigen                -_Schalter für AutoTools, Tasker aktivieren_
- Systemeinstellungen ändern         -_Schalter für AutoTools, Tasker aktivieren_
- Apps beim Datensparen zulassen      -_Schalter für AutoTools, Watchmaker, Tasker aktivieren_
- Zugriff auf Nutzungsdaten            -_Schalter für AutoTools, Tasker aktivieren_

Alle auf diesem [Bild](https://imgur.com/a/IiniWvW) 
gelb markierten Punkte sind wichtig und zu überprüfen

Anschließend müssen noch die App spezifischen Berechtigungen aktiviert werden.

Das geht unter Einstellungen/Apps
Hier einfach die zuvor installierten Apps suchen,
anklicken und anschliessend Berechtigungen auswählen. 
Hier müssen alle Schalter aktiviert werden. 
Das muss für folgende Apps gemacht werden: 

- AutoTools
- Tasker
- Watchmaker

Öffnet nun AutoTools und Tasker einmal und bestätigt alle Fragen nach Berechtigungen die angezeigt werden, 
auch solltet ihr die benachrichtigung im nicht stören modus aktzeptieren, sonst kann weder Tasker, 
AutoTools oder Watchmaker richgit arbeiten wenn ihr diesen eingeschaltet habt. 
Ihr habt zwar im Vorfeld schon alle Berechtigungen aktiviert es kann trotzdem sein das euch die Meldungen angezeigt werden.

Die Apps sind nun alle installiert und ihr könnt das Tasker Projekt von mir importieren.

Klickt auf den folgenden Link, ihr werdet in euren Browser auf die Taskernet Seite weitergeleitet.

     https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Project%3AxDrip%2B+Watchmaker+Project 

Unter der Beschreibung befindet sich ein grüner Button "Import" den drückt ihr, anschließend öffnet sich Tasker und es erscheinen nacheinander 2-3 Meldungen die ihr mit "Yes/Ja" bestätigt.
Nun erscheint unten neben dem kleinen Häuschen ein xDrip Icon. Das ist das Zeichen dafür das alles hingehauen hat. 

Hier seht ihr wo wie ihr den Lokalen Broadcast aktiviert damit xDrip die Werte für Tasker verfügbar macht, sehr wichtig!! sonst läuft nix!
xDrip local Broadcast: 

    https://imgur.com/gallery/Se9Psgp  

Am Ende müsst ihr noch die EInstellungen im Watchmaker Watchface einstellen. dazu tippt ihr zweimal schnell auf das watchface es öffnet sich die watchmaker watchface Übersicht, links und rechts am Bildschirmrand erscheinen Pfeil mit denen ihr navigieren könnt. drück nach Links um die Einstellungen zu erreichen. Die einstellungen "Update Heart rate" und "Update Steps" stellt ihr bitte auf "On every Watch wake up" dann stellt ihr die Einstellungen "Enable Transisitions", "Enable Shaders" und "Enable Text Effects" auf ENABLE.

Wenn das erledigt ist seit ihr fertig und ihr könnt nun das Watchface entweder [hier direkt downloaden](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/tree/master/Watchfaces)

Oder ihr sucht es in meinem Watchmaker Profil. Alle bisher erstellten Watchfaces werden in den nächsten Monaten auf dieses Anleitung angepasst. Das heisst es werden am Ende alle bisher veröffentlichten Watchfaces aus meinem Watchmaker Profil mit dieser Anleitung zu benutzen

 





# English


    **What you need: xDrip, Watchmaker, Tasker, AutoTools**

    **The watch faces can be found here:** 

    **https://getwatchmaker.com/user/Bkd6tbYxr** 

at the moment only the watch faces work: xDrip Diabadass mg / dl / mmol / l, xDrip Sugar Guardian mg / dl / mmol / l and xDrip Glucose Graph mg / dl / mmol / l
All others will be adapted to this new manual in the next few weeks and will then also be available.

    **Please install the latest xdrip nightly from here:** 
    https://github.com/NightscoutFoundation/xDrip/releases
    
Then you have to activate the local broadcast. This is done in the settings in the "Inter-App Settings" menu.
here you see exactly what you have to do so that xDrip makes the values available for Tasker, very important !! otherwise nothing works!
xDrip local broadcast: 

    **https://imgur.com/gallery/Se9Psgp**


### Apps from the playstore ~ Please download and install them all.

    **-Tasker 3.59 € https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=de**

    **-AutoTools € 1.79 (only to be purchased via the AutoApps app, must be purchased) https://play.google.com/store/apps/details?id=com.joaomgcd.autotools**

    **-AutoApps https://play.google.com/store/apps/details?id=com.joaomgcd.autoappshub**

    **-Watchmaker https://play.google.com/store/apps/details?id=slide.watchFrenzy**

    **-Watchmaker Premium 6.99 € https://play.google.com/store/apps/details?id=slide.watchFrenzy.premium**

After you have downloaded all the apps, the first thing you do is open AutoApps. This app is there to purchase the full versions of Tasker’s plugins. You can now run the AutoTools license for € 1.79. If the purchase has been successfully completed, you can tell that the AutoTools is no longer grayed out but is now shown in color.

Open Tasker and AutoTools once and please confirm all permissions you are asking for. A request to switch off the battery optimization is also displayed, but usually only when you exit the app with the Back button.
No matter if you have a Samsung Smartwatch with Tizen OS or a Wear OS by Google Smartwatch. You definitely need the apps from the Playstore. All prices are only payable once. NO SUBSCRIPTION!

If you use a Samsung smartwatch, you also need one of these two apps from the Galaxy Store.
For the Samsung watch models GearS2, Gear S3 and Galaxy Watch (all versions) after installing you can find and select the Watchmaker Watchface like all other watch faces in the watch face overview on the watch or in the Galaxy Wearable app:
    
    **-Watchmaker Companion Legacy 2.49 € http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzy**

For the new Galaxy Active and Galaxy Active 2 models:

    **-Watchmaker Companion 2.99 € http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzyw**

For the Wear OS by Google Smartwatches you open after installing the Watchmaker app on the smartphone, you scroll down the Playstore on your Smartwatch there. Here you will find the Watchmaker Watchface installs it, then you can find and select it as usual directly from the watch in the Watchface overview or of course also from the Wear app on the smartphone.
ALL PRICES ARE FROM 03/17/2020 THESE PRICES WERE NOT COLLECTED BY ME
If you have installed all apps, you basically only have to grant the permissions for Tasker and AutoTools.

To do this, go to Settings, Settings> Apps> Special Access on your smartphone.
Here you will now see several menu items.

Starts at the first, goes through all menu items that I have marked yellow in this picture

    https://imgur.com/a/IiniWvW


Then you have to activate the app specific permissions.

You can do this under Settings / Apps there you will find all installed apps
Finds the previously installed apps from the list and then goes to Permissions. There you activate all switches.
You do that
-AutoTools
-Tasker
-Watchmaker

Now open AutoTools and Tasker once and confirm all questions about permissions that are displayed, you should also accept the notification in do not disturb mode, otherwise neither Tasker, AutoTools or Watchmaker can work properly if you have activated it.
You have already activated all permissions in advance, it may still be that the messages are displayed to you.

The apps are now all installed and you can import the Tasker project from me.

Click on the following link, you will be redirected to the Taskernet page in your browser.

       https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Project%3AxDrip%2B+Watchmaker+Project

Under the description there is a green button "Import" which you press, then Tasker opens and 2-3 messages appear one after the other which you confirm with "Yes".
Now an xDrip icon appears next to the little house. This is the sign that everything has worked.

At the end you have to adjust the settings in the Watchmaker Watchface. To do this, quickly tap the watchface twice. The watchmaker watchface overview opens, and arrows appear on the left and right of the screen with which you can navigate. press left to reach the settings. Please set the settings "Update Heart rate" and "Update Steps" to "On every Watch wake up" then you set the settings "Enable Transisitions", "Enable Shaders" and "Enable Text Effects" to ENABLE.

When this is done you are ready and you can now download the watchface [here directly](https://github.com/wagnefrede/xDrip--Tasker-Tizen-Watchface-Integration/tree/master/Watchfaces)

Or you look for it in my Watchmaker profile. All watch faces created so far will be adapted to this manual in the next few months. That means in the end all watch faces published from my Watchmaker profile will be used with these instructions



-    **-*Galaxy Gear 2, 3, 3Frontier, Galaxy Watch 42mm/46mm, Galaxy Watch Active, Galaxy Watch Active 2 *² For Android Wear Information please visit the Watchmaker Wiki [here](https://watchmaker.haz.wiki/get_on_watch)**
