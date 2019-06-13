Running a public node on a Raspberry Pi
-------------------------------
Running a public node on a Raspberry Pi is a very cheap and energy-saving way to support the BURST environment as it gets more decentralized and thus more stable.

### Step 1: Things to buy (or find somewhere around)

-   Raspberry Pi Model 3 B+ (incl. charging adapter / case)
-   At least 32 GB Micro-SD-Card

### Step 2: Setting up the Raspberry Pi

Visit the official Raspberry Pi website to set up the operating System. This tutorial uses the minimal image based on Debian Stretch (Raspbian Stretch Lite). Carefully work through the manual. The main steps are downloading the operating system and flashing the SD-Card (e.g. via Etcher).
-   https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up

### Step 3: Connecting your Pi via Putty

As the minimal operating system doesn´t have a graphical interface, follow this tutorial to get a connection via Putty. Don’t forget to reset the default password.
-   https://hackernoon.com/raspberry-pi-headless-install-462ccabd75d0

### Step 4: Installing the BURST Reference System (BRS)

Follow this guide to install the BRS on your Pi. Run all commands via Putty. If you don’t have enough rights to perform a certain operation, run the command via sudo. Note: The update of the database (“inflating brs.mariadb”) will take several hours.
-   https://burstwiki.org/en/brs-linux-installation/

### Step 5: Running a Full Node

Set up a public node using this tutorial:
-   https://www.reddit.com/r/burstcoin/comments/87l4sj/set_up_your_public_node/
Set the Parameter “P2P.myPlatform“ in the BRSWallet/conf/brs.properties file to your BURST Address in order to get the NDS-Award (Networtk-Distribution-Strengthen) from the BMF (BURST Marketing fund).
