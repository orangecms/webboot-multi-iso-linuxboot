# Abstract

## webboot - The LinuxBoot way of multi distro ISO booting

With the growing demand and support for [LinuxBoot](https://linuxboot.org) in
firmware, new approaches to booting operating systems have become possible,
based on the Linux [kexec](https://man7.org/linux/man-pages/man8/kexec.8.html)
mechanism. This talk walks through the process of creating an environment for
booting a large set of different ISOs from various distributions, covering
different methods tried and ideas that came up, concluding with how [webboot](
https://github.com/u-root/webboot) eventually offers a decent and easy to use
interface that can be deployed on a USB stick, tried out in a VM, or even run
straight from a mainboard's firmware.
