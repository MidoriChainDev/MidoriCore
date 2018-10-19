### Qos ###

This is a Linux bash script that will set up tc to limit the outgoing bandwidth for connections to the Bitcoin network. It limits outbound TCP traffic with a source or destination port of 50607, but not if the destination IP is within a LAN (defined as 192.168.x.x).

This means one can have an always-on midorid instance running, and another local midorid/midori-qt instance which connects to this node and receives blocks from it.
