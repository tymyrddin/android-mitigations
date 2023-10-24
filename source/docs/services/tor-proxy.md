# Use a Tor proxy

[Orbot](https://play.google.com/store/apps/details?id=org.torproject.android) is a free tor proxy app. It encrypts your Internet traffic and then hides it by bouncing through a series of 
computers around the world. Tor is free software and an open network that helps you defend against a form of network surveillance that threatens personal freedom and privacy, private activities and relationships, and state security 
known as traffic analysis.

If you wish to get it from F-droid and not the Play Google store, you will need to enable the Guardian repository in the F-Droid settings to have the Orbot app (and other apps like Tor Browser) show up. 

## Notes

* If a government makes their own national internet, or routes traffic through specific servers to use deep packet inspection (DPI), running Tor may not provide security if the government is able to see the entire path. 
* Sometimes the Tor network is censored, and clients can't connect to it. An increasing number of censoring countries are using Deep Packet Inspection (DPI) to classify Internet traffic flows by protocol. While Tor uses bridge relays to get around a censor that blocks by IP address, the censor can use DPI to recognize and filter Tor traffic flows even when they connect to unexpected IP addresses. With pluggable transports, censorship against Tor can be bypassed.
* Not only that. If an attacker can see your traffic, and can see the website you're visiting, even with a path outside the adversary's control - they will still be able to correlate the traffic and learn you are visiting the website.
* If the same connection (the same set of relays) were to be used for a longer period of time a Tor connection could be vulnerable to statistical analysis, which is why the client software changes the entry node every ten minutes.
