WebSocket Demo on Witty Cloud Board (ESP8266) for checking full functionality of onboard devices
================================================================================================

<p align="center">
<img src="https://cloud.githubusercontent.com/assets/744810/12700003/5ac3cf0a-c786-11e5-93c3-5b146e50b894.jpg" alt="Witty Cloud Board" style="width:304px;height:228px;">
</p>

Master Source: Find all information here http://adityatannu.com/blog/post/2016/01/31/ESP8266-Witty-Cloud-Board-Demo.html

Simplified: The data folder is downloadable as zip-container for easier handling.

I use the above sketch for hardware testing of the two onboard devices, LDR and RGB.

My learnings during setting up the Witty Board: 
A very first step is to get the upload tool up and running
https://github.com/esp8266/arduino-esp8266fs-plugin  
Get "ESP8266 Sketch Data Upload" tool into Tools tab of your Arduino IDE.

<p align="center">
<img src="https://github.com/Mergenth/WittyCloudTest/blob/master/upload_tool_for_the_unzipped_data_folder.png" alt="ESP8266 Sketch Data Upload" style="width:304px;height:228px;">
</p>

Once the board is flashed, read from Serial Monitor its IP-adress, assigned by your local DHCP server.
This IP-adress you enter into the menuinterface.js file (inside data folder). Upload it to the Witty Board.
You might want to do it with this:   http://local.ip-adress/edit 

Done.

========================================================================
========================================================================

The data folder (unzipped) is stored in parallel to the WittyCloudTest.ino sketch.
<p align="center">
<img src="https://github.com/Mergenth/WittyCloudTest/blob/master/data.zip_Storage_Location_for_WittyCloudTest.png" alt="Folder structure for unzipped data folder storage" style="width:304px;height:228px;">
</p>
