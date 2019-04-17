# ipChangeTool
change IP and MAC of ECB or ECU
#Usage
1. Download the tool
```
$ git clone https://github.com/innfos/ipChangeTool.git
```
2. Enter the ipChangeTool directory and change the permission of ipChange
```
chmod 777 ipChange
```
3. Ensure that you've connected ECB or ECU to your computer, then you can run cmd
```
./ipChange -ip=<1~255> -mac=<1~255>
```
Notice that you can only change the last number of IP and MAC. e.g. the ECU IP address is 192.168.1.30, you can only change 30 with the tool.
