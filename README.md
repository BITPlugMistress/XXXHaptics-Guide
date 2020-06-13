### XXXHaptics: A fucking guide to VRChat

## Required:

-   Virtual Reality Headset supported by VRChat
-   VRChat account with rank of “New User”
-   Any toy registered on buttplug.io
-   Unity 2018.4.20f1 (As of June 2020)
-   VRChat SDK2 (As of June 2020)
-   A computer with built-in Bluetooth OR Plugable USB Bluetooth 4.0 Low Energy Micro Adapter
-   USB Extension Cable/Dongle highly recommended
-   XXXHaptics
-   itiface Desktop
-   Notepad++
-   Lube

## Important Links:

-   <https://hheaven.net/XXXHaptics/manual.html>
-   <http://hheaven.net/XXXHaptics/XXXHaptics.zip>
-   <https://intiface.com/desktop/>
-   <https://github.com/intiface/intiface-desktop>
-   <https://discord.buttplug.io/>
-   <https://buttplug.io/>
-   <https://www.patreon.com/qdot>
-   <https://playground.buttplug.world/>
-   <https://vrchat.com/>
-   <https://docs.vrchat.com/>
-   <https://docs.vrchat.com/docs/controls>
-   <https://docs.vrchat.com/docs/current-unity-version>
-   <https://github.com/madjin/awesome-vrchat>
-   <https://vrchat.fandom.com/wiki/List_of_model_resource_websites>
-   <https://notepad-plus-plus.org/>
-   <https://www.amazon.com/Plugable-Bluetooth-Adapter-Raspberry-Compatible/dp/B009ZIILLI>

## Part 1: Notes

-   Support buttplug.io via Patreon
-   Feel free to share this Guide with anyone
-   Make sure Bluetooth Drivers are up to date
-   XXXHaptics.exe might set off your antivirus
-   Be safe, know your limits, and always use plenty of lube
-   Join the buttplug.io Discord for more advanced questions
-   This software does not modify the VRChat client in any way
-   Log into the VRChat website first before downloading the SDK

## Part 2: Intiface Desktop Setup

A. Launch Intiface Desktop installer and run GET UPDATES

![](media/d14fe20ab5ef22664cc0c390613c1dd2.png)

B.  Do not run RUN CERTSETUP

![](media/00cb8396ea411bcc0c8ad2aa69f53b67.png)

C.  Settings -\> Server Process Settings -\> Check “Start Server when Intiface Desktop Launches”

![](media/4cfbb5ddbb9c0615d05e8760ae3ad9e9.png)

## Part 3: Unity Setup 

### **THIS IS NOT INTENDED TO BE AN AVATAR CREATION GUIDE AND ASSUMES YOU HAVE AT LEAST SOME BASIC KNOWLEDGE ABOUT BOTH UNITY AND AVATAR CREATION. PLEASE REFER TO THE IMPORTANT LINKS SECTION FOR THE APROPREATE RESOURCES**

A.  Go to the Layer Dropdown Menu at the top of the Inspector tab and click Add Layer…

![](media/281a9a43d8c62bad9bb8854532c25e38.png)

B.  Make sure your Tags & Layers are set up correctly

![](media/0c3a17f6a680bf9e266d907e9c6c3645.png)

C.  Import XXXHaptics.unitypackage and add XXXHaptics/prefab/Haptics.prefab as a child of Neck

![](media/364f85821df6fbf3375b7cec024c2875.png)

D.  Break Prefab instance

![](media/87852a66b38fdea4ca805c6283c0e18a.png)

E.  Place HapticsSensor_X_X on desired locations on the Armature Tree

![](media/fa2d04d27532891869dccf30ac08b113.png)

F.  Move HapticsSensor_X_X to desired location within the 3D Scene

![](media/457b72931dbd7f1e6fcb105c2dedc3de.png)

G.  Update HapticsSensor_X_X to match with these settings

![](media/289c2c9bf5f043def108aa4ec6c767cc.png)

H.  Bonus: Change HapticsSensor_X_X Size

![](media/59bc2569db12e1f572d532b0b29b9a05.png)

I.  Bonus: Change HapticsSensor_X_X Culling Masks

![](media/24c1cb840aca964aa9dcb75c7419d385.png)

J.  DO NOT UPLOAD AS PUBLIC/SHARE THE AVATAR IT WILL BREAK REQUIRING A REUPLOAD

![](media/043a7ec81dd52af6e8104bafca8d2405.png)

## Part 4: XXXHaptics Setup

A.  Plug adapter in or enable built-in Bluetooth

![](media/077b8b0f1a747146c8c89d5659940b20.png)

B.  Connect toy to computer via Bluetooth

![](media/5909e4e8459bdac9b18dafc08dfe3969.png)

C.  Open playground.buttplug.world and connect via browser or Intiface

![](media/35161cfa42bdc9e1457110ec0fa6f0e8.png)

D.  Record Toy name IE “Lovense Hush v222”

![](media/538a09adc823400e5d8cb4ed131aec2e.png)

E.  Right click “setting.json” -\> “Edit with Notepad++” or your preferred text editor

![](media/c5f9edc77e73dfabb1b57f78082a1820.png)

F.  Change [XXXXX] to your Toy’s name

![](media/075c3c44e8c0e7ce39d00ae7a28994f8.png)

G.  Edit the code based on your Toy/Avatar configuration and save the .json file

![](media/7af072910d32e7db4ee77801b3f077a3.png)

## Part 5: Testing

A.  Launch VRChat and start Stream Camera by opening the Menu -\> Camera -\>Stream Camera

![](media/3c3f5bbe33b2f1ff9cc2510666a4063d.jpg)

B.  Set Camera to self-gaze mode

![](media/8e9e3cbad72c4ff552df974172367f4f.jpg)

C.  Bonus: Detach screen from lens

![](media/6132eb542694ea0cab71602aa13a33c8.jpg)

D.  Load into modified Avatar, at the top left you should see 4 black boxes

![](media/cde1b67853e4418ab583b52a0b6c0488.png)

E.  Start Intiface Desktop and click START SERVER if autostart is disabled [See1.E]

![](media/3481c49d2b281772f0284d5c3a6e8b4e.png)

F.  Launch XXXHaptics

![](media/1e3b32e0792ae5dcec2d3037ac86aadf.png)

G.  If everything is set up correctly the Toy should connect and react to collisions with the Sensors

![](media/f421a5bc060444d9178fb5c296567a2a.png)
