# openTAKpickList
a list of hardware and software to be used in conjunction with the TAK platform.

## Software

### TAK platform
#### Clients
- ATAK: available from the playstore (reduced version) full version for all architectures here TBD
- WinTAK: [v4.1.0.231](https://drive.google.com/file/d/1BSdTpMVPlQj53W-aH83Vldc_bJpB9ZZQ/view)
- iTAK: Not publicaly available.
- webTAK:	- WebTAK: Only available with the official TAK Server.
- [CoT Beacon (and CoT Generator)](https://github.com/jonapoul/cotgenerator): a simple beacon  that send the position of team memebers without using ATAK. works on Android
- [FreeTAk UAS](https://play.google.com/store/apps/details?id=org.FreeTak.FreeTAKUAS&hl=en_US&gl=US): Android application to control your DJI drone and stream video and position to conneccted TAK clients
- [TAK tracker](https://play.google.com/store/apps/details?id=gov.tak.taktracker&hl=en_CA&gl=US): TAK Tracker is a “send only” version of ATAK. THERE IS NO MAP.

#### Servers
- TAK server: Non available to the public
- FreeTAKServer: [connects sever TAK clients](https://github.com/FreeTAKTeam/FreeTakServer)
- (FreeTAKServer Docker) [https://github.com/FreeTAKTeam/FreeTAKServer-Docker]

### ATAK Plugins
- [Hammer / ARIK](https://play.google.com/store/apps/details?id=com.atakmap.android.cot_utility.plugin&hl=en_CA&gl=US): HAMMER is an ATAK plugin that acts as a software modem and allows transmission/receipt of Cursor on Target (CoT) messages over voice communications. This means that two ATAK devices can communicate with each other over any voice-capable radio, e.g., commercial off the shelf walkie talkies. While it is anticipated that this will be extended in the near future, HAMMER currently supports sending and receiving CoT map markers, self-reported locations and chat messages.
- [TAK Fowarder](https://github.com/paulmandal/atak-forwarder)
- [CoT Generator Plugin](https://github.com/jonapoul/cotgenerator-plugin) (currently requires building and signing yourself)

NON AVAILABLE PLUGINS
- ES Chat	creates a PTT button over the screen (no configuration?)
- oceusvpn	unclear, not functional?
- pdfdocuments	display PDF documents from download folder only
- ads-b	Privides air Traffic Control Data (reqiires external Hardware)
- AR repeater	Augmented reality feed information and location to the augmented reality system
- BlockGenerator	generates a block from a polyline (??)
- DSM Manager	digital surface model for viewing terrain and building heights
- GlenairStarpan	STAR-PAN™ Integrated Soldier Multiport USB Data Hub / Power Distribution Systems and Tactical Interconnects
- HUD	unclear, probably send COT information to a hardware connected device (ARC4 and e COTI see https://www.ara.com/products/arc4-recon
- IceTAK	Instant connect. looks like PTT voice over IP instanconnect.com
- manifest maker	creates cargo manifest for prisoners (!)
- QM elevation	mesh elevation data provided by Cesium
- Reports	reporting tool that includes counter Intel Threat Reporting
- sip	used as a basis to develop voice over IP clients
- Somewear	satellite access , proprietary
- takchat	provides XMPP chat
- trackexport	automates export of GPS, track data
- beartooth TAK	allows to use beartooth offgrid with ATAK
- CBRN plugin	CBRN sensors integration plugin. allow to display chemical, batteriological, nuclear info
- geep portable	plugin for the creation of portable maps
- gotenna Pro	connects the product to ATAK
- GvLFStreamer	aka DTED Streamer. Connect to server IP 8080/gvlf-server
- icom	Kopis mobile MMRIS. addon to use regular radios
- NEON	allow to use the NEON offgrid tracking system. see https://www.trxsystems.com/personnel-tracker-offline.html
- Wave	plugins for radio
- wave relay	wave relay monitor
- wide Area Search	WASP set of icons to assess conditions of structurs and people in case of an emergency. can broadcast auomatically COTs
- Chokepoint	Provide calculation of stategic points necessary to hold a region
- cloud FTP	allows to connect to FTP servers.
- Compass nav	display a big navigation interface that helps navigate to a certain point
- Drifter	allow to simulate the direction and speed of any COT
- data sync	former Mission. can display a timeline of data; works with server groups
- ExCheck	allows to create and consumer cohoperative task lists
- geoTAKCam	add a separate interface for the camera to the phone, adding the ability to put an layer with geo information
- gotennapro ag	new version of GoTenna Pro?
- gotennaConsumer	allow to connect to a radio that transmit data (position, chat, ...) require device
- grg builder	create a grid that can be drop on the map and shared with others
- Hammer	allow to use regular radios for Data transmission
- QuickLog	provide an inteface to take notes (not possible to exchange them (!)
- quickchat	works on the por of geochat to improve the ui ??? need test
- TAK geoCam	geospatially savy Android Camera. add a separate aoo for the geocamera to the phone, adding the ability to put an layer with geo information
- TAK ICU	add a separate app for to the phone remote video capability (including broadcasting of videos)
- Uas tool	alow to fly a DJOI drone (with SDK) using ATAK and stream COTs
- VNS	vehicle Navigation system. add commercial like navigation capabilities to ATAK
- wxreport	weather report. works for forecast in Canada
- Meshtastic	callled ATAK Forwarder. Allows you to connect meshtastic LORA device through ATAK
- Bounce-Viewer	allows to use a trowable camera in ATAK

### Libraries


### MAPS
- [ATAK Maps] (https://github.com/joshuafuller/ATAK-Maps)

## Hardware

### Microservers
- [Pi:](https://www.amazon.com/CanaKit-Raspberry-Basic-Kit-8GB/dp/B08DJ9MLHV/ref=mp_s_a_1_3?dchild=1&keywords=pi4+8gb+raspberry&qid=1613526745&sprefix=pi4+&sr=8-3) CanaKit Raspberry Pi 4 Starter Kit (8GB RAM)
- [PI case:](https://www.amazon.com/Argon-Raspberry-Heatsink-Supports-Accessible/dp/B07WMG27T7/ref=mp_s_a_1_1_sspa?dchild=1&keywords=argon+neo+raspberry+pi+4+case&qid=1613526849&sprefix=argon+neo&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzUDFTTTZDQjlYU1FMJmVuY3J5cHRlZElkPUEwMTk0OTI1MjZOV0pHR1lTSkgzTCZlbmNyeXB0ZWRBZElkPUEwNjQyNjYyMTNaTEZQMExIVUFMVSZ3aWRnZXROYW1lPXNwX3Bob25lX3NlYXJjaF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl) Argon NEO Raspberry Pi 4 Case 

### GPS

### Range finders

### Radios

### Off-grid Comms
- Meshtastic: Use with ATAK Forwarder Plugin. [Project Page](https://www.meshtastic.org/)
    - Latest recommended hardware revision: [T-Beam V1.1 w/ NEO-M8N /w SX1262](https://www.amazon.com/TTGO-Wireless-Bluetooth-NEO-M8N-Battery/dp/B08GK8JP7Y/ref=sr_1_15?dchild=1&keywords=TTGO&qid=1613529697&sr=8-15)
    - Compatible case for 3D Printing: [T-BEAM_M8N_Case_Molle_IMA_v0.4_10FEB2021.stp.zip](https://discord.com/channels/698067185515495436/699733695333924976/809569287177371668)
- goTenna
- Radacat

## Gear
### Phones

### Cases

## Development
### Tools
- scrcpy: This application provides display and control of Android devices connected on USB (or over TCP/IP). It does not require any root access. It works on GNU/Linux, Windows and macOS.



