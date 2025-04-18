# FaderCtrl - User Manual

### Device Firmware Upgrade (DFU) - 
###### `Basic Requirements:` <p>
Getting set up is simple and requires the following - <p>

- Teensy Programmer
  - Download [TeensyLoader](https://www.pjrc.com/teensy/loader.html) for the latest versions. Alternative, `FaderCtrl/Software/...`</p>
  > <em><h5>[Note] Select the right operating system version.</h5></em>
![image](https://github.com/user-attachments/assets/62e7d813-8579-4267-801d-fb8bd8ed2b95)
![image](https://github.com/user-attachments/assets/1805fb95-5848-43e5-baf9-c6d3a486c5cd)
![image](https://github.com/user-attachments/assets/6d384a51-0bbb-493d-b76d-3bb9e90c1741)

## <h6></h6> <p>
  
- `FaderCtrl/Releases`
  - Head to <strong> [Releases](https://github.com/coreyackland/faderctrl/releases) </strong> to download the latest release. See below:-
    - Each release will contain a package with the latest downloads.
<img width="1225" alt="image" src="https://github.com/user-attachments/assets/a275ab7f-d511-450f-a9dd-0a7beeda829a" />

  

###### `Device Update:` <p>
> <em><h5>[Note] Driver installation is not required for either macOS® or Windows® computers.</h5></em>

  - Using the <strong>TeensyLoader</strong> application, go to <strong>File>Open Hex File</strong> to select the latest hex file located in `../Release/FaderCtrl.hex`
    - Initiate the upload procedure by activating the onboard MCU momentary push button. 
> <em><h5>[Note] For access, one side panel of the enclosure must be removed. The controller plate can slide out for ease of access.</h5></em>
![image](https://github.com/user-attachments/assets/dd780f82-f5ca-457b-ad2f-be4752d10659)

### Application Use: <h6>(Release 1.0.2)</h6> <p> 
2025-04 - CURRENTLY ONLY WORKING ON macOS®

> <em><h5>[Note] macOS® users may be required to right-click 'Open' on initial startup.</h5></em>

<em><h5>[Required] Select the connected <strong>FaderCtrl</strong> from the device drop-down list. </h5></em>
  - Assign a <strong>MIDI CC</strong> for each fader by moving the corresponding application sliders. Far left slider correlates to far left hardare fader. 
  - Select `Learn` to enable the assignment of a <strong>MIDI CC</strong> via the hardware fader.
  - To store these values on device, select `Store`.

