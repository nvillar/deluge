# DELUGE SHORTHAND 0.1

A compact way to represent Synthstrom Deluge command sequences in text, based on the Deluge Guidebook, the Community Guide, and additional tips from the Deluge community.

Latest version can be found at: https://github.com/nvillar/deluge/

---

## NOTATION FOR ACTIONS

**Actions** on button and knob controls are represented by different types of brackets around the control name:

| Action                                          | Notation        |
| ----------------------------------------------- | --------------- |
| **Square** brackets for *press*                 | **[CONTROL]** |
| **Angled** brackets for *long press*            | **\<CONTROL>** |
| **Rounded** brackets for *turn*                 | **(CONTROL)** |
| **Curly** brackets for *turn while pressing*    | **{CONTROL}** | 

Actions can be *nested* to represent order of operations. For example creating a new a song - press and hold SHIFT, press *NEW*, release shift, then press *NEW* - is written as: 

**[SHIFT [*NEW*]] [*NEW*]** 

---

## NOTATION FOR CONTROLS

* **Control buttons** are referred to by their label. If referring to a 'shifted' label they are written in italics, e.g. **SAVE** and ***DELETE***.

* **Control knobs** are referred to as: **VSCROLL**, **HSCROLL**, **UPPER**, **LOWER**, **SELECT**/***SETTINGS***, **TEMPO**/***SWING*** and **OUTPUT LEVEL**.

* **Grid pads** are generically referred to as **PAD**. A specific pad can also be referred to by its label, e.g. ***BROWSE***. Additionally, a specific pad can be referred to by a XY coordinate, with **1,1** being the top left, e.g. ***BROWSE*** **PAD 1,3**. When referring to long notes or clips, **START PAD**, **END PAD**, and  **TAIL PAD** (the dimly lit pads following the start pad and including the end pad) are used.

* **Mute / Launch pads** are referred as **MUTE**. A specific mute pad can be referred to by a number, with top being 1, e.g. **MUTE 1**.

* **Audition / Section pads** are referred to as **AUDITION**. A specific audition can be referred to by a number, with top being 1, e.g. **AUDITION 1**.

---

## GLOBAL CONTROLS

| Action                                                  | Notation                                          |
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
| Adjust brighness                                        | [SHIFT [LEARN] (TURN)]                            |
| Firmware update                                         | [SHIFT [POWER ON]]                                |
| Settings menu                                           | [SHIFT [SELECT]]                                  |
| Open sound editor                                       | [SELECT] (HSCROLL)                                |
| Change LED refresh rate                                 | [CLIP] (SELECT)                                   |

## CLIP VIEW

| Action                                                  | Notation                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Long notes                                              | [START PAD [END PAD]]                             |
| Long notes across screens                               | [PAD] (HSCROLL) [HSCROLL [PAD]]                   |
| Adjust note velocity                                    | [PAD (HSCROLL)]                                   |
| Set note probability                                    | [PAD (SELECT)]                                    |
| Copy all note columns at current zoom                   | [LEARN/INPUT [HSCROLL]]                           |
| Paste all note coluns into current zoom                 | [SHIFT [LEARN/INPUT [HSCROLL]]]                   |
| Adjust note velocity                                    | [PAD (HSCROLL)]                                   |
| Duplicate clip                                          | [SHIFT [HSCROLL]]                                 |
| Set clip length                                         | [SHIFT (HSCROLL)]                                 |
| Shift clips left/right                                  | [VSCROLL (HSCROLL)]                               |
| Clear all clip notes                                    | [HSCROLL [BACK/UNDO]]                             |
| Add instrument into a blank kit row                     | [AUDITION [KIT]] (SELECT) [SELECT]                |
| Note zoom level to 128th and 256th                      | [LEARN/INPUT (TEMPO)]                             |
| Live record into sequencer                              | [PLAY] [RECORD] [AUDITION/KEYBOARD/PAD]           |
| Change clip color                                       | [SHIFT (VSCROLL)]                                 |
| Change row color                                        | [SHIFT [AUDITION (VSCROLL)]]                      |
| Move kit clip row up/down                               | [AUDITION {VSCROLL}]                              |
| Nudge note                                              | [PAD {HSCROLL}]                                   |
| Repeat note                                             | [PAD {VSCROLL}]                                   |
| Transponse note                                         | [PAD (VSCROLL)]                                   |
| Change octave                                           | {VSCROLL}                                         |
| Record automation                                       | [RECORD (UPPER/LOWER)]                            |
| Erase automation                                        | [SHIFT [UPPER/LOWER]]                             |
| Per-note parameter lock                                 | [PAD (UPPER/LOWER)]                               |

## SONG VIEW

| Action                                                  | Notation                                          |
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



## AUDIO CLIPS

| Action                                                  | Notation                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Create new audio clip in song view                      | [PAD [SELECT]]                                    |
| Set input source in song view                           | [LEARN/INPUT [PAD]] (SELECT) [SELECT]             |
| Create new audio clip in arranger view                  | [AUDITION [SELECT]]                               |
| Set input source in arranger view                       | [LEARN/INPUT [AUDITION]] (SELECT) [SELECT]        |
| Clear audio recording in clip view                      | [HSCROLL [BACK/UNDO]]                             |
| Change wave color in clip view                          | [SHIFT (VSCROLL)]                                 |
| Set audio clip end point / loop length                  | [END PAD] [PAD]                                   |
| Adjust audio clip length                                | [SHIFT (HSCROLL)]                                 |
| Enter waveform editor in audio clip view                | [SHIFT [*WAVEFORM* PAD 1,1]]                      |
| Grab audio tempo to avoid time stretching               | [TEMPO [PAD]]                                     |

## LOOPER IN SONG VIEW

| Action                                                  | Notation                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Check armed clips                                       | \<RECORD>                                         |
| Change arming (red = record, magenta = record multiple) | [RECORD [MUTE/LAUNCH]]                            |

## ARRANGER VIEW

| Action                                                  | Notation                                          |
| ------------------------------------------------------- | ------------------------------------------------- |
| Add clip into arranger                                  | [PAD]                                             |
| Change clip instance                                    | [PAD (SELECT)]                                    |
| Delete clip instance                                    | [START PAD]                                       |
| Change clip instance length                             | [START PAD [END PAD]]                             |
| Enter clip                                              | [TAIL PAD]                                        |
| Move clip instance horizontally                         | [PAD (HSCROLL)]                                   |
| Move row vertically                                     | [AUDITION (VSCROLL)]                              |
| Clear all clip instances                                | [HSCROLL [BACK/UNDO]]                             |
| Mute / unmute instrumet                                 | [MUTE]                                            |
| Audition instrument                                     | [AUDITION]                                        |
| Solo instrument                                         | [HSCROLL [MUTE]]                                  |
| Auto scroll timeline while playing                      | [CROSS SCREEN]                                    |
| Start playback from current screen                      | [HSCROLL [PLAY]]                                  |
| Make clip unique (white)                                | [SHIFT [START PAD]]                               |
| Copy clip between arranger and song views               | [PAD [SONG]]                                      |
| Adjust clip parameter                                   | [PAD (UPPPER/LOWER)]                              |
| Adjust playback time                                    | [SHIFT (HSCROLL)]                                 |




## SOUND DESIGN
