1.	Download Tasker (2,99 Play Store), AutoNotification(1.99) on Play Store) and WatchMaker (free pn play store;Premium 6.99)
2.	Persistent notification for xdrip must be set
3.	Install the WatchMaker companion app (2,99 on Galaxy Store) to the watch using the Galaxy Store, set WatchMaker as your watch face.
4.	Launch Tasker 
5.	press on three dots on top right corner
6.	select more
7.	select Android settings
8.	apply every single entry permissions to run tasker succsesfully
9.	Press the plus icon at the bottom right of the screen while on profile tab (name it xdrip+ notifications)
10.	Press Event
11.	Press Plugin
12.	Press AutoNotification
13.	Then Intercept
14.	Press the grey pencil button next to configuration
15.	You will recieve warnings to allow access for AutoNotification to view your Notifications, allow it you may also recieve a warning about Doze, allow that.
16.	Press Fill From Current
17.	Press Notification and select the Xdrip+ notification
18.	Enable the Notification App and Notification Id
19.	Press the confirm check mark at the top right of the screen twice
20.	Then press the back arrow
21.	This returns you back to Tasker, select New Task (call it Var)
22.	Press the plus button located at the bottom right
23.	Select Variables then Variables Set
24.	For name type %GLUCOSE and for To type %antitle %TIME
25.	Press the back arrow
26.	Again press the plus button, select Variables then Variables Set
27.	For name type %DELTA and for To type %ansummarytext then press the back arrow.
28.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
29.	Press the grey pencil next to Configuration.
30.	In the Tasker Variable box type %GLUCOSE then press done.
31.	Press the back arrow once.
32.	Press the plus button once again, select Plugin then WatchMaker and WM Send Variable.
33.	press the grey pencil next to Configuration.
34.	Type %DELTA in the Tasker Variable box then press done.
35.	Press the back arrow twice then press the confirm check at the top right corner of Tasker
36.	Allow 5 mins to elapse so the data is sent to WatchMaker then launch WatchMaker on your phone.
37.	Press the 3 dots located at the top right corner and select New Watch
38.	Press the green pencil icon and then the plus button.
39.	Select Time and drag the clock position to suit
40.	Press the plus button again this time select Expression.
41.	Press the white box at the top and type {tglucose} then press done.
42.	Drag the glucose positioning to suit.
43.	Press the plus button again and select Expression.
44. Press the white box at the top and type {tbgtime} then press done.
45. Drag the time positioning to suit.
44. Press the plus button again and select Expression.
46.	Press the white box and type {tdelta} press done, position to suit.
