baby-monitor-doc
================
bluetooth BTLE life motion detector 
================
project specifications
biotrump lab forum
http://forum.biotrump.com/viewtopic.php?f=17&t=100
demo kit
http://item.taobao.com/item.htm?spm=a230r.1.14.7.nGN3UD&id=19066213304
blog
http://overheat.farbox.com/

1. accelerometer : motion detection
2. gyroscope : pose and orientation
a+g : 6 axis fusion
3. heart beat sensor : noncontact, capacitive electrode? TBD
4. vibrator : motor vibrates in critical condition
5. buzzer : beeping in critical condition
6. btle : turn on to broadcast alarm only when no motion is detected after 30s or the ther critical condtion is detected to minimize the exposure to radio energy.
nordic 51822 : Arm cortex M0 + BTLE RF
7. button cell battery
8. led
9. usb charger
10. phone app to receive the alert or to monitor baby motion status
11. remote management server from internet
12. wakeup detection
13. postion change : lying to sitting up or standing up
14. continuous big motion
15. falling
16. dangerous position : head down for 30s 
monitor console : a android 4.3 smart device + BTLE
to monitor one or more sensors simultaneously.

