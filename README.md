# An-Automated-System-for-High-Availability-Deployment-of-Network-Resources
An automated system which could predict the downtime  beforehand and take suitable steps to ensure High Availability (HA) of resources could protect businesses from losing data in a  critical time


# Steps which needs to be followed while running the code
1. Download the High availability of IoT end Device.ino file in the Node-MCU and add the WIFI SSID names in the array const char* KNOWN_SSID[] and the password of the corresponding WIFI SSIDs in the array const char* KNOWN_PASSWORD[]
2. Now, Flash the file in the ESP-8266 Node MCU board and after the wifi scan finishes, the NodeMCU client will connect to the Primary SSID
3. To simulate the failover scenario, make sure Primary SSID Access point going down
4. After the AP went down, the Node-MCU client will connect to its Backup Access point in very minimal amount of time providing almost zero down-time.


