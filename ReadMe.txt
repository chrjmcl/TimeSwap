“This is a mobile based application where people on this platform can trade hours as local currency. 
This system provides a means for people to request different services and also provide diverse services 
to people on this platform. When a user is in need of a request, the request is posted which is broadcasted 
and made available to all users of the application. The request posted includes how much time the requests 
is willing to trade for the service. After each service is provided, the system updates both the number of 
services and the hours for the requester and the responder. The requester of a service gets the chance to rate 
the service a responder provided.”


Use a Mac, not a windows PC

Android Studio Link : https://developer.android.com/studio/

In android studio, hit Open an existing android studio project
From here, go to where you have installed timeswap, and click on the innermost timeswap : https://imgur.com/a/YpvbzDL

Before running:
	Get your SHA1 by running android studio with Timeswap open
	On the Right select Gradle. Under TimeSwap folder, there are TimeSwap(root) and :app. Select :app, then Tasks, then android, then double click signingReport
	On the bottom left console, you should see your SHA1, copy that string
	It will look like this : https://imgur.com/a/S9hMA6B
	Log into the google account:
		Username : timeswap454@gmail.com
		Password : PLEASE CONTACT ME FOR PASSWORD
	Visit: https://console.cloud.google.com/apis/credentials?project=timeswap-8c7d5&folder=&organizationId=
	Click on places key
	Scroll down and click + Add package name and fingerprint
	Enter : com.example.android.timeswap (Your SHA1)
	Hit save

Now hit the green play button, select Create New Virtual Device
Download Nexus 5X 5.2” 1080x1920 420dpi. Hit Next.
Download Nougat 24. Hit Next and Finish.

Chose that emulator, and the application should start.

Registration and Login may take long to validate, depending on firebase’s condition. Simply wait for it or run again.