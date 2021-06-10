# Elk-Stack-Project

In this project, I created a virtual cloud network and an ELK stack.

I first created a resource group to hold and link all the other elements of the virtual cloud network.

In the next step, I created a virtual network on which the project ran on, as well as a security group to add traffic rules to control what came in and
out of my network.

This next step was to create a virtual machine Jump Box in order for me to SSH into and access. (***LEARN MORE ABOUT THIS***)

Another virtual machine was created in order to host my mock enterprise website, as well as implementing all the detailed inbound and outbound security rules 
in my security group. A second virtual machine was created as well in the event that the first virtual machine went down.

I know began work creating the ELK stack by first creating its own virtual network and security group, as well as setting up a peering network
connection between the two virtual networks I had created.

I then created a virtual machine to host the ELK server.

I then downloaded and configured a container for the ELK server, and launched and exposed this container in order to launch the ELK server.

The next step was to download and configure a file beat file, as well as created an ansible playbook for the installation of
filebeat.

Lastly, I ran and checked to ensure the filebeat playbook installed by verifying that the ELK stack was receiving logs.

Upon this step, I now had a completely functioning virual cloud network and ELK stack.

***NOT FINISHED (I want to go into more detailed explanation of each individual step, but have not had the time. This will be something I continuously work on to improve.)***

