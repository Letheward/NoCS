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

## Set of Pitches

{}



## Doing Math 

> The Nature of Chromatic Scale is the nature of number `12`

Pitch Class:

- `Pitch Class - Pitch Class = Interval Class`

~~~
D - G = 2 - 7 = 7 (Mod 12) also Pure Fifth
G - D = 7 - 2 = 5 (Mod 12) also Pure Fourth
~~~

- `Pitch Class +/- Interval Class = Pitch Class`

~~~
D + 5 = 2 + 5 = 7 (Mod 12) also G
D - 7 = 2 - 7 = 7 (Mod 12) also G
~~~

- `Interval Class + Interval Class = Interval Class`

~~~
7 + 5 = 0 (Mod 12) A Octave
~~~

---

Absolute Pitch:

~~~
D#7 - Gb3 = 73 - 36 = 39 (base 12) = 45 (base 10)
Bb5 - E6 = 5T - 64 = -6

reference = A4 = 440Hz = 49
C4 - A4 = 40 - 49 = -9
B5 - A4 = 5E - 49 = 12 (base 12) = 14 (base 10)
~~~