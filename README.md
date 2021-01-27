# blobs
Recreation of agar.io created in Python

# How does it work
This game runs off a local network (every person playing is on the same wifi) meaning it runs off of your networks ip address.

Meaning multiple people can play from different computers

To use this program you'll need to go into **client.py** and change line #13:

self.host = "192.168.2.28" to self.host = "" (type in your networks ip where the blank is)

# How to get your network's ip
Run **server.py** and it will relay your ip to you

# How to play the game
To run the game you'll need to have **server.py** running

After **server.py** is up and running, run **game.py**

You can connect as many clients as you want from any computer as long 

A: **server.py** is running (only run on one computer)

B: Every computer has **client.py** edited with your local network's ip

# Game Mechanics
- Each game lasts 5 minutes
- The more mass you have the slower you move
- Players lose mass as at a rate based off of players mass (larger = faster loss)
- The game will be in "lobby" mode until started, this means all each player can do is move
- The game will begin once a client connects on the same machine the server is running on

# Potential Errors
If you are having connections issues try disabling the firewall on the server and client machines
