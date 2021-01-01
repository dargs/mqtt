Testing out some mqtt stuff on Unexpected Makers WOPR  https://unexpectedmaker.com/shop/wopr-missile-launch-code-display-kit
https://github.com/UnexpectedMaker/wopr/tree/master/WOPR_Display

client.subscribe("esp32/output"); // (on/off) * heartbeat 

client.subscribe("wopr/missile"); // ("clock", "ntp", "missile", "message") 

client.publish("wopr/status", "connected"); // status back to node red. 
        
