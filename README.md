# RSA Cipher Machine (2018) [LINUX VERSION]
I started this project because I have a great interest in cryptography. This year I learned the RSA algorithm and decided to implement it in a program / library.

## My journey
* Started by implementing the math part: `./lib/mathRSA.py`
* Then jumped to encrypt strings: `./lib/stringRSA.py` (this gave me some trouble)
* and finally made the interactive shell: `./lib/enigma.py`

I insisted in using primes generated by me, so I also made a prime generator program ([`./.primes/primeGen.py`](../.primes/primeGen.py)). With that I learned the basics of Threading, which is nice!

## Usage
To use this wonderful cypher machine, just go to the lib directory and run

`python3 enigma.py` (Of course you have to get python3 installed first)

Have fun!
