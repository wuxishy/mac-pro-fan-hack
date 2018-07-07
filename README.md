# mac-pro-fan-hack
Managing fan speed on old mac pro workstations


## How to use
* Make sure `CORETEMP` and `APPLE` point to the correct directory.
* `chmod +x temperature`
* Copy the files to the location as indicated in their comments.
* `systemctl enable temperature-control.service`
* Now the fanspeed (of the front intake, CPU cooler, and rear intake) will be adjusted every minute. 
