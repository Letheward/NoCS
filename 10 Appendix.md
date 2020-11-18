# Appendix

## Interval Cycles in Clock Diagram

~~~
        0
    11     1
  10          2
9               3   IC1
  8           4
     7     5
        6

        0
    10     2
  8           4
6               6   IC2
  4           8
     2     10
        0
        
        0
     9     3
  6           6
3               9   IC3
  0           0
     9     3
        6
        
        0
     8     4
  4           8
0               0   IC4
  8           4
     4     8
        0
        
        0
     7     5
  2          10
9               3   IC5
  4           8
     11    1
        6
        
        0
     6     6
  0           0
6               6   IC6
  0           0
     6     6
        0

        0
     5     7
  10          2
3               9   IC7
  8           4
     1     11
        6

        0
     4     8
  8           4
0               0   IC8
  4           8
     8     4
        0
        
        0
     3     9
  6           6
9               3   IC9
  0           0
     3     9
        6
        
        0
     2     10
  4           8
6               6   IC10
  8           4
    10     2
        0
        
        0
     1     11
  2          10
3               9   IC11
  4           8
     5     7
        6
~~~

## LyCS & LoCS

- IC`7` - Lydian Chromatic Scale (LyCS)

~~~
Degree   0   1   2   3   4   5   6   7   8   9   10  11

Note     1   5   2   6   3   7   b5  b2  b6  b3  b7  4
Mod 12   0   7   2   9   4   11  6   1   8   3   10  5 
7 Multi  0   7   14  21  28  35  42  49  56  63  70  77
Octave   0   0   1   1   2   2   3   4   4   5   5   6 
~~~

- IC`5` - Locrian Chromatic Scale (LoCS)

~~~
Degree   0   1   2   3   4   5   6   7   8   9   10  11

Note     1   4   b7  b3  b6  b2  b5  7   3   6   2   5 
Mod 12   0   5   10  3   8   1   6   11  4   9   2   7 
5 multi  0   5   10  15  20  25  30  35  40  45  50  55
Octave   0   0   1   1   1   2   2   2   3   3   4   4 
~~~

## Diatonic Modes

### Scale Ascended

~~~
Scale        0  1  2  3  4  5  6     Brightness
 
Ionian       0  2  4  5  7  9  11    2          
Dorian       0  2  3  5  7  9  10    4          
Phrygian     0  1  3  5  7  8  10    6          
Lydian       0  2  4  6  7  9  11    1          
Mixolydian   0  2  4  5  7  9  10    3          
Aeolian      0  2  3  5  7  8  10    5          
Locrian      0  1  3  5  6  8  10    7          
~~~

### Brightness Descended

~~~
Scale        0  1  2  3  4  5  6     Mode Degree

Lydian       0  2  4  6  7  9  11    4          
Ionian       0  2  4  5  7  9  11    1          
Mixolydian   0  2  4  5  7  9  10    5          
Dorian       0  2  3  5  7  9  10    2          
Aeolian      0  2  3  5  7  8  10    6          
Phrygian     0  1  3  5  7  8  10    3          
Locrian      0  1  3  5  6  8  10    7          
~~~

### Mirror Scale (Negative Scale)

- Lydian & Locrian

~~~
Scale        0   1   2   3   4   5   6   0    Direction 

Lydian       0   2   4   6   7   9   11  0              
             0  +2  +2  +2  +1  +2  +2  +1    >         
            -2  -2  -2  -1  -2  -2  -1   0    <         

Locrian      0   1   3   5   6   8   10  0              
             0  +1  +2  +2  +1  +2  +2  +2    >         
            -1  -2  -2  -1  -2  -2  -2   0    <         
~~~

- Ionian & Phrygian

~~~
Scale        0   1   2   3   4   5   6   0    Direction

Ionian       0   2   4   5   7   9   11  0             
             0  +2  +2  +1  +2  +2  +2  +1    >    
            -2  -2  -1  -2  -2  -2  -1   0    <

Phrygian     0   1   3   5   7   8   10  0        
             0  +1  +2  +2  +2  +1  +2  +2    >   
            -1  -2  -2  -2  -1  -2  -2   0    <   
~~~

- Mixolydian & Aeolian

~~~
Scale        0   1   2   3   4   5   6   0    Direction 

Mixolydian   0   2   4   5   7   9   10  0        
             0  +2  +2  +1  +2  +2  +1  +2    >   
            -2  -2  -1  -2  -2  -2  -2   0    <   

Aeolian      0   2   3   5   7   8   10  0        
             0  +2  +1  +2  +2  +1  +2  +2    >   
            -2  -1  -2  -2  -1  -2  -2   0    <   
~~~

- Dorian & Itself

~~~
Scale        0   1   2   3   4   5   6   0    Direction 

Dorian       0   2   3   5   7   9   10  0              
             0  +2  +1  +2  +2  +2  +1  +2    >         
            -2  -1  -2  -2  -2  -1  -2   0    <         
~~~

### Interval Vector

- Any Lydian Mode

~~~
PCI         1 2 3 4 5 6
Occurrence  2 5 4 3 6 1 
~~~

- Relation to LyCS

~~~
Occurrence   6   5   4   3   2   1

PCI          5   2   3   4   1   6
LyCS Degree  1   2   3   4   5   6
Note         7   2   9   4   11  6
~~~

- Relation to LoCS

~~~
Occurrence   6   5   4   3   2   1 

PCI          5   2   3   4   1   6 
LoCS Degree  0   11  10  9   8   7 
Note         7   2   9   4   11  6 
~~~

## Important Concepts

- [12 Equal Temperament](https://en.wikipedia.org/wiki/Equal_temperament)
- [Harmonic Series](https://en.wikipedia.org/wiki/Harmonic_series_(music))
- [Just Intonation](https://en.wikipedia.org/wiki/Just_intonation)
- [Pythagorean Tuning](https://en.wikipedia.org/wiki/Pythagorean_tuning)
- [Circle Of Fifths](https://en.wikipedia.org/wiki/Circle_of_fifths)
- [Ladder Of Thirds](https://en.wikipedia.org/wiki/Ladder_of_thirds)
- [Tertian](https://en.wikipedia.org/wiki/Tertian)
- [Quartal And Quintal Harmony](https://en.wikipedia.org/wiki/Quartal_and_quintal_harmony)
- [Pitch Class](https://en.wikipedia.org/wiki/Pitch_class)
- [Interval Vector](https://en.wikipedia.org/wiki/Interval_vector)
- [Interval Cycle](https://en.wikipedia.org/wiki/Interval_cycle)
- [Generated Collection](https://en.wikipedia.org/wiki/Generated_collection)
- [Modular Arithmetic](https://en.wikipedia.org/wiki/Modular_arithmetic)
- [Set Theory](https://en.wikipedia.org/wiki/Set_theory_(music))
- [Axis System](https://en.wikipedia.org/wiki/Axis_system)
- [Neo-Riemannian Theory](https://en.wikipedia.org/wiki/Neo-Riemannian_theory)
- [Tonnetz](https://en.wikipedia.org/wiki/Tonnetz)
- [Lydian Chromatic Concept](https://en.wikipedia.org/wiki/Lydian_Chromatic_Concept_of_Tonal_Organization)