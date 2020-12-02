# Appendix 04

About certain Sets.

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


## Tertian Sequence

A Third means `2` in Scale Degree, `4` in LyCS Degree (Mod 7)

> LyCS Order

Lydian (Tertian):

~~~
d t
0 0  7 * 0 = 0
1 2  7 * 4 = 4
2 4  7 * 1 = 7
3 6  7 * 5 = 11
4 1  7 * 2 = 2
5 3  7 * 6 = 6
6 5  7 * 3 = 9
~~~

Ionian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4     = 4
2 4  7 * 1     = 7
3 6  7 * 5     = 11
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Mixolydian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4     = 4
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Dorian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Aeolian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~

Phrygian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2 - 1 = 1
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~

Locrian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1 - 1 = 6
3 6  7 * 5 - 1 = 10
4 1  7 * 2 - 1 = 1
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~

> Scale Degree Order

Ionian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4     = 4
2 4  7 * 1     = 7
3 6  7 * 5     = 11
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Dorian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Mixolydian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4     = 4
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3     = 9
~~~

Phrygian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2 - 1 = 1
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~

Lydian (Tertian):

~~~
d t
0 0  7 * 0 = 0
1 2  7 * 4 = 4
2 4  7 * 1 = 7
3 6  7 * 5 = 11
4 1  7 * 2 = 2
5 3  7 * 6 = 6
6 5  7 * 3 = 9
~~~

Aeolian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1     = 7
3 6  7 * 5 - 1 = 10
4 1  7 * 2     = 2
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~


Locrian (Tertian):

~~~
d t
0 0  7 * 0     = 0
1 2  7 * 4 - 1 = 3
2 4  7 * 1 - 1 = 6
3 6  7 * 5 - 1 = 10
4 1  7 * 2 - 1 = 1
5 3  7 * 6 - 1 = 5
6 5  7 * 3 - 1 = 8
~~~

> Descending Order

Chord Tone Descending Order (Mod 7):
`3 6 2 5 1 4`

Chord Degree Descending Order (Mod 7):
`5 3 1 6 4 2`

## Quartal Sequence

A Fourth means `3` in Scale Degree, `6` in LyCS Degree (Mod 7)

> LyCS Order

Lydian (Quartal):

~~~
d t
0 0  7 * 0 = 0
1 3  7 * 6 = 6
2 6  7 * 5 = 11
3 2  7 * 4 = 4
4 5  7 * 3 = 9
5 1  7 * 2 = 2
6 4  7 * 1 = 7
~~~

Ionian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5     = 11
3 2  7 * 4     = 4
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Mixolydian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4     = 4
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Dorian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Aeolian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Phrygian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2 - 1 = 1
6 4  7 * 1     = 7
~~~

Locrian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2 - 1 = 1
6 4  7 * 1 - 1 = 6
~~~

> Scale Degree Order

Ionian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5     = 11
3 2  7 * 4     = 4
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Dorian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Phrygian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2 - 1 = 1
6 4  7 * 1     = 7
~~~

Lydian (Quartal):

~~~
d t
0 0  7 * 0 = 0
1 3  7 * 6 = 6
2 6  7 * 5 = 11
3 2  7 * 4 = 4
4 5  7 * 3 = 9
5 1  7 * 2 = 2
6 4  7 * 1 = 7
~~~

Mixolydian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4     = 4
4 5  7 * 3     = 9
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Aeolian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2     = 2
6 4  7 * 1     = 7
~~~

Locrian (Quartal):

~~~
d t
0 0  7 * 0     = 0
1 3  7 * 6 - 1 = 5
2 6  7 * 5 - 1 = 10
3 2  7 * 4 - 1 = 3
4 5  7 * 3 - 1 = 8
5 1  7 * 2 - 1 = 1
6 4  7 * 1 - 1 = 6
~~~

> Descending Order

Chord Tone Descending Order (Mod 7):
`3 6 2 5 1 4`

Chord Degree Descending Order (Mod 7):
`1 2 3 4 5 6`

## Negative Chords

Triads:

~~~
Lydian     M    0 4 7  11 2  6 9 0    0 3 6  dim
Ionian     M    0 4 7  11 2  5 9 0    0 4 7  M
Mixolydian M    0 4 7  10 2  5 9 0    0 4 7  M
Dorian     m    0 3 7  10 2  5 9 0    0 4 7  M
Aeolian    m    0 3 7  10 2  5 8 0    0 3 7  m
Phrygian   m    0 3 7  10 1  5 8 0    0 3 7  m
Locrian    dim  0 3 6  10 1  5 8 0    0 3 7  m
~~~

Seventh Chords:
~~~
Lydian     M7     0 4 7 11  2 6 9 0    0 4 7 10 7 
Ionian     M7     0 4 7 11  2 5 9 0    0 3 7 10 m7
Mixolydian 7      0 4 7 10  2 5 9 0    0 3 7 10 m7
Dorian     m7     0 3 7 10  2 5 9 0    0 3 7 10 m7
Aeolian    m7     0 3 7 10  2 5 8 0    0 3 6 10 m7b5
Phrygian   m7     0 3 7 10  1 5 8 0    0 4 7 11 M7
Locrian    m7b5   0 3 6 10  1 5 8 0    0 4 7 11 M7
~~~

9th Chords:
~~~
Lydian     M9     0 4 7  11 2  6 9 0    0 3 7 10 1  m9b9
Ionian     M9     0 4 7  11 2  5 9 0    0 3 6 10 1  m9b9b5
Mixolydian 9      0 4 7  10 2  5 9 0    0 4 7 11 2  M9
Dorian     m9     0 3 7  10 2  5 9 0    0 4 7 11 2  M9
Aeolian    m9     0 3 7  10 2  5 8 0    0 4 7 10 2  9
Phrygian   m9b9   0 3 7  10 1  5 8 0    0 3 7 10 2  m9
Locrian    m9b9b5 0 3 6  10 1  5 8 0    0 3 7 10 2  m9
~~~

11th Chords:

~~~
Lydian     M#11     0 4  7 11 2 6  9 0    0 4 7 11 2 5  M11
Ionian     M11      0 4  7 11 2 5  9 0    0 4 7 10 2 5  11
Mixolydian 11       0 4  7 10 2 5  9 0    0 3 7 10 2 5  m11
Dorian     m11      0 3  7 10 2 5  9 0    0 3 7 10 2 5  m11
Aeolian    m11      0 3  7 10 2 5  8 0    0 3 7 10 1 5  m11b9
Phrygian   m11b9    0 3  7 10 1 5  8 0    0 3 6 10 1 5  m11b9b5
Locrian    m11b9b5  0 3  6 10 1 5  8 0    0 4 7 11 2 6  M#11
~~~

13th Chords:

~~~
Lydian     M13#11      0  4 7 11 2 6 9  0    0 3 7 10 2 5 8  m13b13
Ionian     M13         0  4 7 11 2 5 9  0    0 3 7 10 1 5 8  m13b13b9
Mixolydian 13          0  4 7 10 2 5 9  0    0 3 6 10 1 5 8  m13b13b9b5
Dorian     m13         0  3 7 10 2 5 9  0    0 4 7 11 2 6 9  M13#11
Aeolian    m13b13      0  3 7 10 2 5 8  0    0 4 7 11 2 5 9  M13
Phrygian   m13b13b9    0  3 7 10 1 5 8  0    0 4 7 10 2 5 9  13
Locrian    m13b13b9b5  0  3 6 10 1 5 8  0    0 3 7 10 2 5 9  m13
~~~