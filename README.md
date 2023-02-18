# [NICONET](https://github.com/lafelabs/niconet)

# NICONET

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




