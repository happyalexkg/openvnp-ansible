This role installs OpenVPN, configures it as a client.

Tested OSes:
Ubuntu trusty (14.04)

Should be working OSes:
Ubuntu trusty & later
Debian 6 & later


Requirements
Openvpn must be available as a package in apt!

Role Variables
openvpn_dev_server:The device you want OpenVPN to use (example:tun)

openvpn_ca_cert:The CA certificate

openvpn_cert: The client certificate\n
openvpn_key_private:The Private Key from certificate\n
openvpn_tls_auth: The OpenVPN static key\n
openvpn_remote_cert: Require that peer certificate was signed "client" or "server"\n
openvpn_remote_ip: Remote host name or IP address\n
openvpn_remote_port: Remote host port\n
openvpn_remote_protocol: Remote host protocol\n


Dependencies
Does not depend on any other roles

Author Information
Written by Alexey Shalin# openvnp-ansible
