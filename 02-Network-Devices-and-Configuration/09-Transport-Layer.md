# 1. Transportation
- Responsibilities [Tracking conversation, segmenting and reasembling data, add header, identifying the app (port), multiplexing], **responsible for establishing a temporary communication session between the source and destination host applications**

# 2. TCP
- A TCP segment adds (**10 fields**) 20 bytes (i.e., 160 bits) of overhead when encapsulating the application layer data. 
- [src port, dst port, seq no, ack no, header len, reserved, control bits, window, checksum, urgent]
- **end-to-end connection needs to be established first before sending data**


# 3. UDP
-  has 4 fields (16 bits) and requires total 8 bytes (64 bits)
- **trivial file transfer protocal (UDP)**

# 4. port
- Socket [IP + port]
- {Well-know [0-1023], Registered [1024-49151], Private/Dynamic [49152-65535]}

# 5. TCP Communication
- control bit (Flag) : [URG, ACK, PSH, RST, SYN, FIN]
- session {start [3-way handsahek], end [2 * 2-way handshake]}
- "Note: Devices today use the **sliding windows protocol**. The receiver typically sends an acknowledgment after every two segments it receives. The number of segments received before being acknowledged may vary. The advantage of sliding windows is that it allows the sender to continuously transmit segments, as long as the receiver is acknowledging previous segments. The details of sliding windows are beyond the scope of this course."
- **seq used to reasemble**
- **window size used to flow control**