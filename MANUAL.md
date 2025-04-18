# FaderCtrl - User Manual

### Device Firmware Upgrade (DFU) - 
###### `Basic Requirements:` <p>
Getting set up is simple and requires the following - <p>

## <h6>(Download either)</h6> <p>

- (1) TyTools/TyUploader
  - Download [TyTools](https://github.com/Koromix/tytools/releases) via <strong> Releases/Assets </strong> and select your operating system.
  - TyTools is a suite of standalone utilities designed to streamline communication and firmware upgrades, eliminating the need to manually press the onboard button to enter boot mode. </p>

- (2) Teensy Programmer
  - Download [TeensyLoader](https://www.pjrc.com/teensy/loader.html) for the latest versions. Alternative, `FaderCtrl/Software/...`</p>
  > <em><h5>[Note] Select the right operating system version.</h5></em>
![image](https://github.com/user-attachments/assets/62e7d813-8579-4267-801d-fb8bd8ed2b95)
![image](https://github.com/user-attachments/assets/1805fb95-5848-43e5-baf9-c6d3a486c5cd)
![image](https://github.com/user-attachments/assets/6d384a51-0bbb-493d-b76d-3bb9e90c1741)

## <h6></h6> <p>
  
- `FaderCtrl/Releases`
  - Download this repository via <em>'Code > Download ZIP'</em> and direct to the <strong> [Releases/](https://github.com/coreyackland/faderctrl/releases) </strong> folder. See below:-
    - This contains both the latest `firmware` image and the `software` application.
<img width="907" alt="image" src="https://github.com/user-attachments/assets/eb9a3eac-b6fa-464d-a204-ff462247a9bb" /> <p>
  

###### `Device Update:` <p>
> <em><h5>[Note] Driver installation is not required for either macOS® or Windows® computers.</h5></em>

  - Using the <strong>(1) TyUploader</strong> application, select the connected FaderCtrl from the device drop-down list.
    - Initiate the upload procedure by selecting the latest firmware image then select <strong>Upload</strong> and wait until the progress bar is complete.
    - <em> If the uploader shows a red warning, please ignore.</em>

  - Using the <strong>(2) TeensyLoader</strong> application, go to <strong>File>Open Hex File</strong> to select the latest hex file located in `../Release/FaderCtrl.hex`
    - Initiate the upload procedure by activating the onboard MCU momentary push button. 
> <em><h5>[Note] For access, one side panel of the enclosure must be removed. The controller plate can slide out for ease of access.</h5></em>
![image](https://github.com/user-attachments/assets/dd780f82-f5ca-457b-ad2f-be4752d10659)

### Application Use: <h6>(Release 1.0.0)</h6> <p> 
> <em><h5>[Note] macOS® users may be required to right-click 'Open' on initial startup.</h5></em>



  - Select the connected <strong>FaderCtrl</strong> from the device drop-down list.
  - Assign a <strong>MIDI CC</strong> for each fader by moving the corresponding application sliders. Far left slider correlates to far left hardare fader. 
  - Select `Learn` to enable the assignment of a <strong>MIDI CC</strong> via the hardware fader.
  - To store these values on device, select `Store`.

