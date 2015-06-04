# IoT Camp - Seattle - 06/04/2015 #

This Site: http://aka.ms/iotcampla


---

## WiFi Info ##

**PLEASE DO NOT USE THE WIFI HEAVILY.  WE ARE SHARING ABOUT A 10Mbps UP/DOWN CONNECTION.  THIS IS NOT THE TIME TO DOWNLOAD VIDEO TORRENTS!**

| SSID:     | msiotcamp     | 
| ---       | ---           |
| **PWD:**  | **msiotcamp** | 

If you have an Ethernet connection, you can plug one of the cables on the tables in.  We will be using those later for the devices though. 

### msiotcamp WiFi Issues ###

Currently, there are some issues with the "**msiotcamp**" wifi network that prevents it's use for the lab. You can still connect for web and email, but protocols like SSH and AMQP needed for the lab are being blocked somewhere.  We will try to get it resolved, but if it doesn't you will need to connect your Gadgeteer's to the hardwired Ethernet connections on your table, not the msiotcamp WiFi.  

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

http://github.com/bretstateham/connectthedots

---

## Links ##

| Site                          | Link                     | 
| ---                           | ---                      |
| This Web Site                 | http://aka.ms/iotcampla  |
| Bret's  Connect the Dots Fork | http://aka.ms/bsctd      | 
| HOL Videos                    | http://aka.ms/ctdholvids | 


---

## Hands-On Labs ##

1. [Overview](https://github.com/BretStateham/connectthedots/tree/master/HOLs)
2. [Azure Prep](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/AzurePrep) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
3. [Connect the Dots Sample Web Site](https://github.com/BretStateham/connectthedots/blob/master/HOLs/Azure/WebSite) ([Video Walkthrough](https://youtu.be/xABIzejOxm4))
4. [Arduino with SparkFun Weather Shield](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/GatewayConnectedDevices/Arduino%20UNO/Weather/WeatherSheildJson)
5. [Raspberry Pi Field Gateway](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/Gateways/GatewayService)
6. [Gadgeteer with FEZ Spider](https://github.com/BretStateham/connectthedots/tree/master/HOLs/Devices/DirectlyConnectedDevices/NETMF/ConnectTheDotsGadgeteer)

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

---

## Raspberry Pi IP Addresses ##

|  #     | IP Address      |
| :----: | --------------: |
|   1    |    172.22.20.75 |
|   2    |     172.22.20.5 |
|   3    |     172.22.20.4 |
|   4    |     172.22.20.2 |
| Bret's |     172.22.20.7 | 

