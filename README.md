I have implemented a learning switch using the POX controller.
The controller learns MAC addresses dynamically from incoming packets, installs flow rules in
the switch, and forwards packets efficiently.
Initally packets are flooded, but afer learning, direct forwarding happens.
I validated this using pingall and observed zero packet loss. 
<img width="1481" height="504" alt="POX" src="https://github.com/user-attachments/assets/b6491faf-0e67-4cd7-a280-be679cded3c3" />
<img width="1543" height="927" alt="MININET" src="https://github.com/user-attachments/assets/248c70a0-48ad-47af-968c-ac9255a2b911" />
<img width="1900" height="810" alt="FLOWRULE" src="https://github.com/user-attachments/assets/049a45dc-014c-41f4-a300-09ba2b5ea4a3" />


