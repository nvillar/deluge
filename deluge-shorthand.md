# DELUGE SHORTHAND 0.1

## NOTATION

### ACTIONS

**Actions** on button and knob controls are represented by different types of brackets surrounding the control name:

|                                                 |                 | 
| ----------------------------------------------- | --------------- |
| **Square** brackets for *press and release*     | **[ CONTROL ]** |
| **Angled** brackets for *press and hold*        | **< CONTROL >** |
| **Rounded** brackets for *turn*                 | **( CONTROL )** |
| **Curly** brackets for *press, hold and turn    | **{ CONTROL }**  

Actions can be nested to represent order of operations. For example creating a new a song: press and hold SHIFT, press LOAD, release shift, then press LOAD, is written as:

**\<SHIFT [*NEW*]> [*NEW*]**

### CONTROLS

**Control knobs** are referred to as: **VSCROLL**, **HSCROLL**, **UPPER**, **LOWER**, **SELECT**, **TEMPO** and **VOLUME**

**Buttons** are referred to by their label. If referring to a 'shifted' label they are written in italics, e.g. **SAVE** and ***DELETE***

**Grid buttons** are referred to as **X**. A specific grid button can be referred to by a XY coordinate, with **X1Y1** being the top left, e.g. **X1Y3** is the button labelled ***BROWSE***

**Mute / Launch buttons** are referred as **M**. 

**Audition / Section buttons** are referred to as **A**.

---
## Global Controls

|                                           |                                                           | 
| ----------------------------------------- | --------------------------------------------------------- |
| View and change zoom level                | \<HSCROLL> {HSCROLL}                                      |
| Scroll grid up/down and left/right        | (VSCROLL) (HSCROLL)                                       |                     
| New song                                  | \<SHIFT [*NEW*]> [*NEW*]                                  |
| Delete song                               | [LOAD] (SELECT) \<SHIFT [*DELETE*]> [*DELETE*]            |
| Load song                                 | [LOAD] (SELECT) [LOAD]                                    |
| Load song keeping current tempo           | [LOAD] (SELECT) [TEMPO] [LOAD]                            |
