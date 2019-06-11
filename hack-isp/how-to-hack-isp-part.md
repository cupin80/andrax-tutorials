# How to hack Internet Service Provider (ISP) part 1

Many people that call yourself by "hacker" don't know how a ISP works, in this article i'll try to
explain this and provide some information about ISP Hacking.

## Can we hack a ISP using Android?

Yes, you can! And this is more simple than you think! Just install ANDRAX and let's start hacking!

## First step

The first step is now the AS (Autonomous System) you can check it with whois and a lot of others resources.

Put the AS in https://bgp.he.net to get all prefixes registered by the ISP

![BGP](/hack-isp/img/bgphe01.jpg)

![BGP 02](/hack-isp/img/bgphe02.jpg)

As you can see we can get all prefixes of the ISP.

![IPCALC](/hack-isp/img/ipcalc.jpg)

## Ok, but how to hack it?

Now you need scan some services in prefixes.

Some interesting ports to scan: **8080, 80, 21, 22, 90, 1881, 443, 2233, 753, 53, 91, 149...**

Getting a list of these services we can perform a lot of attacks.

## How to bypass AUTH?

### Writing... wait!
