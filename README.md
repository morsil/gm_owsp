GameMaker - Open Websocket proxy
=======

OWSP laat GameMaker gebruik maken van Websockets.
D.m.v. een proxy gemaakt met socket.io (NodeJs) en speciaal gemaakte scripts voor GameMaker kunnen de server
en client snel en zonder te veel overhead met elkaar communiceren.

##Server functie lijst:
- 
        ws_init(ip_address, port[, mode = ws_binary])
- 
        ws_deinit()
- 
        ws_clearbuffer()
- 
        ws_write(data, buffer_type)
- 
        ws_send(client_id)
- 
        ws_receive(async_load)
- 
        ws_read(buffer_type)
- 
        ws_isConnected()
