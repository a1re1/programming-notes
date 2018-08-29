# Chapter 01
## Computer Networking: A Top Down Approach
What is the Internet?
  - billions of connected computing devices
    - hosts = end systems
    - running network apps
  - communication links
    - fiber, copper, radio, satellite
    - transmission rate: bandwidth
  - packet switches: forward packets (information)

Service views
  - infrastructure that provides services to applications
    - web, VoIP, email, etc...
  - provide programming interface to apps
    - hooks that allow sending and receiving
    - provides service options, analogous to postal account

What is a protocol?
  - human protocols
    - "What's the time?"
    - "I have a question."
    - "introductions"
  - network protocols
    - format that governs device communication

TCP - Transport Control Protocol
IP - Internet Protocol

Network Edge: clients and servers and devices that connect to the Internet
Bandwidth - the rate at which packets can be transmitted
Resources can be shared or dedicated (Mostly shared now)

### Packets
- Host sends packets that contain messages
- Packet will contain a header (source, destination, misc bits) and then information  (length of packet is L)
- transmission rate of R
- packet transmission delay is L(bits)/R(bits/sec); the time needed to transmit an L bit packet to a link

Packet switching uses store-and-forward strategy: entire packet must arrive at router before it can be transmitted on the next link

### Circuit Switching
- end-end resources allocated to, reserved for "call" between source & destination
- dedicated resources
- guaranteed performance
- segment is idle if not being used
