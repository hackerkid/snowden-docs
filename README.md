# snowden (HTTP Proxy Serever) Docs

This repo contains the docs for the HTTP proxy server which I made for the networking course. The source code would be made public once the evaluation is 
over at github.com/hackerkid/snowdn

##Installing

* Extract the compressed file
* open the folder in terminal
* run `make` in terminal for compiling and building the binary
* run `proxy Port` to start the proxy server in the desired PORT

##Testing
Go to the `Edit` menu in Firefox.
* Select `Preferences`. Select `Advanced` and then select `Network.
* Under `Connection`, select `Settings`.
* Select `Manual Proxy Configuration`. If you are using localhost, remove the
default `No Proxy for: localhost 127.0.0.1`. Enter the hostname (eg localhost) and port where
your proxy program is running.
* Save your changes by selecting `OK` in the connection tab and then select `Close`
in the preferences tab.



