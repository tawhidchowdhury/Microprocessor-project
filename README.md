# 8086 Secret Messaging Demo

A small EMU8086 assembly-language course project that simulates a sender and receiver exchanging a message and an optional reply in a DOS-style text interface.

## What it demonstrates

- Sender and receiver sign-in using sample credentials stored in the source.
- Selecting a recipient and protecting a message with a secret key.
- Simple Caesar, Atbash, and ROT13 substitution options.
- A receiver reply flow and sender-side reply view.

## Run

Open `secretmsg.asm.txt` in EMU8086, assemble it, and run it in the emulator.

## Limitations

This is an educational simulation, not a secure messaging system. The credentials are hard-coded, the ciphers are classical substitutions, and the messages are handled inside the program rather than sent over a network.