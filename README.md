# toners
Tone presets.

## file name format
`{rig-title}.{preset-category}.[position-pickup].[control-setting].{instrument}.{file-extension}`

- A {curly-brace} block represents text that occurs once in the file name.
- A [square-bracket] block represents a hash of zero, one or more related identifiers `key-value` style.
- No spaces in file names. Use hyphens instead of spaces for text within file name blocks.
- Use dots to chain blocks together, and to chain together `key-value` items within a [square-bracket] block.

### {rig-title}
Name of a song, signal chain, whatever helps identify the desierd set of tones.

### {preset-category}
Name of artist, performance venue, whatever helps differentiate the desired tones from others that share the same `rig-title`.

### [position-pickup]
One or more optional `key-value` pairs where `key` represents a pickup position and `value` represents a pickup model or flavor. Do not include pickup/position pairs that are not intended to be used with the preset.

#### Examples:
- `neck-490r` - Gibson 490R pickup in the neck position.
- `tail-490t` - Gibson 490T in the bridge position.

### [control-setting]
One or more optional `key-value` pairs where `key` represents a multi-position control (such as a pickup selector switch, push/pull knob, etc) and `value` represents its setting. Do not include control/setting pairs that are not intended to be used with the preset.

#### Examples:
- `switch-middle` - Pickup selector switch in the middle position.
- `tail-coiltap` - Bridge humbucker coils to be configured as coil tap.
