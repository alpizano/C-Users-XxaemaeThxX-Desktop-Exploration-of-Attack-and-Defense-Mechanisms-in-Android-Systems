# Exploration of Attack and Defense Mechanisms in Android Systems
![Android security hehe](https://github.com/alpizano/Exploration-of-Attack-and-Defense-Mechanisms-in-Android-Systems/blob/master/android_security.jpg)

# Introduction
This research consisted of exploring and implementing webview and repackaging attacks in the Android operating system, aswell as demonstrating exploits to develop countermeasures during Android development. Below, you will find the contents of this git repository, if you plan to download the files and follow along.

# Contents
0. Setup
1. Repackaging Attack

# 0. Setup
Initial setup starts with downloading the virtual machines used in this project. We will be using VirtualBox here, which can be downloaded from here:
https://www.virtualbox.org/wiki/Downloads

# 1. Repackaging Attack
The first android exploit we will be exploring is the Repackaging attack. The Repackaging attack is a very common type of attack on Android devices. In such an attack, attackers modify a popular app downloaded from app markets, reverse engineer the app, add some malicious payloads, and then upload the modified app to app markets. Users can be easily fooled, because it is hard to notice the difference between the modified app and the original app. Once the modified apps are installed, the malicious code inside can conduct attacks, usually in the background. For example, in March 2011, it was found that DroidDream Trojan had been embedded into more than 50 apps in Android official market and had infected many users. DroidDream Trojan exploits vulnerabilities in Android to gain the root access on the device.

We will need to download two virtual machine images for this, which can be found here:
http://www.cis.syr.edu/~wedu/seed/mobile_security.html

For instructions on setting up the SEEDAndroid5.1 VM image, read here:
http://www.cis.syr.edu/~wedu/seed/Documentation/Android5_1_VM/SEEDAndroid_VirtualBox.pdf

For instructions on setting up the MobiSEEDUbuntu14.04_x64 VM image, read here:
http://www.cis.syr.edu/~wedu/seed/Documentation/VirtualBox/UseVirtualBox.pdf


