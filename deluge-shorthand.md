# DELUGE SHORTHAND 1.0

## GLOBAL CONTROLS

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| View / change zoom level                                | [HSCROLL] / {HSCROLL}                             |
| Scroll grid up-down / left-right                        | (VSCROLL/HSCROLL)                                 |
| New song                                                | [SHIFT [*NEW*]] [*NEW*]                           |
| Delete song                                             | [LOAD] (SELECT) [SHIFT [*DELETE*]] [*DELETE*]     |
| Load song                                               | [LOAD] (SELECT) [LOAD]                            |
| Load song keeping current tempo                         | [LOAD] (SELECT) [TEMPO] [LOAD]                    |
| Load song delaying change                               | [LOAD] (SELECT)                                   |
| Fast scroll song list                                   | [LOAD] [SHIFT (SELECT)]                           |
| QWERTY search in song loading mode                      | [PAD]                                             |
| Save song                                               | [SAVE] (SELECT) [SELECT]                          |
| Save song collecting samples                            | [SAVE] (SELECT) \<SELECT> [SELECT]                |
| Change tempo coarse / fine                              | (TEMPO) / {TEMPO}                                 |
| Metronome                                               | [SHIFT [TAP TEMPO]]                               |
| Swing                                                   | [SHIFT (TEMPO)]                                   |
| Adjust brightness                                       | [SHIFT [LEARN] (VSCROLL)]                         |
| Firmware update                                         | [SHIFT [POWER ON]]                                |
| Settings menu                                           | [SHIFT [SELECT]]                                  |
| Open sound editor                                       | [SELECT] (HSCROLL)                                |
| Change LED refresh rate                                 | [CLIP] (SELECT)                                   |
| Resample                                                | [SHIFT [RECORD]]                                  |
| Loop resample                                           | [RECORD [PLAY]] .. [RECORD [PLAY]]                |

<div class="page"/> 

## CLIP VIEW

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Long notes                                              | [Note start PAD [Note end PAD]]                   |
| Long notes across screens                               | [PAD] (HSCROLL) [HSCROLL [PAD]]                   |
| Adjust note velocity                                    | [PAD (HSCROLL)]                                   |
| Set note probability                                    | [PAD (SELECT)]                                    |
| Copy all note columns at current zoom                   | [LEARN [HSCROLL]]                                 |
| Paste all note coluns into current zoom                 | [SHIFT [LEARN [HSCROLL]]]                         |
| Adjust note velocity                                    | [PAD (HSCROLL)]                                   |
| Duplicate clip                                          | [SHIFT [HSCROLL]]                                 |
| Set clip length                                         | [SHIFT (HSCROLL)]                                 |
| Shift clips left/right                                  | [VSCROLL (HSCROLL)]                               |
| Clear all clip notes                                    | [HSCROLL [BACK/UNDO]]                             |
| Note zoom level to 128th and 256th                      | [LEARN (TEMPO)]                                   |
| Live record notes into sequencer                        | [PLAY] [RECORD] [AUDITION/PAD/KEYBOARD]           |
| Change clip color                                       | [SHIFT (VSCROLL)]                                 |
| Change row color                                        | [SHIFT [AUDITION (VSCROLL)]]                      |
| Nudge note                                              | [PAD {HSCROLL}]                                   |
| Repeat note                                             | [PAD {VSCROLL}]                                   |
| Transponse note                                         | [PAD (VSCROLL)]                                   |
| Change octave                                           | {VSCROLL}                                         |
| Record automation                                       | [RECORD (UPPER/LOWER)]                            |
| Erase automation                                        | [SHIFT [UPPER/LOWER]]                             |
| Copy automation                                         | [LEARN [UPPER/LOWER]]                             |
| Paste automation                                        | [SHIFT [LEARN [UPPER/LOWER]]]                     |
| Per-note parameter lock                                 | [PAD (UPPER/LOWER)]                               |

<div class="page"/> 

## SYNTH, MIDI, CV CLIPS

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Cycle default scales                                    | [SHIFT [SCALE]]                                   |
| Change root note of current scale                       | [SCALE [AUDITION of new root note]                |
| Alter current scale                                     | [AUDITION {SELECT}]                               |
| Clone current synth or clit preset                      | [LOAD [SELECT]                                    |
| Transpose clip by octave                                | {VSCROLL}                                         |
| Transpose clip by semitone (SCALE must be off)          | [SHIFT {VSCROLL}]                                 |

## SYNTH CLIPS

| Action                                                  | Sequence                                           |
| ------------------------------------------------------- | -------------------------------------------------- |
| New init synth                                          | [SHIFT [SYNTH]]                                    |
| Load single cycle sample                                | [SHIFT [*BROWSE*]] [SELECT] (SELECT) [SELECT] [BACK]|
| Load long (basic) or multi samples                      | [SHIFT [*BROWSE*]] [SELECT] (SELECT) \<SELECT> (SELECT) [SELECT] [BACK]|
| Save synth as new preset                                | [SAVE [SYNTH]] (SELECT) [SELECT]                   |
| Synth resample                                          | [RECORD [AUDITION]]                                |

## KIT CLIPS

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| New init kit                                            | [SHIFT [KIT]]                                     |
| Save kit as new preset                                  | [SAVE [KIT]] (SELECT) [SELECT]                    |
| Move kit clip row up/down                               | [AUDITION {VSCROLL}]                              |
| Add instrument into a blank kit row                     | [AUDITION [KIT]] (SELECT) [SELECT]                |
| Start/stop recording sample from input into kit         | [AUDITION [RECORD]] / [RECORD]                    |
| Slice a pre-recorded sample into kit                    | [SHIFT [KIT]] (SELECT) [SHIFT [SELECT]]           |

<div class="page"/> 

## AUDIO CLIPS

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Create new audio clip in song view                      | [PAD [SELECT]]                                    |
| Create new audio clip in arranger view                  | [AUDITION [SELECT]]                               |
| Clear audio recording in clip view                      | [HSCROLL [BACK/UNDO]]                             |
| Change wave color in clip view                          | [SHIFT (VSCROLL)]                                 |
| Set audio clip end point / loop length                  | [End PAD] [PAD]                                   |
| Adjust audio clip length (audio will stretch)           | [SHIFT (HSCROLL)]                                 |
| Grab audio tempo to avoid time stretching               | [TEMPO [PAD]]                                     |

## WAVEFORM EDITOR

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Enter waveform file editor in audio clip view           | [SHIFT [*WAVEFORM* PAD 1,1]]                      |
| Change start/end points of sample                       | [Green/Red PAD] [PAD]                             |
| Set loop start point                                    | [Green PAD [PAD to the right]]                    |
| Set loop end point                                      | [Red PAD [PAD to the left]]                       |
| Change loop start/end point                             | [Blue/Purple PAD] [PAD]                           |
| Delete loop points at start/end                         | [Blue PAD [Green PAD]] / [Purple PAD [Red PAD]]   | 

## RECORDING AUDIO IN SONG OR ARRANGER VIEWS

| Action                                                   | Notation                                          |
| -------------------------------------------------------- | ------------------------------------------------- |
| Set input source in song view                            | [LEARN/INPUT [PAD]] (SELECT) [SELECT]             |
| Set input source in arranger view                        | [LEARN/INPUT [AUDITION]] (SELECT) [SELECT]        |
| Check armed clips                                        | \<RECORD>                                         |
| Arm clip (blink red = solo rec, blink purple = multi rec)| [RECORD [MUTE/LAUNCH]]                            |
| Enable metronome to lock-in clip timing to song BPM      | [SHIFT [TAP TEMPO]]                               |
| Start recording                                          | [RECORD] [PLAY]                                   |
| Stop recording                                           | [MUTE/LAUNCH]                                     |
| Enable count-in                                          | [SHIFT [SELECT]]                                  |

<div class="page"/> 

## SONG VIEW

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Queue clip launch / stop                                | [MUTE]                                            |
| Instant launch / stop clip                              | [SHIFT [MUTE]]                                    |
| Enter clip or create new on blank row                   | [PAD]                                             |
| Move clip row                                           | [PAD (VSCROLL)]                                   |
| Change clip section color                               | [SHIFT [AUDITION]]                                |
| Queue section launch section                            | [AUDITION]                                        |
| Section repeat                                          | \<AUDITION> (SELECT)                              |
| Cancel section repeat during countodwn                  | (SELECT)                                          |
| Clone clip from source to destination row               | [PAD [PAD]]                                       |
| Delete clip                                             | [PAD [*DELETE*]]                                  |
| Queue solo clip                                         | [HSCROLL [MUTE]]                                  |
| Instant solo clip                                       | [SHIFT [HSCROLL [MUTE]]]                          |
| Clip parameter change                                   | [PAD (UPPER/LOWER)]                               |
| Song parameter change                                   | [AFFECT ENTIRE] (UPPER/LOWER)                     |
| Change clip preset                                      | [PAD (SELECT)]                                    |
| Change clip type                                        | [PAD [SYNTH/MIDI/CV/SELECT]]                      |
| Check clip name                                         | \<PAD>                                            |
| Record to arranger at play bar position / stop recording| [RECORD [SONG]] / [RECORD]                        |

## LOOPING IN SONG VIEW

| Action                                                   | Notation                                          |
| -------------------------------------------------------- | ------------------------------------------------- |
| Overdub layers                                           | [PLAY] [RECORD [PAD below existing clip]]         |
| Continous overdub layers                                 | [PLAY] [RECORD [AUDITION below existing clip]]    |
| Close loop recording                                     | [MUTE]                                            |
| Close loop recording and solo                            | [HSCROLL [MUTE]]                                  |
| Cancel overdub clip                                      | [PAD] or [AUDITION]                               |

<div class="page"/> 

## ARRANGER VIEW

| Action                                                  | Sequence                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Move play bar position                                  | (HSCROLL)                                         |
| Add clip into arranger                                  | [PAD]                                             |
| Change clip instance                                    | [PAD (SELECT)]                                    |
| Delete clip instance                                    | [Clip start PAD]                                  |
| Delete row from arranger                                | [AUDITION [DELETE]]                               |
| Change clip instance length                             | [Clip start PAD [New clip end PAD]]               |
| Enter clip                                              | [TAIL PAD]                                        |
| Move clip instance horizontally                         | [PAD (HSCROLL)]                                   |
| Move row vertically                                     | [AUDITION (VSCROLL)]                              |
| Clear all clip instances                                | [HSCROLL [BACK/UNDO]]                             |
| Mute / unmute instrumet                                 | [MUTE]                                            |
| Audition instrument                                     | [AUDITION]                                        |
| Solo instrument                                         | [HSCROLL [MUTE]]                                  |
| Auto scroll timeline while playing                      | [CROSS SCREEN]                                    |
| Start playback from current screen                      | [HSCROLL [PLAY]]                                  |
| Make clip unique (white)                                | [SHIFT [Start PAD]]                               |
| Copy clip between arranger and song views               | [PAD [SONG]]                                      |
| Adjust clip parameter                                   | [PAD (UPPPER/LOWER)]                              |
| Adjust playback time                                    | [SHIFT (HSCROLL)]                                 |
| Rename track                                            | [AUDITION [*NAME* PAD 3,5]]                       |

<div class="page"/> 

## MIDI

| Action                                                  | Sequence                                                         |
| ------------------------------------------------------- | ---------------------------------------------------------------- |
| Select MIDI channel in MIDI clip                        | (SELECT)                                                         |
| Set MIDI CC for param knobs in MIDI clip                | [UPPER/LOWER (SELECT)]                                           |
| Change CC keeping automation in MIDI clip               | [UPPER/LOWER {SELECT}]                                           |
| Enable MIDI note output for a kit clip row              | [AUDITION [MIDI]]                                                |
| Set MIDI channel / note for a MIDI kit clip row         | [AUDITION (LOWER/UPPER)]                                         |
| Map external controller to synth or kit notes           | [LEARN [AUDITION] [External controller]]                         |
| Map external controller to trigger button               | [LEARN [MUTE/RECORD/PLAY...] [External controller]]              |
| Unmap external controller from trigger                  | [SHIFT [LEARN [MUTE/RECORD/PLAY...]]]                            |
| Map external controller to Deluge parameter             | [SHIFT [Param PAD]] [LEARN [External controller]]                |
| Unmap external controller from Deluge parameter         | [SHIFT [Param PAD]] [SHIFT [LEARN]]                              |

<div class="page"/> 

---
## NOTATION FOR ACTIONS

**Actions** on button and knob controls are represented by different types of brackets around the control name:

| Action                                          | Notation        |
| ----------------------------------------------- | --------------- |
| **Square** brackets for *press*                 | **[CONTROL]**   |
| **Angled** brackets for *long press*            | **\<CONTROL>**  |
| **Rounded** brackets for *turn*                 | **(CONTROL)**   |
| **Curly** brackets for *turn while pressing*    | **{CONTROL}**   |

Actions can be *nested* to represent order of operations. For example creating a new a song - press and hold SHIFT, press *NEW*, release shift, then press *NEW* - is written as: 

**[SHIFT [*NEW*]] [*NEW*]** 

---

## NOTATION FOR CONTROLS

* **Control buttons** are referred to by their label. If referring to a 'shifted' label they are written in italics, e.g. **SAVE** and ***DELETE***.

* **Control knobs** are referred to as: **VSCROLL**, **HSCROLL**, **UPPER**, **LOWER**, **SELECT**/***SETTINGS***, **TEMPO**/***SWING*** and **OUTPUT LEVEL**.

* **Grid pads** are generically referred to as **PAD**. A specific pad can also be referred to by its label, e.g. ***BROWSE***. An unlabelled pad can be referred to by a XY coordinate, with **1,1** being the top left, e.g. **PAD 1,3**. Pads can also be described by their color or position, such as **Note start PAD**,  or **Green PAD**. 

* **Mute / Launch pads** are referred as **MUTE**. A specific mute pad can be referred to by a number, with top being 1, e.g. **MUTE 1**.

* **Audition / Section pads** are referred to as **AUDITION**. A specific audition can be referred to by a number, with top being 1, e.g. **AUDITION 1**.

---

## CHANGELOG

| Version | Changes                                 |
| ------- | --------------------------------------- |
| 1.0     | Initial release for firmware version 3.1| 

Latest version can be found at **github.com/nvillar/deluge**
