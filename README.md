# HAB Linux
A live USB distribution intended for HAB builders and trackers

## About
HAB Linux is a Linux distribution built specifically for HABbers - people who build, release and track high altitude balloons. It is an Xubuntu installation that is customised with softwre tools used by HAbbers. The release version is a disk image that you write to a USB memory stick, and then boot your computer from. Instructions for its build are provided in case you should want to build it yourself.

## Download
Current release: https://s3-eu-west-1.amazonaws.com/hablinux/hablinux1404_1.img

To install, see the document Use HAB Linux in this directory.

## Tools
The following changes are made to the standard Xubuntu installation:
* Pulseaudio upgraded to 5.0 to address the timing bug that stops fldigi from decoding
* UK keyboard layout selected
* UK servers for updates selected
* Additional software installed:
   * Skype
   * Git
   * Shutter screenshot tool
   * Dropbox
   * RTL-SDR
   * GQRX
   * DL-fldigi HAB version
   * Arduino
   * IDLE python development tool
   * 

## Build
If you want to build HAB Linux (or something similar) yourself, see the document Build HAB Linux in this directory.

## Feedback
Feedback welcome. Open an issue.
