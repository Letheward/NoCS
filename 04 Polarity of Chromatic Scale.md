# Polarity Of Chromatic Scale

## Chromatic Scale is Lydian and Locrian **Combined**

Use `6` as a mid-point

LyCS or LoCS can be slice into Lydian and Locrian

- Lydian Chromatic Scale

| Note    | 1 5 2 6 3 7 b5 |b2 b6 b3 b7 4 |
| -       | -              | -            |
| Lydian  | 0 7 2 9 4 11 6 |              |
| Locrian | 0 6            | 1  8  3 10 5 |                     

- Locrian Chromatic Scale

| Note    | 1 4 b7 b3 b6 b2 b5 | 7  3 6 2 5 |
| -       | -                  | -          |
| Locrian | 0 5 10 3  8  1  6  |            |
| Lydian  | 0 6                | 11 4 9 2 7 |

> Thus, we can create Polarity for Chromatic Scale

Lydian: `+`  
Locrian: `-`

---

## Pythagorean tuning

- Perfect Fifth is Ratio `3:2`

- Perfect Fourth is Ratio `4:3`

> 12ET Fifth/Fourth is 2 cents different

As LyCS go up, the difference is larger and larger

> thus is more dissonant

As LoCS go up, the difference is larger and larger

> thus is more dissonant

until they meet

~~~
Note  Interval from D 	Size(cents)  ET-dif(cents)

G#    augmented fourth  611.73 	     11.73
C#    major seventh     1109.78      9.78
F#    major third       407.82 	     7.82
B     major sixth       905.87 	     5.87
E     major second      203.91 	     3.91
A     perfect fifth     701.96 	     1.96
D     unison            0 .00 	     0.00     
G     perfect fourth    498.04      −1.96
C     minor seventh     996.09 	    −3.91
F     minor third       294.13 	    −5.87
Bb    minor sixth       792.18 	    −7.82
Eb    minor second      90.22 	    −9.78
Ab    diminished fifth 	588.27 	    −11.73 
~~~

Or only LyCS/LoCS

so the number higher in LyCS/LoCS is less LyCS/LoCS-ish

thus we can **Weight** every number

## Just Intonation

Using Popular 5-limit Just Intonation

~~~
Name ET    Just     Difference
0    0     0        0
1    100   111.73  −11.73
2    200   203.91  −3.91
3    300   315.64  −15.64
4    400   386.31  +13.69
5    500   498.04  +1.96
6    600   582.51  +17.49
7    700   701.96  −1.96
8    800   813.69  −13.69
9    900   884.36  +15.64
10   1000  996.09  +3.91
11   1100  1088.27 +11.73
0    1200  1200.00  0 
~~~
S
Base On Difference

LyCs:
`0 7 2 11 4 9 6`
LoCS:
`0 5 10 1 8 3 6`

## Polarity Index (PI)

- Model 1

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 5 4 3 2 1  0 -1 -2 -3 -4 -5 
~~~

Lydian: `5 + 4 + 3 + 2 + 1 = + 15`

Ionian: `5 + 4 + 3 + 2 + 1 - 5 = + 10`

Mixolydian: `5 + 4 + 3 + 2 - 4 - 5 = + 5`

Lydian Dominant: `5 + 4 + 3 + 2 - 4 = + 10`

Lydian Augmented: `4 + 3 + 2 + 1 - 2 = + 8`

Harmonic Minor: `4 + 5 + 1 - 3 - 5 - 2 = 0`

Melodic Minor: `4 + 5 + 3 + 1 - 3 - 5 = + 5`

Major Pentatonic: `5 + 4 + 3 + 2 = + 14`

Minor Pentatonic: `4 + 5 - 3 - 5 - 4 = - 3`

Locrian Natural 2: `- 5 - 4 - 3 - 2 + 4 = - 10`

Half-Whole Diminished: `2 + 5 + 3 - 1 - 3 - 4 = + 2`

`0 1 3 4 6 7 9 10`

Whole-Half Diminished: `4 + 3 + 1 - 3 - 5 - 2 = - 2`

`0 2 3 5 6 8 9 11`

Altered Scale: `2 - 1 - 3 - 2 - 4 = - 8`

`0 1 3 4 6 8 10`

Augmented Scale: `2 + 5 + 1 - 3 - 2 = + 3` 

`0 3 4 7 8 11`

`0 1 4 5 8 9`: `2 + 3 - 1 - 5 - 2 = - 3`

- Model 2

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 1 2 3 2 1  0 -1 -2 -3 -2 -1 
~~~

Lydian: `1 + 2 + 3 + 2 + 1 = + 9`

Ionian: `1 + 2 + 3 + 2 + 1 - 1 = + 8`

Mixolydian: `1 + 2 + 3 + 2 - 1 - 2 = + 5`

Lydian Dominant: `1 + 2 + 3 + 2 - 2 = + 6`

Lydian Augmented: `2 + 3 + 2 + 1 - 2 = + 6`

Harmonic Minor: `1 + 2 + 1 - 2 - 3 - 1 = - 2`

Melodic Minor: `1 + 2 + 3 + 1 - 3 - 1 = + 3`

Major Pentatonic: `1 + 2 + 3 + 2 = + 8`

Minor Pentatonic: `1 + 2 - 3 - 2 - 1 = - 3`

Locrian Natural 2: `2 - 3 - 1 - 2 - 2 = - 6`

Half-Whole Diminished: `- 1 - 3 + 2 + 1 + 3 - 2 = 0`

`0 1 3 4 6 7 9 10`

Whole-Half Diminished: `2 - 3 - 1 - 2 + 3 + 1 = 0`

`0 2 3 5 6 8 9 11`

Altered Scale: `- 1 - 3 + 2 - 2 - 2 = - 6`

`0 1 3 4 6 8 10`

Augmented Scale: `- 3 + 2 + 1 - 2 + 1 = - 1` 

`0 3 4 7 8 11`

`0 1 4 5 8 9`: `- 1 + 2 - 1 - 2 + 3 = + 1`

- Model 3

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 1 2 3 4 5  0 -5 -4 -3 -2 -1 
~~~

Lydian: `1 + 2 + 3 + 4 + 5 = + 15`

Ionian: `1 + 2 + 3 + 4 + 5 - 1 = + 14`

Mixolydian: `1 + 2 + 3 + 4 - 1 - 2 = + 7`

Lydian Dominant: `1 + 2 + 3 + 4 - 2 = + 8`

Lydian Augmented: `2 + 3 + 4 + 5 - 4 = + 10`

Harmonic Minor: `1 + 2 + 5 - 3 - 1 - 4 = 0`

Melodic Minor: `1 + 2 + 3 + 5 - 3 - 1 = + 7`

Major Pentatonic: `1 + 2 + 3 + 4 = + 10`

Minor Pentatonic: `1 + 2 - 3 - 1 - 2 = - 3`

Locrian Natural 2: `2 - 3 - 1 - 3 - 2 = - 7`

Half-Whole Diminished: `4 + 1 + 3 - 5 - 3 - 2 = - 2`

`0 1 3 4 6 7 9 10`

Whole-Half Diminished: `2 + 3 + 5 - 3 - 1 - 4 = + 2`

`0 2 3 5 6 8 9 11`

Altered Scale: `4 - 5 - 3 - 4 - 2 = - 10`

`0 1 3 4 6 8 10`

Augmented Scale: `4 + 1 + 5 - 3 - 4 = + 3` 

`0 3 4 7 8 11`

`0 1 4 5 8 9`: `4 + 3 - 5 - 1 - 4 = - 3`

- Model 4 (Using Just Intonation)

~~~
0 7 2 11 4 9 6  3  8  1  10 5
0 5 4 3  2 1 0 -1 -2 -3 -4 -5 
~~~

Lydian: `5 + 4 + 3 + 2 + 1 = + 15`

Ionian: `5 + 4 + 3 + 2 + 1 - 5 = + 10`

Mixolydian: `5 + 4 + 2 + 1 - 4 - 5 = + 3`

Lydian Dominant: `5 + 4 + 2 + 1 - 4 = + 8`

Lydian Augmented: `4 + 3 + 2 + 1 - 2 = + 8`

Harmonic Minor: `4 + 5 + 3 - 1 - 5 - 2 = + 4`

Melodic Minor: `4 + 5 + 3 + 1 - 1 - 5 = + 7`

Major Pentatonic: `5 + 4 + 2 + 1 = + 12`

Minor Pentatonic: `4 + 5 - 1 - 5 - 4 = - 1`

Locrian Natural 2: `- 5 - 4 - 2 - 1 + 4 = - 8`

Half-Whole Diminished: `2 + 5 + 1 - 3 - 1 - 4 = 0`

`0 1 3 4 6 7 9 10`

Whole-Half Diminished: `4 + 1 + 3 - 1 - 5 - 2 = 0`

`0 2 3 5 6 8 9 11`

Altered Scale: `2 - 3 - 1 - 2 - 4 = - 8`

`0 1 3 4 6 8 10`

Augmented Scale: `2 + 5 + 3 - 1 - 2 = + 7` 

`0 3 4 7 8 11`

`0 1 4 5 8 9`: `2 + 1 - 3 - 5 - 2 = - 7`


## Polar Ratio (PR)

Notes in a Chord or Scale:

> Amount in Lydian except Note `0` /
> Amount in Locrian except Note `0`

Lydian: `6:1`

Locrian: `1:6`

Lydian Dominant: `5:1`

Lydian Augmented: `5:1`

Altered Scale: `2:5`

`0 1 3 4 6 8 10`

Dorian: `3:3`

Whole-Tone: `3:3`

Half-Whole Diminished: `4:4`

`0 1 3 4 6 7 9 10`

Whole-Half Diminished: `4:4`

`0 2 3 5 6 8 9 11`

Chromatic Scale: `6:6`

## Neutral Scale

Neutral Scale's Mirror Scale is Itself

- Dorian: `0 2 3 5 7 9 10`

- Mixolydian b6: `0 2 4 5 7 8 10`

~~~
0 3 4 6 8 9

0 2 3 6 9 10

0 2 4 6 8 10

0 2 5 7 10

0 3 5 7 9
~~~

`6` is the mirror point

Neutral Scale's PI is always `0`, PR `= 1:1`



## Scale Axis

Tritone Axis is the line between Scale Root Note and Tritone

- Any Pair of Mirror Scales have a Tritone Axis

Lydian:  0 2 4 6 7 9 11
Locrian: 0 1 3 5 6 8 10

~~~
0 + 7 = 7
0 - 7 = 5
6 + ( 6 - 7 ) = 5
~~~

---

## Function Axis System

`0` as Tonic

~~~
Tonic              Subtonic           Dominant

Primary Secondary  Primary Secondary  Primary Secondary

T1      T2         S1      S2         D1      D2

0 6     3 9        5 11    2 8        7 1     4 10 
~~~

~~~
0  1  2  3  4  5  6  7  8  9  10 11
T1 D1 S2 T2 D2 S1 T1 D1 S2 T2 D2 S1

0  7  2  9  4  11 6  1  8  3  10 5
T1 D1 S2 T2 D2 S1 T1 D1 S2 T2 D2 S1
~~~

~~~
        0                
    11     1        
  10          2     
9               3  
  8           4   
     7     5       
        6         
        

        0
     5     7
  10          2
3               9
  8           4
     1     11
        6
~~~