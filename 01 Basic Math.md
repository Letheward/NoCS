# Basic Math In Chromatic Scale

## Pitch as Number

> What's the distance between `C` and `E` ?   

> A Major Third apart, that's because we memorize it that way.

> What about `G` and `B` ? `F#` and `A#` ? `Db` and `F` ?

Naming Notes with letters is confusing and hard to calculate,  
instead we'll using **Mod 12** and **Base 12** Numbers.

- Mod 12 number can represent Pitch Class

~~~
0  1  2  3  4  5  6  7  8  9  10(T) 11(E)  
C  C# D  D# E  F  F# G  G# A  A#    B
C  Db D  Eb E  F  Gb G  Ab A  Bb    B
~~~

By default `C = 0` (Mod 12)

- Base 12 number can represent Absolute Pitch

~~~
C4: 40
Ab5: 58
B3: 3E
F#10: T6
~~~

By default `C0 = 00` (Base 12).  

---

In 12TET, Transposing won't change the relations of Notes,    
so Mod 12 and Base 12 in relative sense is also helpful.  
When doing this we may add `Note = 0` (Mod 12) and `Note = 00` (Base 12). 

For example:

- `E = 0` :

~~~
0  1  2  3  4  5  6  7  8  9   10(T) 11(E)  
E  F  F# G  G# A  A# B  C  C#  D     D# 
E  F  Gb G  Ab A  Bb B  C  Db  D     Eb 
~~~

- `Bb2 = 00` :

~~~
C3: 02
A4: 1E
G1: -13
~~~

When analyzing a particular Scale or Chord,  
we often ignore the absolute Pitch of Notes in them  
By default `Root Note = 0` (Mod 12) and `Lowest Root Note = 00` (Base 12)

## Set of Notes

- Pitch Class:

~~~
C Major Chord: {0, 4, 7}
A Minor Chord: {9, 0, 4}
C Ionian: {0, 2, 4, 5, 7, 9, 11}
D Dorian: {2, 4, 5, 7, 9, 11, 0} (C = 0)
D Dorian: {0, 2, 3, 5, 7, 9, 10} (D = 0)
~~~

- Absolute Pitch:

~~~
C4, E4, G4: [40, 44, 47]
C2, G3, E4: [20, 37, 44]
A4, C5, E5: [00, 03, 07] (A4 = 00)
~~~

## Doing Math 

> The Nature of Chromatic Scale is the nature of number `12`

Pitch Class:

- `Pitch Class - Pitch Class = Interval Class`

~~~
D - G = 2 - 7 = 7 (Mod 12) Pure Fifth
G - D = 7 - 2 = 5 (Mod 12) Pure Fourth
~~~

- `Pitch Class +/- Interval Class = Pitch Class`

~~~
D + 5 = 2 + 5 = 7 (Mod 12) G
D - 7 = 2 - 7 = 7 (Mod 12) G
~~~

- `Interval Class +/- Interval Class = Interval Class`

~~~
7 + 5 = 0 (Mod 12) A Octave
7 - 3 = 4 (Mod 12) A Major Third
~~~

- `Set of Pitch - Pitch Class = Set of Pitch`

~~~
Dm7 - D: {2, 5, 9, 0} - 2 = {0, 3, 7, 10} (D = 0) 
General m7 Chord 

Gm - C (G = 0): {0, 3, 7} - 5 = {7, 10, 2} (C = 0)
Gm in C context
~~~

- `Set of Pitch +/- Interval Class = Set of Pitch`

~~~
D - C = 2 - 0 = 2
CMaj7 + 2 = {0, 4, 7, 11} + 2 = {2, 6, 9, 1} DMaj7 (C = 0)
~~~

---

Absolute Pitch:

- `Note - Note = Distance`

~~~
D#7 - Gb3 = 73 - 36 = 39 (Base 12) = 45 (Base 10)
Bb5 - E6 = 5T - 64 = -6

reference = A4 = 440Hz = 49
C4 - A4 = 40 - 49 = -9
B5 - A4 = 5E - 49 = 12 (Base 12) = 14 (Base 10)
~~~

- `Note +/- Distance = Note`

~~~
C3 + 10 = 30 + 10 = 40 (Base 12) C4
A4 - 5  = 49 - 5 = 44 (Base 12) E4
~~~

- `Distance +/- Distance = Distance`

~~~
A4 - C4 = 49 - 40 = 9
C4 - C3 = 40 - 30 = 10 (Base 12)
10 + 9 = 19 (Base 12)

A4 - C4 = 49 - 40 = 9
A4 - D4 = 49 - 42 = 7
9 - 7 = 2
D4 - C4 = 2
~~~

- `Set of Notes - Notes = Set of Distances`

~~~
C4, E4, G4 - G3 = [40, 44, 47] - 37 = 5, 9, 10 (Base 12)
~~~

- `Set of Notes +/- Distance = Set of Notes`

~~~
A2, B2, C3 + 6 = [29, 2E, 30] + 6 = [33, 35, 36] Eb, F, Gb
~~~