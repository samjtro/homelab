# homelab

- $1633 [server](https://pcpartpicker.com/list/mvcKNc)
- $250 [controller](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=2014+mac+mini+i7+16gb+256gb&_sacat=0&LH_TitleDesc=0&_odkw=2014+mac+mini+i7+16gb+ram+256gb+ssd&_osacat=0&LH_PrefLoc=2)

My Dell G5 5090 is starting to slow down. As a result, I have been thinking of getting a new PC; but parts are still absurdly expensive, and I have had the long-standing itch to create a home server. I will eventually get a new PC, but for right now, since I am no longer gaming & not running any GPU-intensive programming tasks, a PC with a good GPU is not entirely neccesary. 

The parts for my G5 are as follows:
- Geforce GTX 1660 Ti
- Intel i5 9600k
- 16GB RAM
- 1TB HDD
- 450W PSU

Thus, the goal is to turn my G5 into a fully headless, designated home server that I can access from my laptops & a controller. I want to keep the machine under $2,000; ideally. It will probably go over that, and that's fine. I could just go out and build a brand new server, but I'm new to having an on-premise dedicated home lab so I want to use old hardware as a base. Not to mention, I am still kind of going nuts on parts; if I want to upgrade, I can very easily do so within the parameters of this system.

Regardless, another goal is to make this a dedicated Workstation for my programming tasks. As a result, I want >32GB RAM & >8 Cores. My current plans are for double that; a Threadripper 1950x gives me 16 Cores @ 32 Threads & I am going to get 64GB of RAM, and then very quickly double to 128GB.

These are the steps I can see as of right now:

0. Backup & Wipe G5 [ ]
1. Install ubuntu server [ ]
2. Configure new server [ ]; priorities:
- SSH
- k8s & docker
3. Buy new case (Phanteks Eclipse P300A) [ ]
4. Buy x3 SSDs (Samsung 980 Plus 2TB NVME, Cache: 2048MB) [ ]
- Configure in RAID10 [ ]
5. Buy new PSU [ ]
6. Buy new Mobo, RAM, CPU & Cooler [ ]
