# GRBL Defaults
To load up these [config lines](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md), connect an arduino serial monitor (115200 baud) and send these one by one. Sending `$$` will print them all out

```
$0=10 (step pulse, usec)
$1=25 (step idle delay, msec)
$2=0 (step port invert mask:00000000)
$3=0 (dir port invert mask:00000000)
$4=0 (step enable invert, bool)
$5=0 (limit pins invert, bool)
$6=0 (probe pin invert, bool)
$10=3 (status report mask:00000011)
$11=0.010 (junction deviation, mm)
$12=0.002 (arc tolerance, mm)
$13=0 (report inches, bool)
$20=0 (soft limits, bool)
$21=0 (hard limits, bool)
$22=1 (homing cycle, bool)
$23=1 (homing dir invert mask:00000011)
$24=200.000 (homing feed, mm/min)
$25=1500.000 (homing seek, mm/min)
$26=250 (homing debounce, msec)
$27=5.000 (homing pull-off, mm)
$100=80.000 (x, step/mm)
$101=80.000 (y, step/mm)
$102=250.000 (z, step/mm)
$110=10000.000 (x max rate, mm/min)
$111=10000.000 (y max rate, mm/min)
$112=500.000 (z max rate, mm/min)
$120=100.000 (x accel, mm/sec^2)
$121=100.000 (y accel, mm/sec^2)
$122=10.000 (z accel, mm/sec^2)
$130=400.000 (x max travel, mm)
$131=288.000 (y max travel, mm)
$132=200.000 (z max travel, mm)

```