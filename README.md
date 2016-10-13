# BCMetronome

A metronome class in swift. 

## Installation

Put BCMetronome.swift and .mp3 files in your project. 

## Usage
```
let metronome = BCMetronome()

metronome.bpm = 140

metronome.beatsPerBar = BCBeatsPerBar.four

metronome.beatNote = BCBeatNote.quarter

metronome.start()
```

## Variables

#### beatsPerBar
  - Top value of time signiture
  - Type: BCBeatsPerBar
  - Possible values: (one-sixteen).
  
#### beatNote
  - Bottom value of time signiture
  - Type: BCBeatNote
  - Possible values: (whole, half, quarter, eighth, sixteenth, thiertysecond)

#### bpm
  - Beats Per Minute
  - Type: Int
  
## Functions
  - start() 
  - stop()
  - toggle() 
    - If it is off, start. If it is on, stop()
