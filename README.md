# Week-9-Honey-Pot

## Which Honeypot(s) you deployed?
* mhn-honeypot-1 

## Any issues you encountered?
* Yes, for installing the git clone https://github.com/RedolentSun/mhn.git , this link didn't work for me so I looked around online and found a link that provided me with the git clone https://github.com/threatstream/mhn.git in the install_hpfeeds.sh file and changed the git clone and the also for the Hurrican lab since that repository didn't work either. Here are the links where I found the working links:
https://github.com/threatstream/mhn/issues/560 

## A summary of the data collected: number of attacks, number of malware samples, etc.
* Attacks in the last 24 hours: 1
TOP 5 Attacker IPs: 46.161.27.30 (1 attacks)
TOP 5 Attacked ports: 8545 (1 times)
TOP 5 Honey Pots: dionaea (1 attacks)
TOP 5 Sensors: mhn-honeypot-1 (1 attacks)

## Any unresolved questions raised by the data collected:
* Yes, for some odd reason on my vmware, the Attack report displays only one attack report when it should have displayed multiple. I researched online and couldn't find anything that could resolve my issue. I have attached a screenshot of the honeypot attack result.

## Issues:
* An issue I kept having was trying to download the session.json file. The instructions provided did not work for me since it required a public key authentication and for some odd reason I was denied access. So I learned to transfer the session.json into a bucket, opened the saved file link in the url and then right-clicked on the page and downloaded it from there.

