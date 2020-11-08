# Roguelike
A simple roguelike for the C64 written in Millfork

This project is written in Millfork, a "middle-level" programming language for 8-bit systems.
For more info, see here: https://github.com/KarolS/millfork/blob/master/docs/index.md

To build the projectL
java -jar c:\Users\chris\millfork-0.3.22\millfork.jar Roguelike.mfk  -s -g -Wall -fsource-in-asm -fsource-in-asm -flenient-encoding -foptimize-stdlib -O4 -Wall -fipo -G vice  -o Roguelike -t c64

To run it in VICE:
C:\Users\chris\WinVice\GTK3VICE-3.4-win64-r37388\x64sc.exe 'C:\Users\chris\Projects\Millfork\Roguelike\Roguelike.prg'

