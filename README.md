# Collision-detection-
(CSMA/CD) Carrier sense multiple access/ collision detection 
INTRODUCTION
carrier sense multiple access (csma) is one of the most widely deployed media access control (MAC) protocols that allow multiple users to share a common transmission channel such as 802.11wireless LAN and Ethernet. Carrier Sense Multiple Access with collision detection is a method used notably in early Ethernet technology for local area network. it uses carrier -sensing to defer transmission until no other stations are transmitting. This is used in combination with collision detection in which a transmitting station detects collisions condition is detected, the station stops transmitting that frame, transmits a jam signal, and then waits for a random time interval before trying to resend the frame
Algorithm 
the algorithm non persistent CSMA is
1.when a frame or channel is ready, the transmitting station checks whether the channel is idle or busy.
2.if the the channelis idke then it transmits the frame immediately.
if the channel is busy, the station waits for a random time period during which it does not check whether the channel is idle or busy
At the end of the waiting time period, it again checks the status of the channel and restarts the algorithm.
BACK-OFF ALGORITHM 
back off algorithm is used for collision  resolution.it works as, when thus collision occurs, both the devices wait for a random amount of time before retransmittingthe signal again, they keep on trying until the data is transferred successfully.
this is called back off algorithm, since the nodes "back off" for a certain amount of time before they try to re-access it again. this random amount of time is directly proportional to the number of attempts it has made to transmit the signal 
https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4rrberOfSAqPTlpdziZPAF0LPK8P6-d3QtZdXEFB3UWwYNlWlFv-tNa0&s=10
