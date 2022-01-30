<h1>
Using Ansible and Jinja2 templates to deploy an L2LS topology
</h1>

Steps:

1. define the inventory: Spines, Leaves, Hosts and their ip addr for access
    ~ equivalent to putting up all the devices on the screen in iterm
2. Start configuring the underlay components: interface modes/ip addr, vlans, svis, bgp conf, mlag conf