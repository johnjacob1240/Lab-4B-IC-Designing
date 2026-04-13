<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

My integrated circuit design is a JK Flip Flop which takes in two inputs and a clock signal, and the based on the inputs and if the clock is on, the state of the circuit will change. If J's state is one then the circuits state is one, but if K's state is one then the curcuits state will be reset to zero. if both are pressed then the curcuit will toggle between the two, but if the clock's state isn't one, then nothing will change about the clocks state 

## How to test

set the inputs and check the outputs match with the expected results:

| J and K | output Q (next) | output Q̄ (next) | operation |
|---------|-----------------|-----------------|-----------|
| 0 0     | Q               | Q̄               | Hold      |
| 0 1     | 0               | 1               | Reset     |
| 1 0     | 1               | 0               | Set       |
| 1 1     | Q̄               | Q               | Toggle    |

Set the clock to 1 Hz and the state of the circuit should change.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
