# [NICONET](https://github.com/lafelabs/niconet)

[NICONET Working Group Meetings on YouTube live at 3:00 PM Mountain Time(5:00 Eastern 2:00 Pacific)  on Friday](https://www.youtube.com/live/scBOWZZ0R30?feature=share)

# NICONET

We believe that broadband access to both the global Internet and to local information resources are basic human rights which should be provided for free to all people everywhere all the time. We believe that the way to achieve this is to find the people who have the least access and give them free access first and work our way up to a free network for all of society.   This network is based on the principles of mutual aid and direct action: seeing a need and taking immediate action to fill that need without asking for permission.

The government and tech companies will not do this on their own, the only sustainable and scalable way to make this kind of network is for people to come together to build this ourselves, and get direct support for this activity from our communities.

NICONET is a truly free wireless network, named after a dog.  We use donated bandwidth, donated hardware, off-grid power, volunteer labor, and free software to distribute free internet in public spaces.  As our network grows, more and more people will rely on it for more and more tasks, and we can ask for more and more community support until it becomes self-sustaining.  No new money needs to be spent to do this on our model.

NICONET is self-replicating. We are building a system designed to be copied by anyone anywhere.  For this to replicate we need a structure which includes a non-profit which can take donations and organize volunteers, a mutual aid group(ideally the same people who take the donations and organize the clinics) who can be boots on the ground finding out community needs in public spaces and making sure those needs are met appropriately, a team of technology experts and teachers who can share knowledge about how to copy this in the build clinics we organize.  Build clinics are events where people can bring in donated hardware and volunteers will convert it all into either bridge nodes or mesh nodes for distribution to network operators.  


NICONET is also an artistic movement, overlapping with solarpunk.  We want all of our infrastructure to be as off-grid as possible, and to have as much living parts as possible, incorporating plants and fungi into the design of structures which carry and support our infrastructure. We can share artistic visions of this on social media with hashtags #niconet and #solarpunk.  Our vision of solarpunk is very  organic, maximalist, rainbow-colored, and built from trash.


There are 2 types of NICONET node: the mesh node and the bridge node.  Mesh nodes are fully mobile, can be wearable, in a backpack, on a cart, in a vehicle like a car or truck or van or camper or bike, or put up somewhere as a piece of public art.  They should have no personal or private property or data on them, and be able to be destroyed or lost without damaging the overall viability of the network.  Mesh nodes are how network operators distribute free wireless to our community, taking the node to where the people are and making sure they can get on, adding more nodes if they need them to get connectivity.  Bridge nodes are fixed installations in the locations where volunteers are willing to host a node and donate bandwidth.  They can have antennas pointed to public hotspots from windows or rooftops which connect to a mesh node and the rest of the local network.  These nodes can be built into flower boxes and other planter structures to make organic infrastructure.


WANTED: volunteers to help build this.  We need at least one OpenWRT guru who does not have to be local but who can do builds and work with us to make sure they work before we try them here.  We also need at least one person to be a teacher of this system here in Denver who can teach others to replicate the system and help us to run clinics where we take donated hardware and turn it into either mesh nodes or bridge nodes. We are also looking for volunteers who are willing to share their home or business internet connection with the local community directly around wherever they are, to help those in need of access who are denied it by our current Internet system.  To contribute you could just build the nodes and document that and message Trash Robot at lafelabs[at]gmail[dot]com and I'll add it to this document.  

Current development is centered in Denver, Colorado and is organized by Denver Street Stories and Trash Robot.

## Setup Guide largely lifted from ChatGPT:

This document describes how to set up a network consisting of bridge nodes and mesh nodes using OpenWrt.

## Bridge Nodes

To set up a bridge node:

1. Install OpenWrt on your router or Raspberry Pi board by following the instructions in the OpenWrt documentation:
   - [Installation on Raspberry Pi](https://openwrt.org/toh/raspberry_pi_foundation/raspberry_pi)
   - [Installation on common routers](https://openwrt.org/docs/guide-user/installation/start)
2. Once OpenWrt is installed, log in to the router or board and navigate to the Network > Wireless section of the web interface.
3. Click the "Scan" button to search for available WiFi networks.
4. Select the WiFi network you want the bridge node to connect to and click the "Join Network" button.
5. Configure the WiFi network settings as needed, including any security settings like WPA2.
6. In the "Interface Configuration" section, select "Create a new wireless network".
7. Configure the new wireless network with the following settings:
   - ESSID: NICONET
   - Mode: Access Point
   - Encryption: None
8. Click "Save & Apply" to save the configuration and restart the wireless network.

Your bridge node is now set up and should be broadcasting a free wireless network named "NICONET" that is separate from the protected WiFi network it is connected to.

## Mesh Nodes

To set up a mesh node:

1. Install OpenWrt on your router or Raspberry Pi board by following the instructions in the OpenWrt documentation:
   - [Installation on Raspberry Pi](https://openwrt.org/toh/raspberry_pi_foundation/raspberry_pi)
   - [Installation on common routers](https://openwrt.org/docs/guide-user/installation)
2. Once OpenWrt is installed, log in to the router or board and navigate to the Network > Wireless section of the web interface.
3. Click the "Scan" button to search for available WiFi networks.
4. Select the "NICONET" network and click the "Join Network" button.
5. Configure the WiFi network settings as needed, including any security settings like WPA2.
6. In the "Interface Configuration" section, select "Create a new wireless network".
7. Configure the new wireless network with the following settings:
   - ESSID: NICONET
   - Mode: Mesh Point
   - Encryption: None
8. Click "Save & Apply" to save the configuration and restart the wireless network.

Your mesh node is now set up and should be able to connect to any network with "NICONET" available, including bridge nodes and other mesh nodes.

## AMAZON LINKS

 - [$40 ROUTER VONETS VAP11S](https://www.amazon.com/dp/B08YR9WLTF/)
 - [$25 INIU Portable Charger, 22.5W 10000mAh Small USB C Power Bank](https://www.amazon.com/dp/B09176JCKZ)
 - [$30 BLAVOR 10W Portable Solar Charger(5V/2A Max), Waterproof IP65 Foldable Solar Panel with Dual Smart USB Output](https://www.amazon.com/dp/B0BJDBQXQ3)

### QR CODE FOR THIS GITHUB.COM/LAFELABS/NICONET: 

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/qrcode.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/batterybox.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/batterybox2.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/routerbatt.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/routerbatt2.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/routerbox.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/solar1.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/solar2.png)

![](https://raw.githubusercontent.com/LafeLabs/niconet/main/trashmagic/solar3.png)




