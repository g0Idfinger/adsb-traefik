# adsb-treafik

Allows you to put your ADSB containers behind a reverse proxy with basic authentication
Ensure to update .env with yoru vars
Ensure to create your secrets for basic auth and cloudflare

This configuration has 2 devices, adsb-server and server
adsb-server has my SDRs conneted to them and runs the containers Ultrafeeder and Dump798
they send their data to the server and feed into the other containers.

Thankst to:
https://www.smarthomebeginner.com/
https://github.com/sdr-enthusiasts

Without their guides I could have made this project.
