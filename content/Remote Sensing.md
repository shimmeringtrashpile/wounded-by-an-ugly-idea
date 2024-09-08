### DC32 Badge Aerospace Village at DEFCON 32
https://www.aerospacevillage.org/dc32-badge
The headlining feature of the badge is its ability to natively receive and display nearby aircraft using the ADS-B signals that most aircraft transmit. What normally takes specialized components and an SDR to receive the 1090 MHz signal, this badge uses some hardware hacks and clever trickery to make regular components do the work.
## Saline Valley
Military aircraft utilize radio communications on either 256.8 MHz or 123.95 MHz while operating in the Saline MOA; however, military aircraft throughout the R-2508 complex often use 315.9 MHz when conducting low altitude operations below 1500' AGL.
https://en.wikipedia.org/wiki/Saline_Valley#:~:text=The%20Saline%20Military%20operations%20area,from%20FL180%20up%20to%20FL600.
## MUOS

The **Mobile User Objective System (MUOS)** has been developed to complement the US military’s current narrowband tactical communications system known as the **Ultra High Frequency Follow-on** system – UFO for short.

The MUOS space and ground segments consist of five orbiting satellites (one is a spare satellite) and four ground stations respectively. In this system, which mimics a cellular-like service, the satellites effectively act as cell towers to support communication. The user segment comprises of UHF radios, which have been upgraded to support the new MUOS **Wideband Code Division Multiple Access (WCDMA)** waveform. MUOS-capable radios, accompanied by muos antenna, are and will be installed on aircraft, ships, and ground platforms, and are used by dismounted soldiers to enable beyond line of sight (BLOS) communications.

Built around the commercial 3G cellular technology, MUOS improves the performance of the network system and has a capacity 10 times greater than the legacy **UFO SATCOM**. It enables voice, video and data transmission over a secure, high-speed Internet Protocol (IP) based and net-centric network.

MUOS will enable more users to access the system when they need it and wherever they need it including Polar regions. The new satellite system supports stable on-the-move and point-to point (P2P) communications. In addition, MUOS integrates with the **Global Information Grid (GIG)** and can connect to the **Defense Information System Network (DISN)**, the Department of Defense (DoD) network, over satcom.

As it continues to operate in the UHF spectrum, UFO SATCOM is less susceptible to blockages and attenuations by difficult terrain conditions, foliage and other obstructions, compared to higher frequency signals.

## Dig into
- Get my PC up and running with SDR# etc.
- UHF Satcom - 240-318 MHz
- https://db.satnogs.org/satellites/
- Try out Artemis Radio Signals Recognition Manual https://www.aresvalley.com/artemis/
- SDRUno and plugins (in my download folder)
- Monitoring Paper - Monitoring, Surveillance, and Management of the Electromagnetic Spectrum: Current Issues in Electromagnetic Spectrum Monitoring
- Tactical Communications Satellites (TacSat)
### ADS-B
- ADS-B and VDL2 on Krakens - https://www.youtube.com/watch?v=s88GWjewU10
	- ADS-B ES on 1090Mhz: ADS-B 1090ES operates on 1090 MHz and is required for aircraft operating above 18,000 FT MSL. 1090 MHz Extended Squitter (ES)
	- ADS-B UAT - 978Mhz - the FAA was concerned about 1090MHz congestion, so they added UAT (on 978MHz) as an alternative. added free weather (FIS-B) to encourage General Aviation owners to choose UAT (Universal Access Transceiver)
	- ACARS
	- VDL2 VHF Digital Link Mode
- Satcom Bands See especially X and Ka - https://uhf-satcom.com/satellite-reception
- San Bernardino Microwave Society - http://www.ham-radio.com/sbms/
- MultiPSK - http://f6cte.free.fr/index_anglais.htm
- Mapping ADS-B on Virtual Radar Server - https://www.virtualradarserver.co.uk/
- Tin Can discone - https://lucsmall.com/2017/02/06/making-antennas-for-1090mhz-ads-b-aircraft-tracking/
- ADS-B colinear - https://nerdsville.blogspot.com/2013/05/video-making-ads-b-collinear-antenna.html?utm_source=feedly&utm_medium=feed&utm_campaign=Feed:+PleaseIgnore+(Please+Ignore)
### ACARS
- ACARS - _ACARS_ is a digital datalink system for transmission of short messages between _aircraft_ and ground stations via airband radio or satellite. ACARS messages may be of three broad types:
	- [Air traffic control](https://en.wikipedia.org/wiki/Air_traffic_control "Air traffic control") messages[[5]](https://en.wikipedia.org/wiki/ACARS#cite_note-5) are used to request or provide clearances.
	- [Aeronautical operational control](https://en.wikipedia.org/wiki/Aeronautical_Operational_Control "Aeronautical Operational Control")
	- Airline administrative control
	ACARS Types
	- ACARS - ARINC: Control messages are used to communicate between the aircraft and its base, with messages either standardized according to ARINC Standard 633, or user-defined in accordance with ARINC Standard 618.[[6]](https://en.wikipedia.org/wiki/ACARS#cite_note-6) The contents of such messages can be OOOI events, flight plans, weather information, equipment health, status of connecting flights, etc.
	- ACARS - SITA: SITA or _Société Internationale de Télécommunications Aéronautiques_, was founded in February 1949 by eleven [airlines](https://en.wikipedia.org/wiki/Airline "Airline") in order to bring about shared infrastructure cost efficiency by combining their [communications](https://en.wikipedia.org/wiki/Airline_teletype_technology "Airline teletype technology") networks. The eleven original airlines were: [British European Airways Corporation](https://en.wikipedia.org/wiki/British_European_Airways_Corporation "British European Airways Corporation") (BEAC), [British Overseas Airways Corporation](https://en.wikipedia.org/wiki/British_Overseas_Airways_Corporation "British Overseas Airways Corporation") (BOAC), [British South American Airways](https://en.wikipedia.org/wiki/British_South_American_Airways "British South American Airways") (BSAA), [KLM](https://en.wikipedia.org/wiki/KLM "KLM"), [Sabena](https://en.wikipedia.org/wiki/Sabena "Sabena"), [Swissair](https://en.wikipedia.org/wiki/Swissair "Swissair"), [TWA](https://en.wikipedia.org/wiki/TWA "TWA"), Swedish A.G.Aerotransport, [Danish Air Lines](https://en.wikipedia.org/wiki/Danish_Air_Lines "Danish Air Lines"), [Norwegian Air Lines](https://en.wikipedia.org/wiki/Norwegian_Air_Lines "Norwegian Air Lines") and [Air France](https://en.wikipedia.org/wiki/Air_France "Air France").
	- ACARS - VHF Data LInk (VDL) Mode 2: - Since 2000, ACARS avionics were modified to use VDL when in coverage of a VDL ground station. SITA began adding VDL radios to existing stations and keeps adding VDL coverage where needed. ACARS avionics fall back to VHF analog low speed outside VDL station coverage.
		- - 136.100 USA (ARINC)
		- 136.650 USA (ARINC)
		- 136.700 USA (ARINC)
		- 136.800 USA (SITA)
		- 136.675 Europe (ARINC)
		- 136.725 Europe (ARINC)
		- 136.775 Europe (SITA)
		- 136.825 Europe (ARINC)
		- 136.875 Europe (SITA)
		- 136.975 Worldwide (SITA & ARINC)
		- AERO
	- JAERO - **[JAERO](https://github.com/jontio/JAERO)**
	- ADS-C C-Band Aero https://jontio.zapto.org/hda1/c-band-ads-decoding.html
- Tech Minds
	- Make Your Own Aircraft Tracking Antenna With RTL SDR https://www.youtube.com/watch?v=TZaENuE_qu8 orhttps://www.hamradio.com/detail.cfm?pid=H0-008158
	- MilSat - https://www.youtube.com/watch?v=Xdc7l0O5fYo
		- https://www.thingiverse.com/thing:3095385
	- Inmarsat and ACARS from Inmarsat
		- https://www.youtube.com/watch?v=OkRbvtm3BfE
		- Nooelec Filter https://www.amazon.com/Nooelec-SAWbird-iO-Ultra-Low-Applications/dp/B07K1NMC23/
		- scytalec viewer - a C# PC-based open source decoder https://bitbucket.org/scytalec/scytalec/src/develop/
		- https://bitbucket.org/scytalec/workspace/repositories/
		- https://www.rtl-sdr.com/scytale-c-a-new-inmarsat-std-c-decoder-tekmanoid-std-c-decoder-updates/
		- https://www.rtl-sdr.com/rtl-sdr-tutorial-decoding-inmarsat-std-c-egc-messages/
		- https://thinair.aelogic.com/scytale-c-how-to-videos-rx-inmarsat-c-std-c-and-messages-using-open-source-software/
		- How to video: https://www.youtube.com/watch?v=vIm9GxTcGZ4
		- https://usradioguy.com/inmarsat-decoding/
		- 
- Decoding Digital
	- RTL-SDR TUTORIAL: DECODING DIGITAL VOICE (P25, DMR, NXDN, D-STAR) WITH DSD: https://www.rtl-sdr.com/rtl-sdr-radio-scanner-tutorial-decoding-digital-voice-p25-with-dsd/
	- Decoding P25: https://www.youtube.com/watch?v=iAXclsdo8do&t=15s
	- VDL2/VDL-M2 - https://www.sigidwiki.com/wiki/VHF_Data_Link_-_Mode_2_(VDL-M2)
		- Dump VDL2 https://www.rtl-sdr.com/dumpvdl2-lightweight-vdl2-decoder/
		- 
	- 
- DMR - Digital Mobile Radio - Decoding
	- [SDRangel](https://github.com/f4exb/sdrangel/releases) has built-in DMR (among other digital modes) decoder.
	- - SDRAngel has a builtin DMR demodulator
	- SDR# has [this](https://www.rtl-sdr.com/simple-dmr-plugin-for-sdr-now-available/) community plugin for DMR that works pretty well.
	- SDR++ needs a virtual cable (like _VBcable_ or _Voicemeeter_) to send the signal to [_DSDplus_](https://www.dsdplus.com/download-2/)
	- [SDRtrunk](https://github.com/DSheirer/sdrtrunk), comes with builtin DMR and other protocol support
	- SDRuno has a [community](https://www.sdrplay.com/plugins/) DMR demodulator plugin
- HFGCS
	- https://en.wikipedia.org/wiki/High_Frequency_Global_Communications_System
	- https://mt-milcom.blogspot.com/2006/05/joint-chiefs-of-staff-hf-gcs-network.html
- The Spectrum Monitor Back Issues
-  ADSB
	- Nooelec Filter - https://www.amazon.com/Nooelec-SAWbird-ADS-B-Dual-Channel-Applications/dp/B0CBD1KK3G/
- SDR Trunking
	- FM Narrow - Analog
	- Digital
		- P25 Phase 1: 
		- P25 Phase 2:  Uses the AMBE2+ vocoder, which allows audio to pass through a more compressed bitstream and provides two TDMA voice channels in the same RF bandwidth (12.5 kHz)
		- LTR: Analog Trunking System
		- DMR: 
		- MDC-1200: https://en.wikipedia.org/wiki/MDC-1200 **MDC** (Motorola Data Communications), also known as **Stat-Alert**, **MDC-1200** and **MDC-600**, is a [Motorola](https://en.wikipedia.org/wiki/Motorola "Motorola") [two-way radio](https://en.wikipedia.org/wiki/Two-way_radio "Two-way radio") [low-speed](https://en.wikipedia.org/wiki/Bitrate "Bitrate") data system using audio frequency shift keying, (AFSK). MDC-600 uses a 600 [baud](https://en.wikipedia.org/wiki/Baud "Baud") data rate. MDC-1200 uses a 1,200 baud data rate. Systems employ either one of the two baud rates. Mark and space tones are 1,200 [Hz](https://en.wikipedia.org/wiki/Hertz "Hertz") and 1,800 Hz. The data are sent in bursts over the radio system's voice channel.
## Locations
250th St E.

### Links

NGA Geomatics
https://earth-info.nga.mil/

Gunter's Space Page Listing of Military Satellites
https://space.skyrocket.de/directories/sat_mil_usa.htm

JTRS: Joint Tactical Radio System (JTRS)
https://en.wikipedia.org/wiki/Joint_Tactical_Radio_System

JPALS (Joint Precision Approach and Landing Systems)
The **Joint Precision Approach and Landing System** (JPALS) is a key component enabling U.S. military forces to be highly mobile and capable of "rapid response" on a global basis to a wide range of military scenarios. Similar in concept to the civilian Local Area Augmentation System (LAAS), JPALS will be based on differential Global Positioning System (GPS) technology, and will consist of modular avionics and ground/shipboard components to provide a range of landing minima and system configurations.

## Projects
Web Map of R-2508: http://127.0.0.1:5500/r-2508.html

### Gear
Uniden SDS200: https://uniden.com/products/copy-of-sds200
Uniden BC125AT: 
Honda Fourtrax Recon: https://powersports.honda.com/atv/recutility/fourtrax-recon

## Objects
#### MUOS Satellites 
https://space.skyrocket.de/doc_sdat/muos-1.htm
#### B21 Raider
https://en.wikipedia.org/wiki/Northrop_Grumman_B-21_Raider

The T-7A advanced jet trainer, which arrived at Edwards only a day before the B-21 from St. Louis.  It’s the first of five dedicated T-7A test aircraft that will be put through its paces over the next two years.

The B-52 test force will grow to eight or more aircraft, as Stratofortresses on loan from Air Force Global Strike Command (AFGSC) arrive to evaluate its new radar, engines, weapons, and a series of navigation and communications upgrades.

The X-62A, a highly modified F-16 that will test autonomy functions.

The new F-15EX fighter.

Collaborative Combat Aircraft (CCAs), intended to be autonomous or semi-autonomous partners for crewed fighters. 

The AIM-260 Joint Advanced Tactical Missile, the next-generation, long-range dogfight missile for Air Force fighters. 

The Next-Generation Air Dominance (NGAD) fighter, a super-stealthy fighter to succeed the F-22

The F-35 and its Block 4 upgrades, as well as a new version of its F135 engine.

The Hypersonic Attack Cruise Missile,  an air-breathing, Mach 5-plus weapon.

#### LGM-35A
https://www.afnwc.af.mil/News/Article-Display/Article/3319317/air-force-conducts-sentinel-static-fire-test/

#### X-59
X-59 Rollout: https://www.nasa.gov/feature/special-report-x-59-rollout/

## Locations
#### Plant 42
https://en.wikipedia.org/wiki/United_States_Air_Force_Plant_42
https://maps.app.goo.gl/ge2S2Juk8t4SNLvG9
#### Rogers Peak
Rogers Peak Multi-Use Instrumentation and Communication Facility
https://parkplanning.nps.gov/projectHome.cfm?projectID=74087
#### Mazourka Peak
168.625 PL 110.9 + 315.90 AM - Mazourka Peak repeater site - Owens Valley - 9,420 feet elevation
https://forums.radioreference.com/threads/range-2508-cross-patch-users-guide.392074/
https://www.fs.usda.gov/sites/default/files/2019-06/r-2508_complex_airspace_crosstalk_use_guide_508_0.pdf

#### Edwards VORTAC
https://maps.app.goo.gl/m2q4uKZicPDXozno9
Omni-directional Range/Tactical Air Navigation
This is a station composed of a VOR for civil bearing information and a TACAN for military bearing information and military/civil distance measuring information. The TACAN transponder performs the function of a DME without the need for a separate co-located DME.
https://en.wikipedia.org/wiki/Tactical_air_navigation_system
EDW - Edwards VORTAC
Frequency: 116.4
34° 58′ 56.5″ N, 117° 43′ 57.4″ W
EDW to airport:
066° | 6.3 nm

PMD - Palmdale VORTAC
Frequency: 115.55
34° 37′ 53.0″ N, 118° 3′ 49.8″ W
PMD to airport:
030° | 31.7 nm

VCV - Victorville (VOR/DME)
Frequency: 109.05
34° 35′ 39.0″ N, 117° 23′ 24.0″ W
VCV to airport:
323° | 26.8 nm

NID - China Lake
Frequency: 111.6
35° 41′ 16.5″ N, 117° 41′ 25.8″ W
NID to airport:
160° | 41.2 nm

### Edwards Groups
#### VX-9 Det Edwards 
VX-9 Det Edwards is tasked with operational test and analysis of emerging F-35 capabilities and weapons, as well as tactics development and aiding the fleet integration of the F-35C into the carrier air wing.
https://www.edwards.af.mil/Units/VX-9-Det-Edwards/

#### 412th Test Wing
The 412th Test Wing is the host wing for Edwards Air Force Base, Calif. - the 2nd largest base in the Air Force. The wing oversees base day-to-day operations and provides support for over 10,000 military, federal civilian and contract personnel assigned to a 470 square mile installation. Approximately 1500 Test Wing Desert Warriors directly support the test and evaluation mission of the Air Force Test Center and the 412th Test Wing.

772nd Test Squadron
Benefield Anechoic Facility (BAF - Anechoic Chamber)


### Stratolaunch
https://globe.adsbexchange.com/?icao=a3ea1f
