# FaderCtrl - User Manual

### Device Firmware Upgrade (DFU) - 
###### `Basic Requirements:` <p>
Getting set up is simple and requires the following - <p>

- TyTools/TyUploader
  - Download [TyTools](https://github.com/Koromix/tytools/releases) via <strong> Releases/Assets </strong> and select your operating system.
  - TyTools is a suite of standalone utilities designed to streamline communication and firmware upgrades, eliminating the need to manually press the onboard button to enter boot mode.
  
- FaderCtrl/Builds
  - Download the latest updates via the <strong> [Builds/](https://github.com/coreyackland/faderctrl/tree/master/Builds) </strong>
  - This contains both the latest `firmware` image and the `software` application. 

###### `Device Update:` <p>
> <em><h5>[Note] Driver installation is not required for either macOS® or Windows® computers.</h5></em>

  - Using the <strong>TyUploader</strong> application, select the connected FaderCtrl from the device drop-down list.
  - Initialising the <strong>Upload</strong> procedure, selected the latest firmware image and wait until the progress bar is complete.
      - <em> If the uploader shows a red warning, please ignore.</em>

### Application Use: <h6>(Release 1.0.0)</h6> <p> 
> <em><h5>[Note] macOS® users may be required to right-click 'Open' on initial startup.</h5></em>



  - Select the connected <strong>FaderCtrl</strong> from the device drop-down list.
  - Assign a <strong>MIDI CC</strong> for each fader by moving the corresponding application sliders. Far left slider correlates to far left hardare fader. 
  - Select `Learn` to enable the assignment of a <strong>MIDI CC</strong> via the hardware fader.
  - To store these values on device, select `Store`.

