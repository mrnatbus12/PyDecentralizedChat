# PyDecentralizedChat

Decentralized P2P python based chat app w/ Rooms!!

Fundemantal ideas of project:
 Every Node keeps a copy of all the chat rooms they create or join in an instance, and whatever rooms someone who points to them as a peer creates,
 If everyone leaves a room, as in there is no active connections to the room at any given moment, the room is deleted, so, only active rooms are passed on to future nodes.
 
 if a node points to another node, and someone 

Upcoming updates:
1. autoamtic node finding, for now if the original peer you pointed to goes down you must manually restart and connect to a live node.
2. fancier cli

How to Use:

1. Clone Repo and ensure you're using python 3.6+
2. `python3 chat.py`
3. `[RUN AS NODE?] [Y/N]` --> Yes will instiantiate a server, you will then enter your local ipv4(further details below), or whatever IP you wish to bind the server to and your port , just ensure you have the proper permissions
4. ```
  [PEER INFO]
  [IP] >>> 
  [PORT] >>> 
  ```
  If you're not a node, you must enter a peer to sync to or else program will fail, if youre node you have 2 options:
    1. Sync with another node that already has room and recieve thier chat logs when you enter a room created on thier server
    2. Sync with yourself and create your own instance 
    
 
