# solid65
compare emulators against each other

This project connects several emulators of the 6502 CPU and tests them against
each other.

## gianluca/mos6502

[link to repository](https://github.com/gianlucag/mos6502)

Known issues with the tester:
- It doesn't check that the number of cycles matches the number of reads and writes

## fake6502

[link to sourcefile](http://rubbermallet.org/fake6502.c)

## mos6502

An emulator written in Rust.

Known issues with the tester:
- It does not log the internal state of the CPU with each bus cycle.

[link to repository](https://github.com/mre/mos6502)
