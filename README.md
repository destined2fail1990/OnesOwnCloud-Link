# OnesOwnCloud-Link
Link is a library used to facilitate the secure connection between an on-premise docker swarm (of sorts), a cloud based docker swarm, or a hybrid.


# Explanation
This would essentially set up and maintain the VPN (Wireguard or similar) connections between the devices / networks. PC's would be fairly simple, but mobile phones could get a bit tricky without support from Apple/Google/Samsung/etc..

The VPN would be in "split tunneling mode" and would not necessarily send traffic to the host - so bandwidth is not as expensive.
