# Using SSH tunnels

Secure Shell (SSH) can be used to securely acquire and use a remote terminal session, tunnel traffic, transfer files, mount remote file systems, and more. 

SSH uses strong encryption, and you can set your SSH client to act as a Socks proxy. The traffic enters the Socks proxy running on your local system and the SSH client forwards it through the SSH connection – this is known as SSH tunneling. Once you have set it up, you can configure applications on your computer – such as your web browser – to use the Socks proxy. Each application must be configured to use the SSH tunnel’s proxy.

This setup works similar to browsing the web over a [Virtual Private Network (VPN)](vpn.md). From a web server perspective, traffic appears to be coming from the SSH server. The traffic between source and the SSH server is encrypted, so you can browse over an encrypted connection as you could with a VPN. 

## Port forwarding

Port forwarding or port mapping is a combined technique of:

  * Translating the address and/or port number of a packet to a new destination.
  * Possibly accepting such packet(s) in a packet filter (firewall).
  * Forwarding the packet according to the routing table.

SSH tunnels can be created in several ways using different kinds of port forwarding mechanisms. 

On Android you can use ConnectBot ([Google Play Store ConnectBot](https://play.google.com/store/apps/details?id=org.connectbot), [F-Droid ConnectBot](https://f-droid.org/en/packages/org.connectbot/)), a traditional-style SSH client, providing command-line access to computers 
running SSH server software. A GUI interface is available for setting up connections. ConnectBot can run pretty much 
all SSH commands, and fully supports persistent connections, key management, and port forward management.

