# Sane-Java-Coding-Convention
Less-Strict Version of Sun's Official Coding Convention

## Differences
Modifications are as follows:
- 4 space indent, not 8
- Star imports are fine (IDE's do this a lot, so it's annoying)
- Line length can be a maximum of 120 characters, not 80 (If you're using a CRT Monitor with a resolution of 800x600, that's your problem, not mine)
- Constants named 'log' or 'logger' are allowed (all other constants follow Sun Convention)
- Magic numbers -1, 0, 1, 2, 3, 4, and 5 are allowed.

## Why
I just wanted to integrate Checkstyle into my project but I was appalled by both the Sun and Google convention for Java. I felt like there was a happy
medium somewhere, so I attempted to make it.  That's what this is.
