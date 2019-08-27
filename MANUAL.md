xDrip Notification on Tizen Watch - exportet with Tasker and Autonotification and integrated to Watchmaker Watchfaces


1. Update V1.1 25.08.2019
2. Update V1.2 27.08.2019



PLEASE NOTICE!
You have to buy Watchmaker Premium             (6,99€ Play Store)
You have to Buy Watchmaker Companion for Tizen (2,49€ Galaxy Store/Watch)
YOu have to buy Autonotification               (2,39€ Play Store)
You have to buy Tasker                         (1,99€ Play Store)

My watchface is free for all but you have to buy premium watchmaker for getting watchfaces synced ton your watch



updated soon: Color Changer for BG values - every variable got a own Tag. Now you are able to script a color changer for BG Value for <70 red and for >200 yellow in between is white but. 
But that color changer have to be scripted with LUA ;-) this will be updatet soon. Please follow Freddy_x on Watchmaker to get Updates. ;-)


1.	Download Tasker (1,99€), AutoNotification(2,39€) and WatchMaker (premium 6,99€ Abo 7,49€ monthly)from the         Google Play Store you need Watchmaker Premium for my Watchface
2.	Install the WatchMaker companion app (2,49€) onto the watch using the Galaxy Store, set WatchMaker as your         watch face.
3.	Open Autonotification
4.	Press on Notification Interceptions
5.	Press on Ignore Apps
6.	Set a hook for each entry but not at xdrip+
7.	Make sure Xdrip is running and the ongoing notification is displayed.
8.	Launch Tasker (accept permissions if it asks.)
9.	Press the plus icon at the bottom right of the screen while on profile tab (name it notification)
10.	Press Event
11.	Press Plugin
12.	Press AutoNotification
13.	Then Intercept
14.	Press the grey pencil button next to configuration
15.	You will recieve warnings to allow access for AutoNotification to view your Notifications, allow it you may         also recieve a warning about Doze, allow that.
16.	Press Fill From Current
17.	Press Notification and select the Xdrip+ notification
18.	Enable the Notification App and Notification Id
19.	Press the confirm check mark at the top right of the screen twice
20.	Then press the back arrow
21.	This returns you back to Tasker, select New Task (call it Var)
22.	Press the plus button located at the bottom right
23.	Select Variables then Variables Set
24.	For name type %GLUCOSE and for To type %antitle
25.	Press the back arrow
26.	Press the plus button located at the bottom right
27.	Select Variables then Variables Set
28.	For name type %BGTIME and for To type %TIME
29.	Press the back arrow
30.	Again press the plus button, select Variables then Variables Set
31.	For name type %DELTA and for To type %ansummarytext then press the back arrow.
32.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
33.	Press the grey pencil next to Configuration.
34.	In the Tasker Variable box type %GLUCOSE then press done.
35.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
36.	Press the grey pencil next to Configuration.
37.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
38.	Press the grey pencil next to Configuration.
39.	In the Tasker Variable box type %BGTIME then press done
40.	Press the back arrow
41.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
42.	Type %DELTA in the Tasker Variable box then press done.
43.	Press the back arrow twice then press the confirm check at the top right corner of Tasker
44.	Allow 5 mins to elapse so the data is sent to WatchMaker then launch WatchMaker on your phone.
45.	Press the 3 dots located at the top right corner and select New Watch
46.	Press the green pencil icon and then the plus button.
47.	Select Time and drag the clock position to suit
48.	Press the plus button again this time select Expression.
49.	Press the white box at the top and type {tglucose} then press done.
50.	Drag the glucose positioning to suit.
51.	Press the plus button again and select Expression.
52.	Press the white box and type {tdelta} press done, position to suit.
