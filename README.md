# Mint-Fixes
This repository is created to keep information about problems on Linux Mint and how I resolved

VLC MEDIA PLAYER: "Codec Not Supported: VLC could not decode the format "h264" (H264 MPEG-4 AVC (part 10))":
Description: The Players does not play a lot of common types of media.
How to Fix:
  Reinstall Mint-Meta-Codecs and Ubuntu-restricted extras.
  
    sudo apt-get install --reinstall mint-meta-codecs
    sudo apt-get install ubuntu-restricted-extras

Reboot the computer.
