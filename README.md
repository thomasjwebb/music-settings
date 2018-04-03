# Music Settings

Settings for my hardware, etc.

## Arturia Beatstep

The `arturia-beatstep` directory has the settings I use in MIDI Control Center to program my beatstep. I set it up in this order in the memory banks:

1. split-ionian-cmaj-i
2. split-aeolian-amin-vi
3. split-dorian-d-ii
4. split-phyrgian-e-iii
5. split-lydian-f-iv
6. split-mixolydian-g-v
7. split-locrian-b-vii
8. roland

The split ones are left half drums based on bitwig's drum mapping, right half the notes of the scale:

| hi-tom  | mid-tom | low-tom | crash   | II       | IV      | VI      | VII     |
| bass    | snare   | cld hh  | open hh | I        | III     | V       | VI      |

The notes are on channel 2, the drums are on channel 1. These are best used with [my modified beatstep controller script](https://github.com/thomasjwebb/BeatstepProController) to allow each channel its own input.

Roland is on channel 10 per Roland's weirdness and its GM mappings, with the last 3 columns unused:

| hi-tom  | mid-tom | low-tom | crash   | crash 2  |
| bass    | snare   | cld hh  | open hh | ride cym |
