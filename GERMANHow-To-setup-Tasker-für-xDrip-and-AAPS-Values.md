Für xDrip benötigt ihr natürlich nur xDrip Profil und den Task 
Für AAPS benötigt ihr sowohl  xDrip Profil/Task als auch AAPS Profil/Task.

Zur Erinnerung AAPS /AndroidAPS) wird benutzt um zusammen mit eurem CGM-Sensor einen Closed-Loop zu bauen. wenn ihr AAPS also bisher
nicht benutzt dann braucht ihr auch nur den TASK und das Profil von xDrip. Alles was mit AAPS zutun hat könnt ihr ignorieren.

Was ihr braucht:

Apps aus dem Playstore: 


-Tasker 3.59€  https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=de 

-AutoNotification  https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification&hl=de 

-AutoNotification Unlock Key 2.39€ https://play.google.com/store/apps/details?id=com.joaomgcd.autonotification.unlock&hl=de 

-Watchmaker https://play.google.com/store/apps/details?id=slide.watchFrenzy 

-Watchmaker Premium 6.99€ https://play.google.com/store/apps/details?id=slide.watchFrenzy.premium 

Egal ob ihr eine Samsung Smartwatch mit Tizen OS habt oder eine Wear OS by Google Smartwatch. Die Apps aus dem Playstore 
benötigt ihr auf jeden Fall. Alle Preise sind nur einmalig zu bezahlen. KEIN ABO! 


Wenn ihr eine Smartwatch von Samsung benutzt dann braucht ihr zusätzlich noch eine dieser beiden Apps aus dem Galaxy Store.

Für die Samsung Uhren Modelle GearS2, Gear S3 und Galaxy Watch (Alle Versionen) nach dem installieren könnt ihr das Watchmaker 
Watchface wie alle anderen Watchfaces in der Watchface Übersicht auf der Uhr oder in der Galaxy Wearable App finden und auswählen :
 
-Watchmaker Companion Legacy  2.49€
http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzy

Für die neuen Modelle Galaxy Active und Galaxy Active 2: 

-Watchmaker Companion 2.99€
http://apps.samsung.com/gear/appDetail.as?appId=slide.watchFrenzyw

Für die Wear OS by Google Smartwatches öffnet ihr nach dem installieren der Watchmaker App auf dem Smartphone,
den Playstore auf eurer Smartwatch dort scrollt ihr runter. Hier findet ihr das Watchmaker Watchface installiert es,
danach könnt ihr es wie gewohnt direkt von der Uhr in der Watchfaceübersicht finden und auswählen odewr natürlich auch von der
Wear App auf dem Smartphone. 

ALLE PREISE SIND VOM 03.11.2019 
DIESE PREISE WURDEN NICHT VON MIR ERHOBEN 

Ihr müsst die automatische Akku-Optimierung für euer Smartphone ausschalten. 
Tipps dazu findet ihr hier. www.dontkillmyapp.com Danach müsst dir noch die automatische Akku-Optimierung für alle Apps ausschalten,
die ihr im Rahmen dieser Anleitung installiert habt. 
Einstellungen und Berechtigungen für AutoNotification, Tasker und Watchmaker 



Als erstes geht ihr nun im Smartphone auf:  Einstellungen/Apps/Autonotification dann auf Berechtigungen. Dort alle Schalter aktivieren.
Dasselbe macht ihr für Watchmaker also:  Einstellungen/Apps/Watchmaker/Berechtigungen
hier ebenfalls alle Schalter aktivieren
Wenn ihr alle Apps auf dem Smartphone installiert habe öffnet ihr erst AutoNotification.
Euer Smartphone wird euch beim starten oder beim beenden von AutoNotification nach Berechtigungen fragen die ihr bitte akzeptiert.
Bitte deaktiviert auch die Akku-Optimierung!
Dort drückt ihr auf "Notification Interception" dann auf "Ignore Apps" 
Hier müsst ihr alle Apps mit Haken versehen, ausser xDrip+ und AAPS 
AutoNotification ist nun fertig eingerichtet. 

Ganz wichtig damit Tasker die nötigen Daten von AutoNotification bekommt müsst ihr dieses auch anschalten, wenn ihr einmal hier seit dann aktiviert auch gleich alle berechtigungen für Tasker gleich mit.
Ich benutze ein Samsung Smartphone mit One UI wenn irh ein anderes Smartphone benutzt kann sich dieser schritt unterscheiden. 
Dazu geht ihr in euerem Smartphone auf Einstellungen/Apps hier klickt ihr oben rechts auf die 3 Punkte und klickt auf "Spezieller Zugriff". Hier seht ihr nun eine Liste von Einträgen die wichtig für die Datenübermittlung ist. es geht um die Einträge 

-Akkuverbauch optimieren              Schalter für AutoNotification und Tasker DEAKTIVIEREN
-Geräteadministrator-Apps             Schalter für Tasker AKTIVIEREN
-Nicht-Stören Berechtigung            Schalter für Tasker AKTIVIEREN
-System Einstellungen ändern          Schalter für Tasker AKTIVIEREN
-Zugriff auf Benachrichtigungen       Schalter für AutoNotification und Tasker AKTIVIEREN
-Apps beim Datensparen zulassen       Schalter für AutoNotification und Tasker DEAKTIVIEREN
-Zugriff auf Nutzungsdaten            Schalter für Tasker AKTIVIEREN

Dann geht ihr zu Einstellungen/Eingabehilfe klickt unten auf "Installierte Dienste" hier scrollt ihr anch unten und aktiviert Tasker

Restliche Tasker Berechtigungen:
Als nächstes öffnet ihr Tasker. Damit Tasker richtig läuft stellt ihr bitte als erstes die Sprache auf Englisch um. 
Um die Änderung zu aktivieren drückt ihr danach oben rechts auf die 3 Punkte um das Menü zu öffnen, dann auf Exit Tasker, 
anschliessend öffnet ihr Tasker auch direkt wieder.Um das ganze Abzukürzen habe ich Screenshots erstellt die bei Fragen alles erklären
sollten.Dazu klickt ihr nachdem öffnen von Tasker oben rechts auf die 3 Punkte. Das menü öffnet sich. Ihr klickt auf "More" 
dann auf "Android Settings" hier findet ihr mehrere Einträge die euch zu den Berechtigungen bringen. Ihr klickt nacheinander 
auf jeden Eintrag. Dann aktiviert ihr die Berechtigung indem ihr einen Schalter aktiviert oder einen Button drücken müsst. 
Ist bei jedem Eintrag anders. Wenn ihr nicht wisst wie findet ihr hier Bilder dazu. https://imgur.com/gallery/HIDsbm1 
Danach ist Tasker fertig eingerichet. 

Nachdem alle Apps nun eingerichtet sind könnt ihr nun die benötigten Tasker Profile und Tasks importieren. Ihr müsst darauf achten 
alles in der richtigen Reihenfolge zu importieren. Immer zuerst den Task und danach das zugehörige Profil. 
Ihr klickt auf den Link für den Task, dann öffnet sich eine Internetseite. Auf dieser findet ihr einen grünen
Button mit der Aufschrift "IMPORT" wenn ihr ihn gedrückt habt werdet ihr zu Tasker weitergeleitet. 
Hier werdet ihr gefrgat ob ihr den Task oder das Profil importieren  und danach gleich aktivieren wollt. Ihr klickt bei beidem "YES" 
Das macht ihr mit allen 



1. ZUERST IMPORTIEREN xDrip+ Task:
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Task%3AVars+xDrip%2B%2Fmg%2Fdl+Watchmaker+ONLY)

2. xDrip+ Profil: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Profile%3AxDrip%2B+Notifications+-+Watchmaker+ONLY

3. ZUERST IMPORTIEREN AAPS Task: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Task%3AVars+AAPS%2Fmg%2Fdl+Watchmaker+ONLY

4. AAPS Profil: 
https://taskernet.com/shares/?user=AS35m8mlt5xx0ME%2BtNTXK6rFnQPs1RUb38m9tui3GLZpydqGl3C7iL1YYOsaI8lQbmAxMf%2B4&id=Profile%3AAAPS+Notifications+-+Watchmaker+ONLY



Nun sind alle Tasks und Profile imporiert und aktiviert.
Öffnet Tasker und klickt oben auf den Reiter "TASKS" dann erst auf "VARS xDrip........" unten befindet sich ein "Play-Button" 
drückt ihn und achtet auf die grünen Punkte die neben den Variabeln erscheinen. Drückt den Zurück Button oben links und macht 
dann dasselbe mit "VARS AAPS......." Im Anschluss müsst ihr sowohl xDrip als auch AAPS einmal beenden. Dazu geht ihr im Smartphone 
auf Einstellungen/Apps/AAPS dort drückt ihr auf "Stoppen erzwingen" Dasselbe macht ihr für xDrip+ ebenfalls. 
Einstellungen/Apps/xDrip+ "Stoppen erzwingen" ACHTUNG MACHT DIES BITTE NICHT WÄHREND EINER SENSOR AUFWÄRMPHASE DIES 
KÖNNTE UNTER UMSTÄNDEN PROBLEME MACHEN!!!!! Nachdem ihr dies für beide Apps gemacht habt öffnet ihr sie bitte einmal. 

Nun sollten alle Variabeln erfolgreich angezeigt werden. Schaut einmal nach.
Öffnet Tasker und klickt oben rechts auf den Reiter 
"VARS" wenn ihr nur den xDrip TASK und das xDrip Profil importiert habt dann findet ihr hier nun 9 Einträge. 
Wenn ihr die TASKS und Profile für xDrip und AAPS importiert habt dann sind es 38. 

Wenn das nicht der Fall ist, wiederhohlt den Vorgang mit dem Play-Button erneut.

FÜR TIZEN SMARTWATCHES WICHTIG!
Ihr müsst noch ein paar Einstellungen auf der Uhr vornehmen. Dazu tappt ihr 2x auf das Watchface. Nun öffnen sich die Einstellungen. 
Das erkennt ihr daran das links und rechts ein Pfeil erscheint. Nach rechts gehts zu den zuletzt synchsonisierten Watchfaces und 
nach links zu den Einstellungen. Hier findet ihr die nötigen Bildder um die richtigen Einstellungen vorzunehmen. 
https://imgur.com/P3iLEOY 

Alle meine selbst gemachten Watchfaces findet ihr hier. Ihr könnt sie selbstverständlich nutzen oder euch selber welche bauen. 


Vielen Dank für das Interesse.



Wenn ihr mir einen Kaffee kaufen wollt geht das über PayPal:

https://www.paypal.me/diafreddy 


Variabeln in Watchmaker hinzufügen:

um ein eigenes Watchface zu bauen macht ihr folgendes:
Öffnet Watchmaker und klickt oben rechts auf die 3 Punkte und anschließend auf "NEW WATCH"
Anschließen seht ihr ein "Plus Button" drückt ihn und anschließen wählt ihr "TEXT" aus. Nun könnt ihr die erste Variabel hinzufügen. 
Tasker Variabeln werden immer in großen Buchstaben und in diesem Format geschrieben {t....}. Für den Glukose-Wert tippt ihr also 
{tGLUCOSE} ein und drückt OK die Anzeige ist nun dem Watchface hinzugefügt worden. Unten findet ihr eine Liste von allen Variabeln 
die ihr benutzen könnt um Werte von xDrip+ und AAPS hinzuzufügen.

Hier im Watchmaker Wiki findet ihr auch alles mögliche was ihr wissen müsst um selber Watchfaces zu bauen. Schaut mal rein
https://watchmaker.haz.wiki/ 

Liste aller Variabeln: 

xDrip+:
{tGLUCOSE}		Glukose-Wert mit Trendpfeil
{tGLUCOSE11}	Glucose-Wert ohne Trendpfeil
{tBGTIME}		Zeitstempfel des Glukose-Werts
{tDELTA}		Delta
{tDELTAA}		Delta als Zahl ohne die worte "delta:" und "mg/dl"

AAPS:
{tAVERAGE}	
{tAAPSGLUCOSE}	Glukose-Wert ohne Trendpfeil
{tAVERAGES}       	15 Minuten Durchschnitt
{tAVERAGEL}	40 Minuten Durchschnitt
{tPUMPSTATUS}	Pumpenstatus
{tAAPSTIME}	Zeitstempel des Glukose-Werts
{tBASAL}
{tBASALRATE}	Basalrate
{tBASALPROFILE}	Basalprofile
{tTBR}		Basalraten Status 
{tIOB}		Insulin On Board
{tCOB}		Carbs On Board
