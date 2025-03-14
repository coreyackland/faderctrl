# FaderCtrl - Firmware & Software Updates

FaderCtrl V1 (2017) - Product support. <p>
<strong> Refer to [MANUAL.md](MANUAL.md) for instructions. </strong>

### Versioning Information

| **Legend** | **Description**                           | **Semantic** | **Description** |
|------------|-------------------------------------------|-------------------------|-----------------|
| `FIX:`     | A bug fix. Relevant to users and developers. | **MAJOR**            | Addresses incompatible API changes. |
| `NEW:`     | A new feature. Relevant to users and developers. | **MINOR**           | Addresses functionality in a backward-compatible manner. |
| `SYS:`     | A system-level change. Usually only relevant to developers. | **PATCH**   | Addresses backward-compatible bug fixes. |

### Releases

*Firmware update required to ensure compatibility with the software functionality listed below.*

#### `v1.0.2`
- `SYS:` MIDI Exclusions - Ignored MIDI Active Sense (0xFE) and MIDI Clock (0xF8).

#### `v1.0.1`
- `FIX:` Device Selector - Restricted interaction when no device is selected.
- `FIX:` MIDI Learn - Resolved duplicate channel movements when faders share the same CC number (e.g., zero).
- `SYS:` SysEx Handler - Enhanced bi-directional communication between the hardware and software interface.

#### `v1.0.0`
- `NEW:` MIDI Learn - Enables the user to assign a control change [CC] from the device per fader.
- `NEW:` Device Selector - Enables the user to select a MIDI device to update its control change parameters.
