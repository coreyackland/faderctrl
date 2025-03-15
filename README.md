# FaderCtrl - Firmware & Software Updates

FaderCtrl V1 (2017) - Product support. <p>
<strong> Refer to [MANUAL.md](MANUAL.md) for instructions. </strong>

### Information

| **Type** | **Description**                                             | **Versioning** | **Description**                              |
|----------|-------------------------------------------------------------|----------------|----------------------------------------------|
| `FIX`   | A bug fix. Relevant to users and developers.                | `MAJOR`        | Addresses incompatible API changes.          |
| `NEW`   | A new feature. Relevant to users and developers.            | `MINOR`        | Addresses backward-compatible functionality. |
| `SYS`   | A system-level change. Usually only relevant to developers. | `PATCH`        | Addresses backward-compatible bug fixes.     |

---
### Releases
<em><h6>[`Version`] - Firmware [`FW`]  | Software [`SW`]</h6></em>

> ##### `v1.0.2` - `SW`
> - `SYS` **MIDI Exclusions** - Ignored MIDI Active Sense (0xFE) and MIDI Clock (0xF8).
>
> ##### `v1.0.1` - `FW` | `SW`
> - `FIX` **MIDI Learn** - Resolved duplicate channel movements when faders share the same CC number (e.g., zero).
> - `FIX` **Device Selector** - Restricted user interface functionality when no device has been selected.
> - `SYS` **SysEx Handler** - Enhanced bi-directional communication between the hardware and software interface.
>
> ##### `v1.0.0` - `FW` | `SW`
> - `NEW` **MIDI Learn** - Enables the user to assign a control change [CC] from the device per fader.
> - `NEW` **Device Selector** - Enables the user to target a FaderCtrl device to update its control change parameters.

### Roadmap

<em><h6>Development: A description of desirable or currently in-progress features. </h6></em>
