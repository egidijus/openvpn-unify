openvpn-unify
=============

this script will create a unified open-vpn configuration file from server and user certificates and keys
the end user will have one file to manage and to use for connecting to the open-vpn server.

This will also work for creating open-vpn unified configs for ipad and iphone devices.

usage: `openvpn-unify <common-name-of-certificate>`

you may want to change these bits to reflect your configuration:


in `openvpn-unify`
keyHome="/etc/openvpn/keys"
templateHome="/etc/openvpn/easy-rsa"
binHome="$templateHome"

in `template.ovpn`
remote yoursite.com 1194

