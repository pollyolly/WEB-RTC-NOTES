### Web-RTC-Notes

```
NAT - Network Address Translator
STUN - Session Traversal Utilities for NAT
     - Tell me my public ip/port through NAT
     - Free server
     - Doesnt work in Symmetric NAT
     - Work in Full-cone
     - Cheap to maintain
     - Default port 3478, 5349
     -
     Example how it work: Computer 1 <--[ip:port]--> Stun Server <--[ip:port]--> Remote Computer 
                          Computer 1 <-- [Files/Media etc] Remote Computer 1
                          
TURN - Traversal Using Relays around NAT
     - Expensive to maintain
     - Not free
     - Default port 3478, 5349
     - In case of Symmetric NAT we use TURN
     -
    Example how it work: Computer 1 <--[ip:port]--> Stun Server <--[ip:port]--> Remote Computer 
         Computer 1 <-- [Files/Media etc] Stun Server <-- [Files/Media etc] Remote Computer 1
         
ICE
SDP
Signaling the SDP
```
