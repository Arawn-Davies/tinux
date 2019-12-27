# tinux
## Small Linux system targeting 486+ systems

After buying an old 486 laptop with an i486 DX2-66 CPU, 8MB RAM and a 325MB HDD, I wanted to build a small 
but up-to-date Linux system that can run on this ancient relic. Now, it is still in it's early days, so I'm still refining a few things 
(ie. what packages to include, kernel version etc.) but the main thing is that it has busybox, uclibc, serial I/O 
(so I can use it as a dumb terminal if I need to) and enough stuff to allow it to be self-building and expandable to
target newer architectures like i686, ARM and more. 
  
Based on Buildroot at first, I am providing the tinux_defconfig file and Buildroot .config configuration file.
  
### Note: The buildroot release used is the latest stable. 
I haven't tried using Buildroot directly via source control with it working, due to me learning how to use .config and defconfigs on the 
stable release, 2019.02.8 as of writing this README.   
