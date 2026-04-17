I have implemented a learning switch using the POX controller.
The controller learns MAC addresses dynamically from incoming packets, installs flow rules in
the switch, and forwards packets efficiently.
Initally packets are flooded, but afer learning, direct forwarding happens.
I validated this using pingall and observed zero packet loss. 
