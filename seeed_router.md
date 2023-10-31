# seeed router
QTY : 2

router IP : 192.168.2.1

| router number | auth details |
| -------- | -------- |
| 2/2 | user:root<br>pwd:1234<br>wireless<br>ssid:ESWS_CERT<br>pwd:EsWs@@CERT|
| 1/2 | user:root<br>pwd:123456789|


# issues
* when dealing with seeed routers sometimes the configuration is not applied
* This is due to corruption in the file system, which makes the file system read-only [ro] and not accept any configurations
* `/dev/mmcblk0p2 on / type ext4 (ro,noatime)`
* to solve this problem update the firmware of the router
![image](https://github.com/certesws/HW/assets/23504514/304c70cd-a63a-4493-9509-f607b33b672d)
