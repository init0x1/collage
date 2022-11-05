## ▪ Module 01: Computer Networks and the Internet

<hr>

### How do packet delay and loss occur?

• packets queue in router buffers, waiting for turn for transmission

▪ queue length grows when arrival rate to link (temporarily) exceeds output link 
capacity 

▪ packet loss occurs when memory to hold queued packets fills up

### Host: sends packets of data function :
▪ takes application message

▪ breaks into smaller chunks, 
known as packets, of length L bits

▪ transmits packet into access 
network at transmission rate R

• link transmission rate, aka link 
capacity, aka link bandwidth 

Packet transmission delay = time needed to
transmit L-bit
packet into link = L  / R 

### Packet delay :
1. Transmission Delay:
The time taken to transmit a packet from the host to the transmission medium is called 
Transmission delay.
2. Propagation delay:
After the packet is transmitted to the transmission medium, it has to go through the medium to reach 
the destination. Hence the time taken by the last bit of the packet to reach the destination is called 
propagation delay.
3. Queueing delay: 
Let the packet is received by the destination, the packet will not be processed by the destination immediately. It has to 
wait in a queue in something called a buffer. So the amount of time it waits in queue before being processed is called 
queueing delay.
=>This delay depends upon the following factors:
• If the size of the queue is large, the queuing delay will be huge. If the queue is empty there will be less or no delay.
• If more packets are arriving in a short or no time interval, queuing delay will be large.
• The less the number of servers/links, the greater is the queuing delay
4. Processing delay:
• Now the packet will be taken for the processing which is called processing delay.
• Time is taken to process the data packet by the processor that is the time required by intermediate routers to decide
where to forward the packet, update TTL, perform header checksum calculations.

### Packet loss

▪ queue (aka buffer) preceding link in buffer has finite capacity

packet arriving to
full buffer is lost

▪ packet arriving to full queue dropped (aka lost)

▪ lost packet may be retransmitted by previous node, by source end 
system, or not at all

### Throughput

▪ throughput: rate (bits/time unit) at which bits are being sent from 
sender to receiver

• instantaneous: rate at given point in time

• average: rate over longer period of time