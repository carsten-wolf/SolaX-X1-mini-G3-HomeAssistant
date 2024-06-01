# SolaX-X1-mini-G3-HomeAssistant
Configuration for SolaX 1 mini G3 and Home Assistant

This is based on the [Solax-X1-mini-G4---HomeAssistant](https://github.com/ThomasBlome/Solax-X1-mini-G4---HomeAssistant) repo by Thomas Blome
You can get Data in real time from the inverter without the cloud (limit of 5 minutes)
What you need is the Wifi Pocket USB Dongle from SolaX and the IP address of the Dongle, the SerialNo that is on the Dongle.

> [!IMPORTANT]
> To test the connection you can use a curl command. Replace SERIAL with the SerialNo that is on the USB Dongle and the xxx for you IP of the Dongle
`curl -d "optType=ReadRealTimeData&pwd=SERIAL" -X POST http://192.168.xxx.xxx`

>[!NOTE]
>Home assiatant configuration: Replace **Put-in-SerialNo** with the SerialNo that is on the USB Dongle and the xxx for you IP of the Dongle

![Screenshot of the Dashboard.](/SolaX1_Dashboard.png)
