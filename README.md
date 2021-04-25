# OnesOwnCloud-Link
Link is a library used to facilitate the secure connection between an on-premise docker swarm (of sorts), a cloud based docker swarm, or a hybrid.


# Explanation
This would essentially set up and maintain the VPN (Wireguard or similar) connections between the devices / networks. PC's would be fairly simple, but mobile phones could get a bit tricky without support from Apple/Google/Samsung/etc..

The VPN would be in "split tunneling mode" and would not necessarily send traffic to the host - so bandwidth is not as expensive.

# My Use Case

I have ran into this problem a few times, where I have a group of friends that I want to have access to a project (Dev environemnt) or a real service I have installed on a server to only them. Typically, this takes HOURS to set up, and it's tedious to get someone to hand over there phone for some people. Could always hand them the App and IP:Port + Cert, but that's asking too much already.

With OOC-Link - this is all handled in the background seamlessly. Just install an app, login, and it works. You can join each of your friends networks and set permissions to get to each.


# Orchestration W11 Containers peer-to-peer / server-client
