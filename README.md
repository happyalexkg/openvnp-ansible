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
openvpn_cert: The client certificate
openvpn_key_private:The Private Key from certificate
openvpn_tls_auth: The OpenVPN static key
openvpn_remote_cert: Require that peer certificate was signed "client" or "server"
openvpn_remote_ip: Remote host name or IP address
openvpn_remote_port: Remote host port
openvpn_remote_protocol: Remote host protocol



Dependencies
Does not depend on any other roles

Author Information
Written by Alexey Shalin# openvnp-ansible
