# Readings: Socket BE


### Common Networking Terms

- **Nodes:** is a physical electronic device hooked up to a network, for example a computer, printer, router, and so on.
<br>

- **Links:** Links connect nodes on a network. Links can be wired, like Ethernet, or cable-free, like WiFi.
- Links to can either be point-to-point,or one-to-many.

<br>

- **Protocol:** is a mutually agreed upon set of rules that allows two nodes on a network to exchange data.

<br>

- **Networks:** is a general term for a group of computers, printers, or any other device that wants to share data.

<br>

- **Topology:** describes how nodes and links fit together in a network configuration, often depicted in a diagram.

![Topology network Type](./assets/2-Network-Topology-Types.png)

      **A network consists of nodes, links between nodes, and protocols that govern data transmission between nodes.**


## The OSI Model

- The OSI model consists of 7 layers of networking.

- **Layer:** is a way of categorizing and grouping functionality and behavior on and of a network.

- **In the OSI model, layers are organized from:** the most tangible and most physical, to less tangible and less physical but closer to the end user.

### How to remember all the names of the layers?
- **Please** | Physical Layer
- **Do** | Data Link Layer
- **Not** | Network Layer
- **Tell** (the) | Transport Layer
- **Secret** | Session Layer
- **Password** (to) | Presentation Layer
- **Anyone** | Application Layer


### What are each of the layers?
- **Physical Layer:** There’s a lot of technology in Layer 1 - everything from physical network devices, cabling, to how the cables hook up to the devices. Plus if we don’t need cables, what the signal type and transmission methods are (for example, wireless broadband).
- The data unit on Layer 1 is the bit
<br>

- **Data Link Layer:** defines how data is formatted for transmission, how much data can flow between nodes, for how long, and what to do when errors are detected in this flow.
- The data unit on Layer 2 is a frame.

<br>

- **Network Layer:** This is where we send information between and across networks through the use of routers. Instead of just node-to-node communication, we can now do network-to-network communication.
<br>

- **Transport Layer:** This where we dive into the nitty gritty specifics of the connection between two nodes and how information is transmitted between them. 
<br>

- **Session Layer:** This layer establishes, maintains, and terminates sessions.

- **Presentation Layer:** This layer is responsible for data formatting, such as character encoding and conversions, and data encryption.

- **Application Layer:** this is the layer that is ultimately responsible for supporting services used by end-user applications. Applications include software programs that are installed on the operating system, like Internet browsers (for example, Firefox) or word processing programs (for example, Microsoft Word).

### How could I use this information to troubleshoot networking issues?
- **Layer 1 Problems** 
            
     - Defunct cables, for example damaged wires or broken connectors
     - Broken hardware network devices, for example damaged circuits
     - Stuff being unplugged (...we’ve all been there)

- **Layer 2 Problems** 

       -  All the problems that can occur on Layer 1
       -  Unsuccessful connections (sessions) between two nodes
       - Sessions that are successfully established but intermittently fail
       -  Frame collisions


- **Layer 3 Problems**

       - All the problems that can crop up on previous layers :)
       - Faulty or non-functional router or other node
       - IP address is incorrectly configured

- **Layer 4 Problems**

     - All the problems that can crop up on previous layers :)
     - Blocked ports - check your Access Control Lists (ACL) & firewalls
     - Quality of Service (QoS) settings. QoS is a feature of routers/switches that can prioritize traffic, and they can really muck things up. Learn more about QoS here.

- **Layer 5 Problems**

     - Servers are unavailable
     - Servers are incorrectly configured, for example Apache or PHP configs
     - Session failure - disconnect, timeout, and so on.

- **Layer 6 Problems**

     - Non-existent or corrupted drivers
     - Incorrect OS user access level


- **Layer 7 Problems**

     - All issues on previous layers
     - Incorrectly configured software applications
     - User error (... we’ve all been there)

[For more information](https://www.freecodecamp.org/news/osi-model-networking-layers-explained-in-plain-english/)

# Socket.io Documentation


- **Socket.IO** is a library that enables low-latency, bidirectional and event-based communication between a client and a server.

- It is built on top of the WebSocket protocol and provides additional guarantees like fallback to HTTP long-polling or automatic reconnection.

- **WebSocket** is a communication protocol which provides a full-duplex and low-latency channel between the server and the browser.

- Socket.IO is NOT a WebSocket implementation.

- Socket.IO is not meant to be used in a background service for mobile applications.

[For more information](https://socket.io/docs/v4/)

[Information about server API](https://socket.io/docs/v4/server-api)

[Information about client API](https://socket.io/docs/v4/client-api)


