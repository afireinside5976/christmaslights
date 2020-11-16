# 2020 Christmas Light Show

## Show Times and Dates

Show will run nightly from November 27, 2020 until January 2, 2021.

* Sunday-Thursday, 5:30 PM (17:30) until 10:00 PM (22:00)
* Friday and Saturday, 5:30 PM (17:30) until 11:00 PM (23:00)

### Rain Delays

During times of heavy rain, or in the worse case snow, the light show may be stopped to reduce the chance of 
electrical shorts occurring. If the show is cancelled, it is asked that you revisit 
another evening after the rain has cleared.

## Music

### Listen From Your Car

To listen to the light show, tune your radio to 90.3 FM.
It is asked that you keep your radio volume down to not disturb the neighbors. You are asked to remain in your 
car to observe social distancing guidelines and for your safety of traffic on the roadway.

### Show Playlist

The songs below are synchronized to the lights and play during 
[show times](#show-times-and-dates) on loop. The entire show is about 
15 minutes in length.

* Show Introduction
* Boyz II Men Countdown
* 20th Century Fox Theme
* Christmas Time Is Party Time - Luke
* Christmas Eve/Sarajevo - Trans-Siberian Orchestra
* Silent Night - The Temptations

### Offline Playlist

The songs below play on loop during non-showtime hours. Lights do not synchronize to music during 
non-show hours.

* Christmas in Hollis - Run DMC
* Christmas Song - Alvin and the Chimpmunks
* Christmas Time Is Party Time - Luke
* Knockin Boots on Christmas - H-Town
* What You Want for Christmas - Quad City DJs and K-nock
* Christmas Songs - Mariah Carey
* O Come All Ye Faithful - Luther Vandross
* Christmas Eve/Sarajevo - Trans-Siberian Orchestra
* Silent Night - The Temptations

## Hardware

### Raspbery Pi

The Falcon Pi Player is installed in the Raspberry Pi. The Rasberry Pi controls the relays, which in turn
controls all of the lights. The Pi controls each of the 24 channels of relays via the GPIO pins on the 
Raspberry Pi.

### Christmas Lights

All of the lights are LED. Only two colors are used for the light show. White and red.

### Relays

All of the relays are Solid State Relays (SSR). SSRs were used because they have no mechanical or moving 
parts and having greater reliability for being switched on and off frequently.

### FM Transmission

Music is transmitted over radio via a low-power FM transmitter. Music goes into the transmitter directly from the 
Raspberry Pi and broadcasted on an open frequency. Radio Locator in [Other Resources](#other-resources)
was used to locate the best frequency.

## Software

### Xlights

The music and light sequences are connected together using Xlights. This software is open source
and runs on most operating systems, including Windows, Linux, and Mac.

### Falcon Pi Player (FPP)

Once the sequences have been created in Xlights, those files are copied over to FPP. From there, the 
show data, music, and scheduling are all done within this software.

### Kdenlive

Kdenlive is a video editing tool. It can also be used to modify audio files. The show intro audio file was
modified with Kdenlive to have the voiceover and background music on the same track.

## Resources

Below are links to other websites and reference documentation that was used to build this light show.

### Light Show Websites

* <a href="https://sites.google.com/site/listentoourlights/home" target="_blank">Listen To Our Lights</a>
* <a href="http://www.lightinguppaxton.com/" target="_blank">Lighting Up Paxton</a>

### Resources and Other Information

* <a href="https://ttstool.com/" target="_blank">TTS Tool, for text to speech recordings</a>
* <a href="https://radio-locator.com/cgi-bin/vacant" target="_blank">Radio Locator, find vacant radio channels</a>
* <a href="http://www.falconchristmas.com/" target="_blank">Falcon Christmas</a>

## FAQ (Frequently Asked Questions)

### How do you keep the lights from shorting out in the rain?

Each connection that is on the ground is wrapped in electrical tape. That prevents water from 
coming in contact with the outlet, which would result in an electrical short, thus tripping the breaker and 
shutting down the show.

### How much does this cost?

Not sure. This is the first year doing an animated display, so there's no comparison from previous years.

### Why do you do this? 

Because looking at Christmas lights is cool!

### What have you done in previous years?

Use the navigation on the left to see the information about the previous years' shows.

### How can I get a copy of your sequences? 

You can get them from my 
<a href="https://github.com/almostengr/christmaslights" target="_blank">Github repo</a>. Each sequence is
designed for AC lights only.