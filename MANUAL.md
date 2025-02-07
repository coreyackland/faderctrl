# FaderCtrl - User Manual

### Device Firmware Upgrade (DFU) - 
###### `Basic Requirements:` <p>
Getting set up is simple and requires the following - <p>

- TyTools/TyUploader
  - Download [TyTools](https://github.com/Koromix/tytools/releases) via <strong> Releases/Assets </strong> and select your operating system.
  - TyTools is a suite of standalone utilities designed to streamline communication and firmware upgrades, eliminating the need to manually press the onboard button to enter boot mode.
  
- FaderCtrl/Builds
  - Download this repository via <em>'Code > Download ZIP'</em> and direct to the <strong> [Builds/](https://github.com/coreyackland/faderctrl/tree/master/Builds) </strong> folder. See below:-
<img width="907" alt="image" src="https://github.com/user-attachments/assets/eb9a3eac-b6fa-464d-a204-ff462247a9bb" /> <p>
  - This contains both the latest `firmware` image and the `software` application.

###### `Device Update:` <p>
> <em><h5>[Note] Driver installation is not required for either macOS® or Windows® computers.</h5></em>

  - Using the <strong>TyUploader</strong> application, select the connected FaderCtrl from the device drop-down list.
  - To initialise the upload procedure, selected the latest firmware image, select <strong>Upload</strong> and wait until the progress bar is complete.
      - <em> If the uploader shows a red warning, please ignore.</em>

### Application Use: <h6>(Release 1.0.0)</h6> <p> 
> <em><h5>[Note] macOS® users may be required to right-click 'Open' on initial startup.</h5></em>



  - Select the connected <strong>FaderCtrl</strong> from the device drop-down list.
  - Assign a <strong>MIDI CC</strong> for each fader by moving the corresponding application sliders. Far left slider correlates to far left hardare fader. 
  - Select `Learn` to enable the assignment of a <strong>MIDI CC</strong> via the hardware fader.
  - To store these values on device, select `Store`.

