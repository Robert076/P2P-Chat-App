#Usage

Start server:
  python3 server.py

Start multiple clients (at least 2 to experience the app completely):
  python3 client.py

The program will automatically assign udp ports that are free for each client so no need to worry about it.
Every client will see a message: [UDP Port]. Take that port and write in the other client terminal: CHAT IP(get this from server print) UDPPort MESSAGE
You should see a message on the client's side you sent it to.
