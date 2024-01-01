# Termite - SAM Coupé RS232 Terminal Software

## Introduction

This terminal software was originaly written as a project sponsored by Brian Gaff. The ideas was to
come up with fully working RS232 software (with VT100 emulation) for the SAM Coupe home computer. 

Thiw would use the SAM Comms Interface to connect to a modem, and then allow the SAM to Connect to bulletin
boards, the internet, and share files using ZModem etc etc.

It was intended to be similar to the MS DOS terminal software [Terminate](https://en.wikipedia.org/wiki/Terminate_(software))
and would copy some of its features such as user-to-user chat.

## Status

It's not finished, but it kind of works. THe source code provided is - at the time of writing - the same code that was last touched in 1994. 

## Features

- Keyboard support
- Bell sound on error/buffer fill
- Fast Buttefly print routine for text printing, with full color printing.
- Circular buffers for read/write handling from the Comms interface
- Re-entrancy handling for interrupts to allow interrupts to keep pumping while other unrelated interrupts are being serviced.
- Scrolling screen buffer
- Flashing cursor
- UI drawing routines
- Chat window
- Toggleable local echo
- Debugging mode
- Dialer and Phonebook support
- Screen flash support
- [ANSI](https://en.wikipedia.org/wiki/ANSI_escape_code) support

## To-Do

- Split file into files based on function.

---
Copyright &copyr; 1994 SImon Cooke
