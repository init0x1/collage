## ▪ Module 01: Computer Networks and the Internet

<hr>

### • Network core : packet/circuit switching, internet structure

## The network core

#### packet-switching: hosts break  application-layer messages into packets

### Two key network-core functions :

#### Forwarding :
 • aka “switching” 
 local action: move 
arriving packets 
from router’s 
input link to 
appropriate router 
output lin

#### Routing: 
▪ global action: 
determine source destination paths 
taken by packets
▪ routing algorithms

### Packet-switching: store-and-forward

• store and forward: entire packet must arrive at 
router before it can be transmitted on next link

### Packet-switching: queueing
Queueing occurs when work arrives faster than it can be serviced:

### Packet queuing and loss: 
if arrival rate (in bps) to link exceeds 
transmission rate (bps) of link for some period of time:

• packets will queue, waiting to be transmitted on output link 

• packets can be dropped (lost) if memory (buffer) in router fills up

### Alternative to packet switching: circuit switching
end-end resources allocated to, 
reserved for “call” between source 
and destination ▪ commonly used in traditional telephone networks

### Circuit switching: FDM and TDM

#### Frequency Division Multiplexing (FDM) 
• optical, electromagnetic frequencies 
divided into (narrow) frequency bands

▪ each call allocated its own band, can 
transmit at max rate of that narrow 
band 

#### Time Division Multiplexing (TDM) 

▪ time divided into slot

▪ each call allocated periodic slot(s), can 
transmit at maximum rate of (wider) 
frequency band (only) during its time 
slot(s)
