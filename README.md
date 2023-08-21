# SP
Anti DDos for fivem server (SP) V 1.2

how to install 
#install
### Setup For FiveM - open SP.cfg
### replace xx.xx.xx.xx To Your IP from SP Anti DDoS.
Do not forget to delete these from the original server.cfg file
endpoint_add_tcp "0.0.0.0:30120"
endpoint_add_udp "0.0.0.0:30120"
-----------------------------------------
add this lines and start the resources
ensure SP-AntiDDoS
exec resources/SP-AntiDDoS/SP.cfg
