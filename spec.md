# Features

## Intervals for Bass and Guitar

This diagram shows the basic interval which should be rendered.
Features that should be added is a switch which allows intervals to be shown with notes or just notes by themselves.

| :----: | :----: | :----: | :----: | :----: |
|   P12  |   ♭13  |   P13  |   ♯13  |   ♭15  |
|   M9   |   m10  |   M10  |   P11  |   ♯11  |
|   M6   |   m7   |   M7   |   O    |   m9   |
|   M3   |   P4   |   TT   |   P5   |   m6   |
|   M7   |   R    |   m2   |   M2   |   m3   |


## Scales for Bass and Guitar

For a given key, this will list all of the notes and locations of the scale on the bass / guitar.
So, for instance, the scale pattern for the major scale would be:


| :----: | :----: | :----: | :----: | :----: |
|   P12  |        |   P13  |        |   ♭15  |
|   M9   |        |   M10  |   P11  |        |
|   M6   |        |   M7   |   O    |        |
|   M3   |   P4   |        |   P5   |        |
|        |   R    |        |   M2   |        |

This should be able to be switched to a note view. For instance, if we are in the C major scale, that would be:

| :----: | :----: | :----: | :----: | :----: |
|   G    |        |   A    |        |   B    |
|   D    |        |   E    |   F    |        |
|   A    |        |   B    |   C    |        |
|   E    |   F    |        |   G    |        |
|        |   C    |        |   D    |        |


## Arpeggios for Bass and Guitar

For a given chord, this will list all of the notes and locations of the arpeggio on the bass / guitar.
So, for instance, the arpeggio pattern for a major chord with the 7th, that would be:


| :----: | :----: | :----: | :----: | :----: |
|   P5   |        |        |   m7   |        |
|        |        |   M3   |        |        |
|        |   m7   |        |   O    |        |
|   M3   |        |        |   P5   |        |
|        |   R    |        |        |        |

This should be able to be switched to a note view. For instance, if we are in the Cmaj7 arpeggio, that would be:

| :----: | :----: | :----: | :----: | :----: |
|   G    |        |        |   A#   |        |
|        |        |   E    |        |        |
|        |   A#   |        |   C    |        |
|   E    |        |        |   G    |        |
|        |   C    |        |        |        |


## Jazz Chord Scales

It is important to provide the scales and modes from the major scale.
This is the 12 notes in the following scales:

- Ionian
- Dorian
- Phrygian
- Lydian
- Mixolydian
- Aeolian
- Locrian

The each scale should then show the chordal scales as follows with the base chord indicated:

- I
- i
- ii
- iii
- IV
- V
- vi
- dim vii

Where capital roman numberals indicates major scales, lowercase minor scales, and dim lowercase indicates a diminished scale.
