# Setting up a simple 21112 network complete with Quagga OSPF routing

The 21112 network simply refers to the network topology shown in the figure below.

![core in docker](./images/docker_install_of_core_and_quag-vtysh.png)

It is essentially 2 hosts - 1 switch - 1 router - 1 switch - 2 hosts, hence 21112.  It is a basic setup to 2 networks separated by a router:

1. 10.0.0.0/24
2. 10.0.1.0/24

that includes hosts and switches.

