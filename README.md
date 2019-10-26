# Den Automation Product API
Everything I've learned about the internal operation of Den Automation Ltd products. 

## Disclaimer 
I am a small shareholder in Den Automation Ltd, via Seedrs. I own several bits of Den Automation hardware.
I am *not* associated with Den Automation Ltd. 

## Den App is no longer functional.

## Communications
To communicate directly with the Den Hub, MQTT over Websockets is used. You can open a connection to the hub on port 1884, using the IP Address of the hub. There is a mDNS name available, but I don't have that to hand at present.

## Getting your credentials
This is the tricky part of using the API. I was able to get my credentials by sniffing the packets on the internet. I outline the process I used on my blog and I'll details the steps here. You're free to use whatever mechanism you wish to snif the packets going across the app.

### Connect your iPhone to Wireshark
