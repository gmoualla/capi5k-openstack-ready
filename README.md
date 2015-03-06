# My own version of capi5k-openstack

This repo is a clone of this one: https://github.com/capi5k/capi5k-openstack. 

It deploys OpenStack on [Grid5000](http://www.grid5000.fr) with 5 nodes for a duration of 7 hours on the Toulouse's site. 

In the future, it will automatically deploy the FRIEDA framework to manage data-intensive scientific applications and it will also install my own Python application which will handle the deployement of Virtual Machines (VM) on Grid5000 depending on the user's needs. 

Commands to execute the deployement: 

    cap automatic puppetcluster; cap puppetcluster
    cap openstack; cap openstack:bootstrap

When connected to the controller node:

    source demorc
    cd greenerbar   # Not available yet
    python main.py  # Not available yet
