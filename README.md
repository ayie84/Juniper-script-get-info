# Juniper-script-get-info

This script perfom multiple command into singgle command to get some information. I filter some information base on what i need. This script i already test on EX2300. Here is the example output from the script.

Output example from get-info.slax
```
----------------------------------------------------------------------------------------------------------------
                                              Welcome admin
----------------------------------------------------------------------------------------------------------------
       ** This is the output of the script  for EX2300T4 on Sun Jun  3 01:46:31 2018 ** 
----------------------------------------------------------------------------------------------------------------
SWITCH:    *  INFO    * : EX2300T4-C8-1R1-1
           *  SERIAL  * : 123456789abc
           *  MODEL   * : EX2300-48T
           *  VERSION * : 15.1X53-D56
           *  OS      * : JUNOS OS Kernel 32-bit  [20170413.348470_builder_head]
----------------------------------------------------------------------------------------------------------------
CLOCK :    *  SOURCE  * :  LOCAL CLOCK 
----------------------------------------------------------------------------------------------------------------
CHASSIS:   ** GREEN ** : There are no active chassis alarms
----------------------------------------------------------------------------------------------------------------
SYSTEM:    ** GREEN ** : There are no active system alarms
           *  UPTIME * : System Uptime is 17 days, 16:55
           *  USER   * : netadmin is currently logged in from 172.25.1.46 since 1:19AM
           *  COMMIT * : Last commit was 2018-06-01 23:18:49 MYT by: netadmin
           *  DRIVE  * : RE0 is OK and master and has been up for 17 days, 16 hours, 51 minutes, 43 seconds
           *  REBOOT * : Last Reboot Reason :: 0x1:power cycle/failure
----------------------------------------------------------------------------------------------------------------
POWER:     *  STATUS * : FPC 0 Power Supply 0 / OK
SENSOR:    *  INFO   * : FPC 0 CPU Sensor / 54 degrees C / 129 degrees F / OK
SENSOR:    *  INFO   * : FPC 0 PSU Sensor / 44 degrees C / 111 degrees F / OK
FAN:       *  INFO   * : FPC 0 Fan Tray 0 / Spinning at normal speed / OK
----------------------------------------------------------------------------------------------------------------
PROCESS:   *  CPU       * : Process 11 % / IDLE : 66 %
LOAD AVG:  *  1 minute  * : 0.46
           *  5 minute  * : 0.43
           *  15 minute * : 0.36
----------------------------------------------------------------------------------------------------------------
```

# How to load into EX2300

-Step 1
</br>Please make sure you know the root password

-Step 2

