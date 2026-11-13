# LocalDot

LocalDot is an open-source replacement board for the 3rd-generation Echo Dot. It keeps the original enclosure, four-microphone array, speaker, buttons, and LED ring, while connecting the device to Home Assistant without requiring Amazon's servers.

<p align="center"><img src="Images/v2-assembled.jpg" alt="LocalDot revision 2.0 installed with the original speaker" width="440"></p>

*LocalDot revision 2.0 with the original speaker.*

## Why LocalDot?

An Echo Dot with working hardware can have a second life as a local voice assistant. LocalDot replaces the mainboard without modifying the enclosure, while leaving the familiar microphone array, speaker, controls, and lights in place.

## Hardware at a glance

- Designed for the 3rd-generation Echo Dot enclosure and original components
- Four microphones, with audio processing on an ESP32-P4
- ESP32-S3 for connectivity and device control
- Integration with Home Assistant for local voice-assistant features




## Revision 2.0 photos

<p align="center"><img src="Images/v2-front.jpg" alt="Front of the LocalDot revision 2.0 PCB" width="340"> <img src="Images/v2-back.jpg" alt="Back of the LocalDot revision 2.0 PCB" width="340"></p>

*Front (left) and back (right) of the revision 2.0 board.*

  The revision 2.0 prototype is shown above. Hardware and firmware are still being developed, and more design files and setup instructions will be published here as they are ready.
  

  ### Development status tracking table

  | HW Revision | V2.0 | V2.1 |
|---|---|---|
| Schematic | ✅ (uploaded)  | ❌ (not uploaded)|
| Kicad project | ✅ (uploaded)  | ❌ (not uploaded)|
| Gerber + BOM | ✅ (not uploaded) | ❌ (not uploaded)|
| 40-pin FPC pinout | ✅ (uploaded) | ✅ (uploaded)|
| 8-pin clock FPC pinout | ❌ (not uploaded) | ✅ (not uploaded)|


### Actual compatibility with different revisions of the Echo Dot 3rd 
  
| HW Revision | Status | Done |
|---|---|---|
| Donut | Compatible  | ✅ |
| Crumpet | Compatible  | ✅ |
| Clock version | Working as standard Dot. Clock not tested | 🟨 |

## Stay updated with the latest news!
- [The Campaign is now live!](https://www.crowdsupply.com/aaelectronics/localdot/updates/our-campaign-is-now-live)
- [Answering some common questions about LocalDot](https://www.crowdsupply.com/aaelectronics/localdot/updates/answering-some-common-questions)


## Follow the project 

- [Crowd Supply](https://www.crowdsupply.com/aaelectronics/localdot)
- [Home Assistant Community discussion](https://community.home-assistant.io/t/re-using-an-echo-dot-3rd-gen-with-voice-assistant/1020256/17)

## FPC connector pinout

<p align="center"><img src="Docs/fpc-pinout.svg" alt="FPC connector pinout table with signal names and descriptions" width="900"></p>
