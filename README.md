## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

This version of the installer hopes to deploy the [most secure version possible](https://community.openvpn.net/openvpn/wiki/Hardening).

[x] [Pre-defined DHE groups 2048-bit](https://wiki.mozilla.org/Security/Server_Side_TLS#ffdhe2048)  
[ ] [Pre-defined DHE groups 4096-bit](https://wiki.mozilla.org/Security/Server_Side_TLS#ffdhe4096)  
[ ] tls-version-min=1.2  
[ ] tls-cipher  
[ ] tls-auth  
[ ] 2/M-FA using Google Authenticator  
