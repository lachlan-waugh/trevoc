# trevoc
A kernel-land rootkit for Linux

&nbsp;

## features
* files/directories hiding
* processes/ptree hiding
* network connections/activity hiding
* prevents basic detections by tooling
* cleaning of system logs

&nbsp;

## stealth
* syscall hooking
* syscall table hijacking
* vfs hooking

&nbsp;

## persistence
* crontab
* `LD_PRELOAD` (`/etc/ld.so.preload`)
* setuid binary (in case you lose root privileges)

&nbsp;

## acknowledgement
heavily inspired from many of the rootkits from [awesome linux rootkits](https://github.com/milabs/awesome-linux-rootkits)
