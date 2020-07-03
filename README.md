#### Note: All the Python scripts of this repository Requires linux Operating System and Support of Network Interface Card in Monitor Mode.

# 1. Beacon_Frames_Scanner.py 
This Script scans and provides all the Beacons Frames Discovered by the Network Interface Card. Wireless Beacon Frames are transmitted by the Wireless Access   Points. Connection between Access Points and End Devices occur with help of Beacon Frames emitted by WLAN. Beacons Frames carry several information like Time-stamp, SSID, MAC-Addresses of Access Point, Beacon Interval, Supported Rates. Beacon frames are transmitted  periodically by Access Points to indicate their presence. Whenever we turn on the Wifi Icon in our Mobile Phone; we see lots of Wirless SSID discovered by our Phone. This is due, Access Points are emitting the Beacons Frames and our phones discover them to inform the user. Then, there further connection processes if the user wants to connect to the Access Point.  
#### Requirements  


#### To Execute the Script:    
git clone *https://github.com/Papu11/Wireless_Security_with_Python-Scapy.git*      
cd Wireless_Security_with_Python-Scapy/  
sudo python2 Beacon_Frames_Scanner.py  
