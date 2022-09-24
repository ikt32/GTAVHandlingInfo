# GTAVHandlingInfo

Repository to host files for various tools to use.

## Contributing

Make a pull request for your changes, or make [an issue](https://github.com/E66666666/GTAVHandlingInfo/issues/new).

Increment the version number of the relevant file in your PR, and update this readme with the changelog.

Use tabs to indent.

## `flags.json`

Describes the handling flags and their effects.

Each field of flags has 32 entries, so don't add or remove anything - just edit the strings.

On file version increment, [Real Time Handling Editor](https://www.gta5-mods.com/tools/real-time-handling-editor) updates the local file.

### 1.0

* Initial version, pulled from [Aquaphobics' Discord](https://discord.gg/Vtz9Q6C)

### 1.1

* Update descriptions for `DONT_FORCE_GRND_CLEARANCE` and `DOUBLE_RWHEELS` by GreenAid

### 2.0

* Add official flag names by Wildbrick
* Add more advanced flag research notes by Wildbrick
* Add damage flags by Wildbrick

### 2.1

* Correct `strAdvancedFlags` 0x4 info (enables `fMaxDriveBiasTransfer`) by [Reactors](https://www.gta5-mods.com/users/Reactors)

### 2.2

* Add `strAdvancedFlags` `_AF_CAN_BE_STANCED` from LS Tuners and update `_AF_IGNORE_TUNED_WHEELS_CLIP` by [Wildbrick142](https://github.com/Wildbrick142)

### 2.3

* Update flags `MF_TANDEM_SEATING`, `MF_NO_1STPERSON_LOOKBEHIND`, `HF_SMOOTHED_COMPRESSION`, `HF_HAS_TRACKS` by [alloc8or](https://github.com/alloc8or)

### 2.4

* Add `strAdvancedFlags` `_AF_HAS_SPECIAL_PERFORMANCE_MODS` from The Contract and add advanced flag research notes to `_AF_UNKNOWN_FLAG_1`, `_AF_UNKNOWN_FLAG_4`, `_AF_UNKNOWN_FLAG_11` by [Wildbrick142](https://github.com/Wildbrick142)

### 2.5

* Add all official `strAdvancedFlags` names thanks to the anonymous "100ksource"

## `notes.json`

Describes the handling parameters and their effects.

`description` is one string. This describes what the parameter is, and applicable units. May be an empty string, no additional description is shown.

`extra` is an array of strings. This describes how the parameter works:

* Top: Formula, if applicable.
* Next: Value range/examples.
* Bottom: Advice for choosing a decent value.

`extra` may be omitted, no extra information panel is shown in that case.

### 1.0

* Initial version, with help from Eddlm.
