# system-performances-tools

## Classic

- top
- ps auxwww

## System resources

List of tools used to look after system performances (mem, cpu, disks, network, processes, files..) :

- [sysdig](http://www.sysdig.org/) :star: :star: :star: :star: :star: : a console ui to monitor (live and snapshots) several aspects of the system
- [iostat](http://linuxcommand.org/man_pages/iostat1.html) :star: :star: :star: :star: : i/o accesses
- [dstat](http://dag.wiee.rs/home-made/dstat/) :  
- [sar](http://linuxcommand.org/man_pages/sar1.html) : monitor network, devices
- [iotop](http://guichaz.free.fr/iotop/) : top, with i/o !
- [vmstat](http://linuxcommand.org/man_pages/vmstat8.html) : mem/swap/cpu
- [ifstat](https://linux.die.net/man/1/ifstat) : like iostat, vmstat, but for network
- [iperf](https://iperf.fr/) : test maximum bandwidth (tcp/udp)

## Java specifics

- [jstat](http://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr017.html) : like iostat, vmstat, for java processes. eg: `jstat -gc -t -h30 [vmid] 1s : monitor Java GC`