# FaderCtrl - Firmware & Software Updates

FaderCtrl V1 (2017) - Product support. <p>
<strong> Refer to [MANUAL.md](MANUAL.md) for instructions. </strong>

### Legend - 
> ###### `FIX:` A bug fix.  Relevant to users and developers.
> ###### `NEW:` A new feature. Relevant to users and developers.
> ###### `SYS:` A system-level change.  Usually only relevant to developers.

### Semantic Versioning - 
> ###### `MAJOR: 1.x.x` Addresses incompatible API changes.
> ###### `MINOR: x.1.x` Addresses functionality in a backward compatible manner.
> ###### `PATCH: x.x.1` Addresses backward compatible bug fixes.
</p>

<h6><em>A firmware update is required to ensure compatibility with the software functionality listed below.</em></h6>

#### `1.0.2` -
- `SYS:` MIDI Exclusions - Ignored MIDI Active Sense (0xFE) and MIDI Clock (0xF8).

#### `1.0.1` -
- `FIX:` Device Selector - Restricted interaction when no device is selected.
- `FIX:` MIDI Learn - Resolved duplicate channel movements when faders share the same CC number (e.g., zero).
- `SYS:` SysEx Handler - Enhanced bi-directional communication between the hardware and software interface.

#### `1.0.0` -
- `NEW:` MIDI Learn - Enables the user to assign a control change [CC] from the device per fader.
- `NEW:` Device Selector - Enables the user to select a midi device to update its control change parameters.
