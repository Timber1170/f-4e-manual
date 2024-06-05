![JTAF Logo](../../../JTAF/img/Logo.png)

# **KY-28 Operations Checklist**

- [**KY-28 Operations Checklist**](#ky-28-operations-checklist)
    - [*Equipment Checks*](#equipment-checks)
    - [*Post Launch*](#post-launch)
    - [*After Landing*](#after-landing)

### *Equipment Checks*

| | | Checklist Item | Action |
|-|-| ---------------| -------|
|1.|                           | KY-28 Power| |
|  |  <input type="checkbox">  |a. Power Knob | [OFF](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|  |  <input type="checkbox">  |b. Mode Switch | [P](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|2.|  <input type="checkbox">  | Code Setting | DETERMINE THAT A PROPER CODE HAS BEEN SET BY PERSONNAL QUALIFIED IN VOICE SECURITY EQUIPMENT |
|  |                           ||In DCS and in combination with SRS this is done through the ground crew communication menu in the DCS communications menu |
|3.|  <input type="checkbox">  | UHF Radio | [ON](../../cockpit/wso/left_console/aft_section.md#communication-control-panel) |
|4.|  <input type="checkbox">  | Mode Switch | [P](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|5.|  <input type="checkbox">  | Power Knob | [ON](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|6.|  <input type="checkbox">  | Ground Test | ESTABLISH COMMS |
|  |                           || If a ground test of equipment is desired, establish two-way, plain-text radio communications on the plain-voice radio with a suitable remote station and request and equipment check. (In DCS another player is needed) |
|7.|  <input type="checkbox">  | Mode Switch | [C](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|8.|  <input type="checkbox">  | Alarm Check | OBSERVED |
|  |                           ||**The KY-28 will perform an automatic alarm check when the mode switch is set to C and the power knob is set to ON**|
|                          
||                             ||* The check will continue for about 2 seconds after power is applied. During this time a steady, unbroken 1200Hz tone is heard in the headset |
|  |                           ||* Upon successful completion of the check, the 1200Hz tone is interrupted at a 2.3Hz rate |
|9.|  <input type="checkbox">  | Clear Interupted Tone | [MOMENTARILY POSITION THE MICROPHONE BUTTON TO UHF TO CLEAR THE INTERRUPTED TONE](../../cockpit/wso/left_console/center_section.md#mic-switch) |
|  |                           ||When the microphone button is released, the KY-28 reverts to the standby condition and is ready for either transmission or reception. If the unit fails to pass the alarm check, the steady 1200Hz tone continues and further cipher operation is inhibited.|
|10.|                           | Alarm Check Failure |  |
|   |  <input type="checkbox">  |a. Power Knob | [OFF](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|   |  <input type="checkbox">  |b. Mode Switch | [P](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|   |                           ||Note: If the KY-28 fails the alarm check, the power knob must be set to OFF and the mode switch to P(Plain) to enable conventional UHF communications |
|11.|  <input type="checkbox">  | Transmit Ciphered Messages | [MIC TO UHF, WAIT FOR TONE](../../cockpit/wso/left_console/center_section.md#mic-switch) |
|  |                           ||**To transmit ciphered messages, position the microphine button to UHF and wait until a momentary tone is heard before voice input**|
|  |                           ||* With the power knob set to ON, the momentary tone is delayed 0.5 seconds after pressing the microphone button. During this time, an encryption check is performed and the sync preample is transmitted to receiving stations. |
|  |                           ||* If the encryption check fails, a 1200Hz tone interrupted at a 2.3Hz rate is presented in the headsets and cipher transmission is not possible. If the encryption check succeeds, a momentary tone is heard in the headsets. |
|12.|  <input type="checkbox">  | Cyper Radio Communications | [ESTABLISH AND CHECK](../../cockpit/wso/left_console/center_section.md#mic-switch) |
|  |                           ||**After the momentary tone is heard, establish  two-way cipher radio communications with a cooperating station and check for readability and signal strenght and/or transmit your message**|
|  |                           ||* Upon releasing the microphone button, the KY-28 will return to the standby condition. Simultaneous transmission by two or more stations on the same frequency is not possible and may result in garbled messages or loss of synchronization. |
|13.|  <input type="checkbox">  | Resume Normal Communications (Mode Switch)| [P](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|  |                           ||**Resume normal, non-crypto communications iof desired at anyu time bt setting the mode switch to P(plain) again**|
|14.|  <input type="checkbox">  | In-Flight Checks| THE ABOVE PROCEDURE MAY BE USED TO PERFORM AN IN-FLIGHT CHECK OF THE EQUIPMENT |


### *Post Launch*

| | | Checklist Item | Action |
|-|-| ---------------| -------|
|1.|  <input type="checkbox">  | Equipment Operation | THE SPEECH SEURITY EQUIPMENT SHALL BE OPERATED AS BRIEFED |
|2.|                           | **Warning** | [IF **ZEROIZE** IS PRESSED DURING FLIGHT, CIPHERED COMMUNICATION IS NOT POSSIBLE. THE CODE CAN ONLY BE RESET (OR CHANGED) THROUGH THE GROUND CREW COMMUNICATIONS MENU AFTER LANDING.](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |

### *After Landing*

| | | Checklist Item | Action |
|-|-| ---------------| -------|
|1.|  <input type="checkbox">  | Zeroize | [AS BRIEFED](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |
|2.|  <input type="checkbox">  | Power Knob | [OFF](../../cockpit/wso/right_sub_panel.md#ky-28-controls) |