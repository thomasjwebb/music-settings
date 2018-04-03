# Music Settings

Settings for my hardware, etc.

## Arturia Beatstep

The `arturia-beatstep` directory has the settings I use in MIDI Control Center to program my beatstep. I set it up in this order in the memory banks (all with c as root note):

1. split-ionian-cmaj-i
2. split-aeolian-cmin-vi
3. split-dorian-ii
4. split-phrygian-iii
5. split-lydian-iv
6. split-mixolydian-v
7. split-locrian-vii
8. roland
9. gm

The split ones are left half drums based on bitwig's drum mapping, right half the notes of the scale:

| hi-tom  | mid-tom | low-tom | crash   | II       | IV      | VI      | VII     |
|---------|---------|---------|---------|----------|---------|---------|---------|
| bass    | snare   | cld hh  | open hh | I        | III     | V       | VI      |

The notes are on channel 2, the drums are on channel 1. These are best used with [my modified beatstep controller script](https://github.com/thomasjwebb/Bitwig-ArturiaBeatstep) to allow each channel its own input.

Roland is on channel 10 per Roland's weirdness and its GM mappings, with the last 3 columns unused (gm is same but channel 1):

| hi-tom  | mid-tom | low-tom | crash   | crash 2  |
|---------|---------|---------|---------|----------|
| bass    | snare   | cld hh  | open hh | ride cym |

## Bitwig Projects

Trying to come up with the best starting points to make it easy based on my Arturia beatstep + APC Keys 25 setup and share it with anyone else.

Update from local settings with:

    cp -R ~/Documents/Bitwig\ Studio/Library/Templates/beatstep-project.bwtemplate bitwig-templates/

