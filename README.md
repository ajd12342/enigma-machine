# enigma-machine

### A modern version of the World War II Enigma Machine in Racket, a variant of Scheme. The machine has encrypt, decrypt, and crack mode.

### Course Project, CS 154, Spring 2019, IIT Bombay.

The Enigma machine was implemented as a GUI in Racket using `racket-gui`, `2htdp/image` and `math/matrix` libraries of Racket. 

It has 3 modes:
* Encrypt - Encrypt mode uses a random initial seed and rotor configuration and encrypts whatever you type. Finish by hitting Enter.
* Decrypt - Enter the random seed and rotor configuration used by the encryption and enter the encrypted message. Since Enigma is self reciprocal, the decrypt mode is exactly the encrypt mode with a given seed and rotor config.
* Crack - A module that would make Turing proud, this one attempts to guess the message given the encrypted message and a known message prefix.

The project report explains the methods used in great detail.

## How to run:

1. Install DrRacket 7.1 or above. See https://racket-lang.org/download/
2. Run `racket board.rkt` on the terminal.
3. Enjoy!

