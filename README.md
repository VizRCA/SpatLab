# SpatLab
Speaker setup files and guides for how to run the system

## Quickstart

1. Switch on the three PDU power blocks at the wall sockets
2. Switch on PDU 3, powers computer and MOTU audio interface
3. Switch on MOTU audio interface
4. Power up the computer or connect to the MOTU using Ethernet, USB or Thunderbolt
5. Start up MOTU Discovery and make sure audio card is working
6. If required, open up Rapture 3D advanced and make sure the correct speaker layout is chosen and audio channels are linked up
7. Open GLM software on computer, make sure volume if -120dB before switching on speakers!
8. Switch on PDU 1 & 2, this turns on all the speakers
9. Open your choice of audio playback system and turn up the volume knob.

## System Specification
16.1 channel spatial audio system with:

+ 4 height speakers - Genelec 8330A SAM Studio Monitor
+ 8 lateral speakers - Genelec 8330A SAM Studio Monitor
+ 4 ground speakers - Genelec 8330A SAM Studio Monitor
+ 1 subwoofer - Genelec 7350A Smart Active Subwoofer

All speakers are controlled using the Genelec Speaker management system GLM 3.0. All speakers are mounted on a scaffold rig with specific speaker alignments.

3 Rackmounted PDUs supply all power; these, in turn, plug into separate wall sockets.

Audio output from the computer is managed through a MOTU 112D AVB Audio interface.

## Spatial Audio Rendering

Currently three softwares are configured for Spatial Audio Rendering:

+ Reaper, using Blue Ripple Rapture 3D Advanced ambisonic decoder
+ Max/MSP, using IRCAM's Spat plugin suite, allowing a variety of rendering options.
+ Rapture 3D - Ambisonic Player, Standalone Ambisonic file playback using

In the future, this list will include SuperCollider and Ableton Live 10.

## Virtual Reality Mixing
The following systems can be used to generate and experience Spatial Audio in VR

+ DearVR Spatial Connect (purchase TBC) using Reaper as the DAW to host DearVR Pro plugin using Rapture 3D Advanced as the ambisonic decoder.
