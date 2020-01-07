# mv1000-arch
arch linux for the gl inet mv1000

username/password: root

192.168.8.1 is configured on the lan ports, and they are configured as a bridge, wan is configured for dhcp.

Lots of todo's here:
Add usb3 device to kernel
add led driver from openwrt kernel/set led triggers
add dtb/kernel config for arches expressobin kernel

Bootlog:
Welcome to Arch Linux ARM!

[    6.953765] systemd[1]: Set hostname to <MV1000-arch-test>.
[    7.603232] random: systemd: uninitialized urandom read (16 bytes read, 19 bi                                                                                          ts of entropy available)
[    7.612916] systemd[1]: system-getty.slice: unit configures an IP firewall, b                                                                                          ut the local system does not support BPF/cgroup firewalling.
[    7.625407] systemd[1]: (This warning is only shown for the first unit using                                                                                           IP firewalling.)
[    7.635732] systemd[1]: Created slice system-getty.slice.
[  OK  ] Created slice system-getty.slice.
[    7.652743] random: systemd: uninitialized urandom read (16 bytes read, 20 bi                                                                                          ts of entropy available)
[    7.662767] systemd[1]: Created slice system-serial\x2dgetty.slice.[  OK  ] C                                                                                          reated slice system-serial\x2dgetty.slice.
[    7.680748] random: systemd: uninitialized urandom read (16 bytes read, 21 bi                                                                                          ts of entropy available)
[    7.690965] systemd[1]: Created slice User and Session Slice.
[  OK  ] Created slice User and Session Slice.
[    7.708780] random: systemd: uninitialized urandom read (16 bytes read, 21 bi                                                                                          ts of entropy available)
[    7.718541] systemd[1]: Started Dispatch Password Requests to Console Directo                                                                                          ry Watch.
[  OK  ] Started Dispatch Password …ts to Console Directory Watch.
[    7.736743] random: systemd: uninitialized urandom read (16 bytes read, 22 bi                                                                                          ts of entropy available)
[    7.746574] systemd[1]: Started Forward Password Requests to Wall Directory W                                                                                          atch.[  OK  ] Started Forward Password R…uests to Wall Directory Watch.
[    7.764816] systemd[1]: Condition check resulted in Arbitrary Executable File                                                                                           Formats File System Automount Point being skipped.
[    7.776979] random: systemd: uninitialized urandom read (16 bytes read, 23 bi                                                                                          ts of entropy available)
[  OK  ] Reached target Local Encrypted Volumes.Encrypted Volumes.
[    7.800804] random: systemd: uninitialized urandom read (16 bytes read, 24 bi                                                                                          ts of entropy available)
[    7.810305] systemd[1]: Reached target Paths.
[  OK  ] Reached target Paths.
[    7.824720] random: systemd: uninitialized urandom read (16 bytes read, 24 bi                                                                                          ts of entropy available)
[    7.834186] systemd[1]: Reached target Remote File Systems.
[  OK  ] Reached target Remote File Systems.
[    7.848688] random: systemd: uninitialized urandom read (16 bytes read, 25 bi                                                                                          ts of entropy available)
[  OK  ] Reached target Slices.hed target Slices.
[    7.872732] random: systemd: uninitialized urandom read (16 bytes read, 26 bi                                                                                          ts of entropy available)
[    7.882200] systemd[1]: Reached target Swap.[  OK  ] Reached target Swap.
[    7.893091] systemd[1]: Listening on Device-mapper event daemon FIFOs.
[  OK  ] Listening on Device-mapper event daemon FIFOs.
[    7.916920] systemd[1]: Listening on Process Core Dump Socket.
[  OK  ] Listening on Process Core Dump Socket.
[  OK  ] Listening on initctl Compatibility Named Pipe.bility Named Pipe.
[    7.949471] systemd[1]: Listening on Journal Audit Socket.
[  OK  ] Listening on Journal Audit Socket.
[    7.965296] systemd[1]: Listening on Journal Socket (/dev/log).
[  OK  ] Listening on Journal Socket (/dev/log).
[    7.981310] systemd[1]: Listening on Journal Socket.
[  OK  ] Listening on Journal Socket.
[    7.997468] systemd[1]: Listening on Network Service Netlink Socket.
[  OK  ] Listening on Network Service Netlink Socket.
[  OK  ] Listening on udev Control Socket.ev Control Socket.
[    8.029120] systemd[1]: Listening on udev Kernel Socket[  OK  ] Listening on                                                                                           udev Kernel Socket.
[    8.060886] systemd[1]: Mounting Huge Pages File System...
         Mounting Huge Pages File System...
[    8.080028] systemd[1]: Mounting POSIX Message Queue File System...
         Mounting POSIX Message Queue File System...
[    8.107961] systemd[1]: Mounting Kernel Debug File System...
         Mounting Kernel Debug File System...
[    8.148927] systemd[1]: tmp.mount: Directory /tmp to mount over is not empty,                                                                                           mounting anyway.
[    8.181030] systemd[1]: Mounting Temporary Directory (/tmp)...
         Mounting Temporary Directory (/tmp)...
[    8.197111] systemd[1]: Condition check resulted in Create list of static dev                                                                                          ice nodes for the current kernel being skipped.
[    8.215803] systemd[1]: Condition check resulted in Set Up Additional Binary                                                                                           Formats being skipped.
[    8.227846] systemd[1]: Condition check resulted in Load Kernel Modules being                                                                                           skipped.
[    8.252872] systemd[1]: Mounting FUSE Control File System...
         Mounting FUSE Control File System...
[    8.275962] systemd[1]: Mounting Kernel Configuration File System...
         Mounting Kernel Configuration File System...
[    8.321325] systemd[1]: Starting Remount Root and Kernel File Systems...
         Starting Remount Root and Kernel File Systems...
[    8.343776] systemd[1]: Starting Apply Kernel Variables...
         Starting Apply Kernel Variables...
[    8.389252] systemd[1]: Starting udev Coldplug all Devices...
         Starting udev Coldplug all Devices...
[    8.415690] systemd[1]: Mounted Huge Pages File System.
[  OK  ] Mounted Huge Pages File System.
[    8.441525] systemd[1]: Mounted POSIX Message Queue File System.
[  OK  ] Mounted POSIX Message Queue File System.
[    8.457821] systemd[1]: Mounted Kernel Debug File System.
[  OK  ] Mounted Kernel Debug File System.
[    8.477642] systemd[1]: Mounted Temporary Directory (/tmp).
[  OK  ] Mounted Temporary Directory (/tmp).
[    8.493409] systemd[1]: Mounted FUSE Control File System.
[  OK  ] Mounted FUSE Control File System.
[    8.509442] systemd[1]: Mounted Kernel Configuration File System.
[  OK  ] Mounted Kernel Configuration File System.
[    8.526262] systemd[1]: Started Remount Root and Kernel File Systems.
[  OK  ] Started Remount Root and Kernel File Systems.
[    8.547039] systemd[1]: Started Apply Kernel Variables.
[  OK  ] Started Apply Kernel Variables.
[    8.581161] systemd[1]: Condition check resulted in First Boot Wizard being s                                                                                          kipped.
[    8.599588] systemd[1]: Condition check resulted in Rebuild Hardware Database                                                                                           being skipped.
[    8.634620] systemd[1]: Starting Load/Save Random Seed...
         Starting Load/Save Random Seed...
[    8.671579] systemd[1]: Starting Create System Users...
         Starting Create System Users...
[    8.773222] systemd[1]: Started udev Coldplug all Devices.
[  OK  ] Started udev Coldplug all Devices.
[    9.539743] systemd[1]: Started Create System Users.
[  OK  ] Started Create System Users.
[    9.569257] systemd[1]: Starting Create Static Device Nodes in /dev...
         Starting Create Static Device Nodes in /dev...
[    9.622599] systemd[1]: Started Create Static Device Nodes in /dev.
[  OK  ] Started Create Static Device Nodes in /dev.
[    9.641550] systemd[1]: Reached target Local File Systems (Pre).
[  OK  ] Reached target Local File Systems (Pre).
[    9.656906] systemd[1]: Condition check resulted in Virtual Machine and Conta                                                                                          iner Storage (Compatibility) being skipped.
[  OK  ] Reached target Local File Systems.ocal File Systems.
[    9.701139] systemd[1]: Started Entropy Daemon based on the HAVEGE algorithm.
[  OK  ] Started Entropy Daemon based on the HAVEGE algorithm.
[    9.724164] systemd[1]: Starting Rebuild Dynamic Linker Cache...
         Starting Rebuild Dynamic Linker Cache...
[    9.743805] systemd[1]: Starting Journal Service...
         Starting Journal Service...
[    9.761046] systemd[1]: Condition check resulted in Commit a transient machin                                                                                          e-id on disk being skipped.
[    9.799734] systemd[1]: Starting udev Kernel Device Manager...
         Starting udev Kernel Device Manager...
[    9.886358] systemd[1]: Started Journal Service.
[  OK  ] Started Journal Service.
[    9.901308] audit: type=1130 audit(1574296155.076:2): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-journald comm="systemd" exe="/usr/lib/syst                                                                                          emd/systemd" hostname=? addr=? terminal=? res=success'
         Starting Flush Journal to Persistent Storage...
[   10.015489] systemd-journald[1753]: Received client request to flush runtime                                                                                           journal.
[  OK  ] Started Flush Journal to Persistent Storage.
[   10.057037] audit: type=1130 audit(1574296155.232:3): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-journal-flush comm="systemd" exe="/usr/lib                                                                                          /systemd/systemd" hostname=? addr=? terminal=? res=success'
         Starting Create Volatile Files and Directories...
[  OK  ] Started udev Kernel Device Manager.
[   10.233084] audit: type=1130 audit(1574296155.408:4): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-udevd comm="systemd" exe="/usr/lib/systemd                                                                                          /systemd" hostname=? addr=? terminal=? res=success'
         Starting Network Service...
[  OK  ] Started Create Volatile Files and Directories.
[   10.321150] audit: type=1130 audit(1574296155.496:5): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-tmpfiles-setup comm="systemd" exe="/usr/li                                                                                          b/systemd/systemd" hostname=? addr=? terminal=? res=success'
         Starting Rebuild Journal Catalog...
         Starting Network Time Synchronization...
         Starting Update UTMP about System Boot/Shutdown...
[   10.606544] audit: type=1127 audit(1574296155.780:6): pid=1779 uid=0 auid=429                                                                                          4967295 ses=4294967295 msg=' comm="systemd-update-utmp" exe="/usr/lib/systemd/sy                                                                                          stemd-update-utmp" hostname=? addr=? terminal=? res=success'
[  OK  ] Started Rebuild Journal Catalog.
[   10.685474] audit: type=1130 audit(1574296155.860:7): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-journal-catalog-update comm="systemd" exe=                                                                                          "/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  OK  ] Started Update UTMP about System Boot/Shutdown.
[   10.781613] audit: type=1130 audit(1574296155.956:8): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-update-utmp comm="systemd" exe="/usr/lib/s                                                                                          ystemd/systemd" hostname=? addr=? terminal=? res=success'
[  OK  ] Started Network Service.
[   10.848993] audit: type=1130 audit(1574296156.024:9): pid=1 uid=0 auid=429496                                                                                          7295 ses=4294967295 msg='unit=systemd-networkd comm="systemd" exe="/usr/lib/syst                                                                                          emd/systemd" hostname=? addr=? terminal=? res=success'
         Starting Network Name Resolution...
[  OK  ] Started Network Time Synchronization.
[   10.957004] audit: type=1130 audit(1574296156.132:10): pid=1 uid=0 auid=42949                                                                                          67295 ses=4294967295 msg='unit=systemd-timesyncd comm="systemd" exe="/usr/lib/sy                                                                                          stemd/systemd" hostname=? addr=? terminal=? res=success'
[  OK  ] Reached target System Time Set.
[  OK  ] Reached target System Time Synchronized.
[  OK  ] Found device /dev/ttyMV0.
[   11.588802] br-lan: port 1(lan1) entered blocking state
[   11.600876] br-lan: port 1(lan1) entered disabled state
[   11.614216] device lan1 entered promiscuous mode
[   11.619115] audit: type=1700 audit(1574296156.796:11): dev=lan1 prom=256 old_                                                                                          prom=0 auid=4294967295 uid=981 gid=981 ses=4294967295
[   11.636463] device eth0 entered promiscuous mode
[   11.660985] br-lan: port 2(lan0) entered blocking state
[   11.666336] br-lan: port 2(lan0) entered disabled state
[   11.677072] device lan0 entered promiscuous mode
[   11.984935] IPv6: ADDRCONF(NETDEV_UP): br-lan: link is not ready
[  OK  ] Started Rebuild Dynamic Linker Cache.
         Starting Update is Completed...
[   12.602953] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
[  OK  ] Started Update is Completed.
[  OK  ] Reached target System Initialization.
[  OK  ] Started Daily verification of password and group files.
[  OK  ] Started Daily Cleanup of Temporary Directories.
[  OK  ] Reached target Timers.
[  OK  ] Listening on D-Bus System Message Bus Socket.
[  OK  ] Reached target Sockets.
[  OK  ] Reached target Basic System.
[  OK  ] Started D-Bus System Message Bus.
         Starting Login Service...
[  OK  ] Started Network Name Resolution.
[  OK  ] Reached target Network.
[  OK  ] Reached target Host and Network Name Lookups.
[  OK  ] Started MV1000 set interfaces to up.
[  OK  ] Started OpenSSH Daemon.
         Starting Permit User Sessions...
[   13.100311] IPv6: ADDRCONF(NETDEV_UP): lan0: link is not ready
[  OK  ] Started Login Service.
[  OK  ] Started Permit User Sessions.
[   13.142400] IPv6: ADDRCONF(NETDEV_UP): lan1: link is not ready
[   13.160960] IPv6: ADDRCONF(NETDEV_UP): wan: link is not ready
[  OK  ] Started Getty on tty1.
[  OK  ] Started Serial Getty on ttyMV0.
[  OK  ] Reached target Login Prompts.
[  OK  ] Reached target Multi-User System.
[  OK  ] Reached target Graphical Interface.
[   13.632616] mvneta d0030000.ethernet eth0: Link is Up - 1Gbps/Full - flow con                                                                                          trol off
[   13.640449] IPv6: ADDRCONF(NETDEV_CHANGE): eth0: link becomes ready
[   14.997116] dsa dsa@0 wan: Link is Down
[   15.069231] dsa dsa@0 lan0: Link is Down
[   15.145131] dsa dsa@0 lan1: Link is Down
[   17.009911] dsa dsa@0 wan: Link is Up - 1Gbps/Full - flow control off
[   17.016290] IPv6: ADDRCONF(NETDEV_CHANGE): wan: link becomes ready

Arch Linux 4.4.52-armada-17.10.3-ge1b9bf1 (ttyMV0)

MV1000-arch-test login: 
