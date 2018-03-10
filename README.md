# Heltec WiFi Kit 32 OLED Example

## Overview

<p>
This is an example of how to learn by doing.  I've been a Microsoft stack developer for a long time and have just recently discovered microcontrollers.  I picked up a dev board from China for cheap and now it's time to do something with it.  So here are my high-level goals:
<ul>
  <li>Get a development environment configured</li>
  <li>Configure that development to connect to a microcontorller</li>
  <li>Write some code to display some text on a screen<li>
  <li>Push that code to said microcontroller and see the text<li>
</ul>
</p>
<p>
Now let me make some qualifying statements.  
<ol>
  <li>I've always used Visual Studio Enterprise in a Windows environment<li>
  <li>I don't know the Mac/Linux environment</li>
  <li>Although I've done extensive work in C#, I've never done anything in C/C++</li>
  <li>I have basic elecrtonics knowledge, maybe more than the layperson, but by no means an expert, or even advanced<li>
  <li>Did I mention I don't know anything about embedded development?<li>
</ol>
</p>

<p>
So, with all that in mind let's get started!
<br><br>
I picked up a few dev boards from China for cheap.  I've played around with them, but settled on the Heltec WiFi Kit 32.  This one happens to have LoRa.  
  <div align="center">
    <img src="http://www.heltec.cn/wp-content/uploads/2016/09/433%E4%B8%BB%E5%9B%BE%E6%9B%B4%E6%96%B0-800x800.png" alt-text="Heltec WiFi Kit 32 (LoRa)" width="75%">
  </div>
  I chose this one mostly because of the built in WiFi, Bluetooth and OLED screen, and because it was cheap.  Although this is what I'll be working with, it's using the ESP32 chip, so most dev boards based on ESP32 should work similarly, maybe with some minor (hopefully) tweaks.
</p>

#Setting Up Your Dev Environment
<p>Choosing an IDE</p>


## WHF is a Toolchain?
<p>Setting up the ESP32 tool chain</p>

## How to install MOS

- Install and start [mos tool](https://mongoose-os.com/software.html)
- Switch to the Project page, find and import this app, build and flash it:

<p align="center">
  <img src="https://mongoose-os.com/images/app1.gif" width="75%">
</p>

