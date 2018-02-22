# web-proxy
Script to quickly install web-proxy with self-signed certificate to bypass most blockages. <br />
I'm just a hobbyist that took stuff already made from left and right and compiled it to suit my needs, <br />
if it helps anyone else then better :) <br />
This script will install php-proxy and Glype (as backup) running through Nginx on a Debian like distro fresh install. <br />
It will install self signed certificate with default values. <br />
This script was made to quickly create a functioning SSL web proxy, security has not been ehanced, <br />
SSL is just there to avoid proxy servers like Barracuda or Squid to read data and understand that we are trying to run a web proxy. <br />
I obviously don't take any responsability on how this script could be used. <br />
 <br />
 <br />
Script is made to be run as root!
 <br />
 <br />
Install : <br />
```
wget https://raw.githubusercontent.com/roddsrod/web-proxy/master/prx.sh && chmod +x prx.sh && ./prx.sh
```
 <br />
 <br />
 Point to https://YourServerIP and you should see the web proxy running (since it's a self signed certificate the browser will tell you it's an untrusted site, accept the risk and there you go.
