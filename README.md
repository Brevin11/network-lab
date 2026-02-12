# network-lab

<b>Below is a high level look at a network design I made via Cisco Packet Tracer. I have also attached the file to my repository if you wish to view it more in-depth in the Packet Tracer environment.</b>
<br>
<br>
<br>
<br>
<br>
<p> <img width="1400" height="819" alt="Screenshot 2026-02-12 141042" src="https://github.com/user-attachments/assets/95ca41b7-8d84-4af7-9c84-8eda1fa727bd" />
A logical diagram of my network utilizing a router-on-a-stick design. </p>
<br>
<br>
<br>
<br>
<br>
<p> <img width="1055" height="267" alt="Screenshot 2026-02-12 141254" src="https://github.com/user-attachments/assets/5d34c31a-456f-4feb-aee4-987dae4e49d8" />
Implemented dynamic routing using OSPF to enable automatic route propagation and failover. </p>
<br>
<br>
<br>
<br>
<br>
<p><img width="922" height="129" alt="Screenshot 2026-02-12 141419" src="https://github.com/user-attachments/assets/670b1cf6-4ebc-43da-a0d6-a4dc3eb43b7e" /> <br>
Creation of different vlan subinterfaces. </p>
<br>
<br>
<br>
<br>
<br>
<p></p><img width="880" height="358" alt="Screenshot 2026-02-12 141455" src="https://github.com/user-attachments/assets/ceb78e5b-b4f6-4733-abb1-ec2a9ffa99a2" /> <br>
Each switchport has been logically seperated into its own vlan.</p>
<br>
<br>
<br>
<br>
<br>
<p> </p><img width="750" height="152" alt="Screenshot 2026-02-12 141908" src="https://github.com/user-attachments/assets/be18f11b-02e8-43eb-a35c-0c178951355a" /> <br>
DHCP has been setup on each router. Endpoints have been given an IP address automatically instead of creating a static entry for them.</p>
<br>
<br>
<br>
<br>
<br>
<p> </p><img width="894" height="285" alt="Screenshot 2026-02-12 142012" src="https://github.com/user-attachments/assets/33ab8553-e821-4aad-8ae0-9b1ddda5c8de" /><br>
ICMP packets are recieved through inter-vlan routing successfully. Can restrict inter-vlan communication with ACLs on the router.</p>
