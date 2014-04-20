meditationA
===========

Max/MSP/Jitter meditation (#03)

The prompt was an asymptotic equation generator. I created a MIDI sequencer where each note triggers a visual response with a parameterized decay time. Each MIDI note controls the location of a 3D gridshape and will shift it from a sphere to a cube.

I might keep developing this patch to use more interesting sounds and customized shapes that incorporate Paul Bourke's equations as inspiration.

The original meditation's equation generator can be found burried inside of the VISUALS subpatch, in the SHAPE subpatch, as "p decayrAttack". Here, it controls the xfade between the two forms of each gridshape as they morph from shpere to cube.

There are also asymptotic equations to generate the location of each shape, inside of each shape's "p whereareyou" subpatches. These subpatches are inspired by the "drunk donut" example from class.
