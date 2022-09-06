# homelab

to see what I am going to be doing on this server, check out [home-k8s](https://github.com/samjtro/home-k8s)

## goals

total est. cost: $2061.62-$2161.62
  - $1811.62 [server](https://pcpartpicker.com/user/makingcomputersformyself/saved/xGyDZL)
  - $250-350 [controller](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=2014+mac+mini+i7+16gb+256gb&_sacat=0&LH_TitleDesc=0&_odkw=2014+mac+mini+i7+16gb+ram+256gb+ssd&_osacat=0&LH_PrefLoc=2)

- [x] Backup & Wipe G5
- [x] Install ubuntu server 
- [x] Configure new server; primarily for SSH, k8s & docker
  - EDIT: I have ssh'd into the server successfully and setup a MicroK8s instance on the machine
- [ ] Buy new case (Phanteks Eclipse P300A)
- [ ] Buy x3 SSDs (Samsung 980 Plus 2TB NVME, Cache: 2048MB); configure in RAID10
- [ ] Buy new PSU
- [ ] Buy new Mobo, RAM, CPU & Cooler
- [ ] Buy controller; 2014 i7 Mac Mini

My Dell G5 5090 is starting to slow down. As a result, I have been thinking of getting a new PC; but parts are still absurdly expensive, and I have had the long-standing itch to create a home server. I will eventually get a new PC, but for right now, since I am no longer gaming & not running any GPU-intensive programming tasks, a PC with a good GPU is not entirely neccesary. 

The parts for my G5 are as follows:
- Geforce GTX 1660 Ti
- Intel i5 9600k
- 16GB RAM
- 1TB HDD
- 450W PSU

Thus, the goal is to turn my G5 into a fully headless, designated home server that I can access from my laptops & a controller. I want to keep the machine under $2,000; ideally. It will probably go over that, and that's fine. I could just go out and build a brand new server, but I'm new to having an on-premise dedicated home lab so I want to use old hardware as a base. Not to mention, I am still kind of going nuts on parts; if I want to upgrade, I can very easily do so within the parameters of this system.

Regardless, another goal is to make this a dedicated Workstation for my programming tasks. As a result, I want >32GB RAM & >8 Cores. My current plans are for double that; a Threadripper 1950x gives me 16 Cores @ 32 Threads & I am going to get 64GB of RAM, and then very quickly double to 128GB. This will allow me to do basically everything I need & have overhead for more.

I am also planning on keeping my GTX 1660 Ti; it will not go on my server though. I will use it as an external GPU for the Mac Mini; in case I want to run any ML tasks, or play any games.

My controller will be a Mac Mini; which I am very excited about. I haven't used Mac on the desktop for a while (in H.S., ran a Hackintosh at home & used them in other various aspects of education); they are much more powerful than Raspberry Pis, and the x86 architecture makes it easy for compatibility purposes. They are also fairly cheap; obviously not what a Raspberry Pi would cost me, but <$300 for an i7 with 16gb of RAM is still very good. These came to my attention as efficient server controllers via proximity to [rwxrob](https://github.com/rwxrob), who is building his homelabs out of used Mac Minis. I could probably do this for the same cost as what I'm going with now, but am not because I would still need to buy storage racks and probably some more compute power to put in my cluster. Once I move into my house, I will be adding a few old computers I have in storage into my cluster; and maybe buying some more Mac Minis! 

I haven't really seen exactly what I plan on doing elsewhere, but it's basically of an amalgamation of everything I've seen prior. The idea is to connect the Mini to my pre-existing Desktop setup, run the server elsewhere & ssh into the server. I can then leverage the enormous compute of the server on the Mac Mini. Will more than likely flash Linux onto the Mini, but I'm not positive yet. Will upgrade MacOS and see how it's feeling; if it is too slow, then I'll flash Linux. Else; I'll get to use Mac on the Desktop again!