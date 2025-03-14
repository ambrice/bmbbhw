# Big Mouth Billy Bass Master Control Program

This is the hardware design for the Big Mouth Billy Bass controller.  The current
software (zephyr version) runs on a group of 6 adafruit boards with a lot of
wires running between them.  So this is my first hardware design attempt, to use
the adafruit boards as a reference and compile them into one board.

The adafruit schematics are available under EAGLE which is a dead-end program, so
using KiCad 8 to design the board.  Started with brand-new KiCad 9, but it was
suggested that KiCad 8 would be more stable and have less potential issues with
manufacturing, Osh Park for example accepts KiCad 8 board files directly but not
KiCad 9 yet.
