# Xubuntu-22.04-Jammy-Jellyfish-Installation
This is the installlation of new OS Linux with Xubuntu using VirtualBox Machine


## Go to https://xubuntu.org/download/

## Download the version 22.04 Jammy Jellyfish in Torrent Downloads

## Install Utorrent to read a torrent file, if you have already, skip this process

## After modifiying and setup of utorrent, open the torrent iso file in Utorrent

## In VirtualBox Machine Click "New"

## Fill out the name and insert the ISO file that you moddify in Utorrent then click "Next"

## Unattended guest OS install setup
Create for a guest username and password

## Hardware
Recommended Base Memory: 4096 MB (Note: This will do if you have 8 GB Ram in your device)

Processor: 2

## Virtual hard disk
Set the Disk Size atleast: 30GB

Proceed to "Next"

## Begin the unattended installation
Click the Show (green arrow button) and you'll presented with a VM window

Take time to install and wait for the finish button

## You might possible to see this error, but disregard this and Start the Machine.
![image](https://github.com/Gino156/Xubuntu-22.04-Jammy-Jellyfish-Installation/assets/81914900/9cd0642b-50a2-465f-af33-1b8e7bf0f674)

## Setting correct sudo permissions
Navigate to users and group- click the icon left of your window, type "users", click "Users and Groups"

click "Manage Groups"

find "sudo"

Add yourself to sudo

Rebooot your VM:

To open terminal: press Ctrl + Alt + T and type "reboot" and press enter

Alternatively, just click the icon, look for power icon and restart

## Test your newly gained sudo privileges
Open terminal

use this command:

sudo apt update

sudo apt upgrade

Enter your provided password

Done!

shutdown your VM
