# IoT Camp - Seattle - 06/04/2015 #

This Site: http://aka.ms/iotcampsea

EVAL LINK: http://aka.ms/IoTEventWA


---

## WiFi Info ##

**PLEASE DO NOT USE THE WIFI HEAVILY.  THIS IS NOT THE TIME TO DOWNLOAD VIDEO TORRENTS!  IF YOU NEED VISUAL STUDIO 2013 SEE ME, DON'T DOWNLOAD IT!**

| SSID:     | msiotcamp     | 
| ---       | ---           |
| **PWD:**  | **msiotcamp** | 

If you have an Ethernet connection, you can plug one of the cables on the tables in.  We will be using those later for the devices though. 

### msiotcamp WiFi Issues ###

Currently, there are some issues with the "**msiotcamp**" wifi network.  All "**msiotcamp**" traffic is going through my tiny [Zyxel MWR102](http://www.zyxel.com/us/en/products_services/mwr102.shtml?t=p) Access Point.  So, it is NOT a power house.  If you have an ethernet port, plug into that (at least until we need it for the devices in the lab). 

---

## Presenter Info

Bret Stateham<br/>
Bret.Stateham@microsoft.com<br/>
@BretStateham<br/>
http://BretStateham.com<br/>

Jeremy Foster<br/>
jerfost@microsoft.com<br/>
@CodeFoster<br/>
http://codefoster.com<br/>

---

## Slides ##

You can grab them from the [Slide Deck](/Slide Deck) folder in this same repo.

## Connect The Dots Fork ##

The live [connectthedots.io] repo has some issues, and doesn't inclue the Hands-On Lab documents for todays events.  

**Make sure you use my fork of the Connect the Dots Repository:**

http://aka.ms/bsctd

---

## Links ##

| Site                          | Link                                | 
| ---                           | ---                                 |
| This Web Site                 | http://aka.ms/iotcampsea            |
| Bret's  Connect the Dots Fork | http://aka.ms/bsctd                 | 
| Hands-On Labs                 | http://aka.ms/ctdhols               |
| Hands-On Lab Videos           | http://aka.ms/ctdholvids            |
| Rocket Launcher               | http://github.com/dxdisrupt/rocket  |  
| Seattle DeviceJam Meetup      | http://www.meetup.com/DeviceJam/    |
| Tweet Monkey                  | http://codefoster.com/tweetmonkey   |
| Command Monkey                | http://codefoster.com/commandmonkey |
| MSP RGB LED Sample            | https://github.com/mspcontent/Creating-Your-First-Internet-Connected-Device | 
| Arduino Web Motor Control     | https://www.youtube.com/watch?v=09m3ohJ4PSU | 

---

## Hands-On Labs ##

1. [Overview](https://github.com/BretStateham/connectthedots/tree/master/HOLs)
2. [Azure Prep](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/AzurePrep) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
3. [Connect the Dots Sample Web Site](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/WebSite) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
4. [Arduino with SparkFun Weather Shield](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/GatewayConnectedDevices/Arduino%20UNO/Weather/WeatherSheildJson)
5. [Raspberry Pi Field Gateway](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/Gateways/GatewayService)
6. [Gadgeteer with FEZ Spider](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/DirectlyConnectedDevices/NETMF/ConnectTheDotsGadgeteer)

---

## USB Sticks ##

There are some USB Sticks that have the large downloads you may need on them.  

**IF YOU TAKE ONE, PLEASE *COPY* THE CONTENTS TO YOUR COMPUTER THEN PASS IT ON**

**PLEASE RETURN THE USB DRIVES WHEN YOU ARE DONE**
---

## Bret's Event Hub and Web Site Info ##

If you are having problems getting your Azure Backend to work, you can try pointing at mine.  Just make sure that 

1. You give your sensors a unique name so you can see it on my page 
2. Give your sensors a unique GUID
3. Both of the above would be in either your Arduino source code, or in the Gadgeteer source code, depending on which type of device you are using.  s

|  Item           | Value                                             | 
| ---             | ---                                               |
|Service Bus Name:|ctdhol-ns                                          |
|Event Hub Name:  |ehdevices                                          |
|Key Name:        |D1                                                 |
|Key:             |L2wFYmNQ05PqD3n6d1/ScRPJB/dbzCHYh1RQwWVuBJc=       |
|URL Encoded Key: |L2wFYmNQ05PqD3n6d1%2FScRPJB%2FdbzCHYh1RQwWVuBJc%3D |
|Web Site URL:    |http://ctdholweb.azurewebsites.net                 |	
| tcpdump info    | http://www.networkworld.com/article/2225683/cisco-subnet/raspberry-pi-as-a-network-monitoring-node.html | 

---

## Raspberry Pi IP Addresses ##

|  #     | WiF IP Address   | Ethernet IP  | 
| :----: | --------------:  | --:          |
|   Pi2  |                  | 10.10.10.204 |
|   Pi3  |                  | 10.10.10.227 |
|   Pi4  |                  | 10.10.10.148 |
|     1  |                  |   10.10.8.97 |
|     4  |                  |  10.10.7.174 |
|    2C  |                  | 10.10.10.253 |
|    3C  | 10.10.11.10      | 10.10.10.252 |
|    4C |  10.10.10.207     |  10.10.9.198 |
|    5C |  10.10.8.89    | 10.10.9.41  |
|    7C |  10.10.4.182   |  10.10.6.105 |
|    8C |  10.10.10.236  | 10.10.11.31|
| Bret's |                  | 10.10.10.160 |


