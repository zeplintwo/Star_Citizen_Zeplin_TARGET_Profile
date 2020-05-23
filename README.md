# Zeplin’s Star Citizen TM Warthog Script Profile for TARGET

This is a build from my flight hardware that I use when playing Star Citizen. It has the Warthog HOTAS and a set of T.Flight Rudder Pedals (TFRP).  It is designed to keep the things that I am used to doing in Elite as close as possible to the same reactions in Star Citizen. The profile that I use in Elite is from Aussiedroid if you are interested search him in google. His profile had inspired my profiles that I create to have the same level of ease of use. But have the depth to be able to do almost all function that you would need in a game with such different ships and jobs that the ships can do.

---

## Hardware
Required hardware:
Thrustmaster (TM) Warthog HOTAS – Throttle and Joystick

Optional hardware:
TM T.Flight Rudder Pedals (TFRP) – in flight mode
NaturePoint TrackIR – IR headset (hat rig not tested and unsure if it will work properly with included settings file.)

Optional Software:
External VoIP - Discord,TS3,Mumble,Skype

---

This script works well in SC and was built in 3.9.0 and should be fine in later patches. 
There are several things that you may want to change from the way I fly. Most of the setting are in the ‘SC_User_Settings-v#.#.ttm’ file. More on that later. 

---

## Features of script:

-Switchable throttle maps ingame 3 presets controlled by ‘flaps’ 6 different profiles in script. 
-Switchable joystick maps ingame 3 presets controlled by ‘Autopilot’ 
-Full lock/unlock & open/close from one button depending on ‘shift’ pinky button.
-Flight assist pulse or lock.
-Flight brakes pulse or lock.
-Chaff/flare toggle with same button launch
-Missile lock and fire from same button. 
-Full six axis thrusting. For and Aft are more of a bump then actual ‘thruster’ like Elite has.
-Three position comms External application, Local Ingame, Global Ingame. Selectble from throttle pinky switch.
-Full power management from joystick
-Full shield control from joystick
-Major target selection direct from joystick
-and more...

---
## Thrustmaster links to TARGET Software

Thrustmaster US website: http://www.thrustmaster.com/en_US
Thrustmaster US support: http://www.thrustmaster.com/en_US/support
Thrustmaster US T.16000m downloads: https://support.thrustmaster.com/en/product/t-16000m-fcs-space-sim-duo-en/
Target software found in download link above under software as of this writing on March 12, 2020 the file name was T.A.R.G.E.T.-Software v3.0.18.328 v2. There is no direct link I can give. The version number will change in the future.

---

## Installation:

   1. Download and extract the latest ‘source’ files. [Releases](https://github.com/zeplintwo/ Star_Citizen_Zeplin_TARGET_Profile/releases)
   2. Unpack zip and keep all files in same directory. 
   3. Open ‘TARGET Script Editor’ Open and Compile ‘Star_Citizen_Zeplin_Profile-v#.#.#.tmc'.
   4. Edit 'SC_User_Settings-v#.#.#.ttm' save changes if any.
   5. Close ‘TARGET Script Editor’ window.
   6. Launch ‘TARGET GUI’ and ‘Run Configuration’ on ' Star_Citizen_Zeplin_Profile-v#.#.#.tmc '. 
      - You can also run the configuration from the Script Editor.
   7. Copy the ‘layout_Zeplin_SC_Binds_exported.xml’ to your (install drive)\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Controls\Mappings. [For more on importing see this link for SC support site.][https://support.robertsspaceindustries.com/hc/en-us/articles/360000183328]
   8. Copy the ‘SCZeplin.xml’ to the TrackIR profile folder at %AppData%\NaturalPoint\TrackIR 5\Profiles. [For more on TrackIR setting here is there 5.3 Manual][https://www.naturalpoint.com/trackir/documents/TrackIR-5.3-Manual.pdf]   
   9. Launch save game and enjoy. 
 
