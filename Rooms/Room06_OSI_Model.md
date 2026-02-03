# Room 06 — OSI Model

**Date:** 2026-02-02
**Path:** Pre Security  

## What I did
- Learned about the OSI Model and looked at each layer to understand what they do. Also did a game to further understand what OSI model works which was a dungeon I had to escape from and list the correct steps of the OSI Model.

## Key concepts
- OSI stands for Open Systems Interconnection Model which is used in networking.
- This model helps decide how all networked devices send receive and interpret data.
- Devices on the OSI model can have different functions and designs while still talking to other devices.
- Encapsulation is when pieces of information get added to the data.
- **Physical Layer**: Devices use their signals to transfer data in binary like a ethernet cable which connects devices.
- **Data Link**: Data link layer helps adds the pysical MAC address to the endpoint. Each network enabled computer has a NIC or Network Interface card which has a unqiue MAC address.
- **Network**: Allows for communcation between devices on different networks. Takes care of the most optimal path in which data should reach a device. OPSF = Open Shortest Path First, and RIP = Routing Information Protocol. IP Addresses are used in this protocol.
- **Transport**: TCP and UDP. TCP is Transmission Control Protocol which is reliable. Reserves a constant connection between the two devices for the amount of time it takes for the data to be sent and received. TCP has error checking. Slower than UDP. Guarantees accuracy of data however, if one chunk is missing than it all goes wrong. Slow connection breaks the while thing. TCP is used for emails, file sharing, or looking at the internet. These services require the data be accurate.
UDP is User Datagram Protocol. Not as advanced as TCP, and does not have error checking and reliability. The data isn't even guaranteed to get there just pray and hope. Much faster, does not reserve a continous connection. Unstable connections are bad. Used for discovering devices or large files like video streaming where some data missing isn't that bad.
- **Session** Creates and mantains the connection for computer data to where it is going. Once the connection is there then the session gets made. Connection active = session active. Closes the connection if it has not been used and sessions can have checkpoints in cse data is lost. Sessions are unique.
- **Presenatiation**: Ensures that data from the application layer is readable by the receiving system. Basically a data translator. Makes formats translated so it is easy to understand.
- **Application**: GUI or Graphical User Interphase is made by applications for users to interact with data being sent or recieved. DNS or Domain Name System is how websites are translated into IPs. 

## One takeaway
- The OSI model is key for transmitting data and takes place in our daily lifes.
