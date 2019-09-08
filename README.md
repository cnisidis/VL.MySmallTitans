# VL.MySmallTitans

*MySmallTitans is a condensed but not that small collection of different VL and vvvv nodes for mangling with any kind of midi input (**Iapetus**) in order to control image sequence playback (**Crius**) or play with lights (**Hyperion** [upcoming]) and get control of everything with a timeline (**Rhea**) and a simplistic UI (**Phoebe**)* 

## Iapetus

*Midi related toolkit, sync vvvv with your favorite DAW*

**MidiClockToSeconds**
- Convert midiclock to Seconds 

**SecondsToTime**
- Convert seconds to Time Object (for better visualizing purpose)

**MidiDeviceSelect**
- Select the midi port/device you want to get in sync with

**MidiSyncDevice**
- Get the actual Clock and Sysex commands from your Selected Midi Device

**MidiSync**
- Basic implementation of MidiClock (get position song)

**MidiPlayStop**
- Get the midi RealTime commands (play, stop, continue, reset)

**GetMidiInNote**
- Just get the actual playing midi note(s)

**KeyToNote**
- Transcript Key (i.e. C#4) to an integer corresponding on this note

**NoteToKey**
- The other way around of KeyToNote

**MidiSyncImagePlayer**
- Load and play sequences in sync with your DAW


## Crius

*Name your decks, load your tracks and CUE them*

**Playlist**
- load the tracks and set the apropriate deck for each one

**Decks**
- Name your Decks and load you Playlist

**Track**
- The actual track of you playlist 


## Phoebe

(WIP)
*Simplistic UI to rule over the small titans*


more to come...

## Hyperion
*Artnet/DMX Based on VL.Fixtures*

## Rhea
*Timeline visualizer Based on Hanlder







