![Rayhunter Logo - An Orca taking a bite out of a cellular signal bar](https://www.eff.org/files/styles/media_browser_preview/public/banner_library/rayhunter-banner.png)

# Rayhunter

![Tests](https://github.com/EFForg/rayhunter/actions/workflows/check-and-test.yml/badge.svg)

Rayhunter is an IMSI Catcher Catcher for the TP-link m7350 mobile hotspot. To learn more, check out the [Rayhunter Book](https://efforg.github.io/rayhunter/).

## Installing Rayhunter

You can install Rayhunter easily by downloading and running the installation script.

### Quick Setup

1. Download the latest release from the [Releases Page](https://github.com/PhucHauDeveloper/rayhunter-m7350v4/releases).
2. Extract the archive.
3. Open the extracted folder.
4. Run the `install.cmd` (Windows).
5. Follow the on-screen instructions.

After installation, the device will reboot and launch Rayhunter automatically. No manual telnet setup or firmware downgrades are required.

You can now access Rayhunter's Web UI at:

* `http://192.168.0.1:8080`


### 🚀 What's New in This Fork

This customized fork brings major usability and feature upgrades over the original Rayhunter release:

✅ OPKG Package Manager Included: 
Enjoy the flexibility to install whatever you need with 2.8MB of free space remaining. Explore available packages at [Entware Repository](http://bin.entware.net/armv7sf-k3.2/).

✅ Time Sync & Display Enhancements: 
The device now syncs time with your computer and displays it on the screen—alongside band, TTL, RSSI, RSRQ, and SNR—making the device more useful at a glance.

✅ Live Rayhunter Status Indicator: 
A #: symbol before the band indicates that Rayhunter is active. If it's missing, Rayhunter is inactive.

~~✅ Physical Button Toggle for Rayhunter:~~
~~Hold the top button for 2 seconds (while the screen is active) to enable or disable Rayhunter—perfect for reset the red line.~~
(is coming to main branch and mine is no longer a diff)

✅ Improved Security Defaults: 
SSH is enabled by default after installation, while Telnet is automatically disabled.

✅ Built-in TTL Modification Tool (ttlset): 
Easily change TTL values to help bypass carrier tethering restrictions.

✅ Integrated OpenVPN & cURL Support: 
VPN functionality and web tools are ready to go, plus the latest IPS updates are included for better network protection.

📌 These enhancements are designed to improve user experience and security while keeping installation simple and accessible.
