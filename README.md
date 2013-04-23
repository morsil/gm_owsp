GameMaker - Open Websocket proxy
=======

OWsP laat GameMaker gebruik maken van Websockets.
D.m.v. een proxy gemaakt met socket.io (NodeJs) en speciaal gemaakte scripts voor GameMaker kunnen de server
en client snel en zonder te veel overhead met elkaar communiceren.

Server functie lijst:
---------------------
- ws_init()
- ws_deinit()
- ws_clearbuffer()
- ws_write()
- ws_send()
- ws_receive()
- ws_read()
- ws_isConnected()
