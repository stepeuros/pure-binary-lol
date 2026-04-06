# pure-binary-lol
# Pure Binary Hello

This program is written in **raw machine code** — no programming language used.
I cannot run this as the binary does not match with the correct system, I am on Windows 11, this is written for Linux (x86, 32-bit).
There is however a solution to run this but I do not want to spend much time and energy now, I probably will in the future.

## Binary

```
10111000 00000100 00000000 00000000 00000000
10111011 00000001 00000000 00000000 00000000
10111001 00010000 10000000 00000100 00001000
10111010 00000101 00000000 00000000 00000000
11001101 10000000

10111000 00000001 00000000 00000000 00000000
10111011 00000000 00000000 00000000 00000000
11001101 10000000

01001000 01100101 01101100 01101100 01101111
...
```

## Hex

```
B8 04 00 00 00 BB 01 00 00 00 B9 0C 00 00 00 BA 05 00 00 00 CD 80
B8 01 00 00 00 BB 00 00 00 00 CD 80
48 65 6C 6C 6F
```


## What it does

Prints: `Hello`

## Explanation

* No Python
* No C
* Just CPU instructions
