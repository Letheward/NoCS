# Polarity Of Chromatic Scale

## Chromatic Scale is Lydian and Locrian **Combined**

Use `6` as a mid-point

LyCS or LoCS can be slice into Lydian and Locrian

- Lydian Chromatic Scale

~~~
Note    | 1  5  2  6  3  7  b5 | b2 b6 b3 b7 4 |
Lydian  | 0  7  2  9  4  11 6  |               |
Locrian | 0                 6  | 1  8  3  10 5 |                     
~~~

- Locrian Chromatic Scale

~~~
Note    | 1  4  b7 b3 b6 b2 b5 | 7  3  6  2  5 |
Locrian | 0  5  10 3  8  1  6  |               |
Lydian  | 0                 6  | 11 4  9  2  7 |
~~~

> Thus, we can create Polarity for Chromatic Scale

Lydian: `+`  
Locrian: `-`

---

## Polarity Label

TODO

~~~
0 7 2 9 4 11 6
0 1 2 3 4 5  6

0 5 10 3 8 1 6
0 1 2  3 4 5 6
~~~

- Dorian 

`0 2 3 5 7 9 10` > `0 7 2 9 - 0 5 10 3`

`0123-0123`

- Random Set

`0 1 6 7 8 10` > `0 7 6 - 0 10 8 1 6`

`016-02456`

the reverse

- 

`025-0134`

`0 2 11 - 0 5 3 8`

`0 2 3 5 8 11`

- 

`0235-0235`

`0 2 9 11 - 0 10 3 1`

`0 1 2 3 9 10 11`

TODO

~~~
another method

06 7294e 5t381
00-00000-00000

0 1 2 3 9 10 11

00-0290e-0t301

except first one, 0 for not having a note

or 

0- -29-e -t3-1

binary:

0 2 3 5 8 11

0 6 7294e 5t381
10-01001-10010

or
10-01001-10010
to decimal

// notice this is backwards
// because the order is from 0 to 4
// but numbers started from highest digit 
10-01001-10010
        <- from here

actual binary numbers:
01   10010    01001

=> 1-22-9  // this is unreadable, but may be helpful in calculations
// or for categorizing

for comparison:
1-22-9
1     --------- type, usually 1 or 3, for if note 6 is present
22    --------- Lydian notes
9     --------- Locrian notes

22 > 9 (notice here is a assumption that high digit numbers are more "important")
so overall this set is more lydian

total states:
4-32-32  // actually, can be remembered
~~~

## Weighting

### Pythagorean tuning

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

---

### Just Intonation

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

LyCS:
`0 7 2 11 4 9 6`
LoCS:
`0 5 10 1 8 3 6`

---

### Value 3rds and 7ths

`+`
~~~
0 1 2 3 4 5  6
0 7 2 9 4 11 6
0 1 2 3 3 2  1
~~~

`-`
~~~
0 1 2  3 4 5 6
0 5 10 3 8 1 6
0 1 2  3 3 2 1
~~~

`6` > have `7` = `1`  
have `5` = `-1`  
have `5` and `7`/nor `5` or `7` = `0`  

## Polarity Index (PI)

- Model 1

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 5 4 3 2 1  0 -1 -2 -3 -4 -5 
~~~

Lydian: `5 + 4 + 3 + 2 + 1 = + 15`

Ionian: `5 + 4 + 3 + 2 + 1 - 5 = + 10`

Harmonic Minor: `4 + 5 + 1 - 3 - 5 - 2 = 0`

Altered Scale: `2 - 1 - 3 - 2 - 4 = - 8`

`0 1 3 4 6 8 10`

- Model 2

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 1 2 3 2 1  0 -1 -2 -3 -2 -1 
~~~

Lydian: `1 + 2 + 3 + 2 + 1 = + 9`

Ionian: `1 + 2 + 3 + 2 + 1 - 1 = + 8`

Harmonic Minor: `1 + 2 + 1 - 2 - 3 - 1 = - 2`

Altered Scale: `- 1 - 3 + 2 - 2 - 2 = - 6`

`0 1 3 4 6 8 10`

- Model 3

~~~
0 7 2 9 4 11 6  1  8  3  10 5
0 1 2 3 4 5  0 -5 -4 -3 -2 -1 
~~~

Lydian: `1 + 2 + 3 + 4 + 5 = + 15`

Ionian: `1 + 2 + 3 + 4 + 5 - 1 = + 14`

Harmonic Minor: `1 + 2 + 5 - 3 - 1 - 4 = 0`

Altered Scale: `4 - 5 - 3 - 4 - 2 = - 10`

`0 1 3 4 6 8 10`

- Model 4 (Using Just Intonation)

~~~
0 7 2 11 4 9 6  3  8  1  10 5
0 5 4 3  2 1 0 -1 -2 -3 -4 -5 
~~~

Lydian: `5 + 4 + 3 + 2 + 1 = + 15`

Ionian: `5 + 4 + 3 + 2 + 1 - 5 = + 10`

Harmonic Minor: `4 + 5 + 3 - 1 - 5 - 2 = + 4`

Altered Scale: `2 - 3 - 1 - 2 - 4 = - 8`

`0 1 3 4 6 8 10`

- Model 5 (Value 3rds and 7ths)

Lydian: `0 2 4 6 7 9 11`

`0 +2 +3 +1 +1 +3 +2 = 12`

Ionian: `0 2 4 5 7 9 11`

`0 +2 +3 -1 +1 +3 +2 = 10`

Dorian: `0 2 3 5 7 9 10`

`0 +2 -3 -1 +1 +3 -2 = 0`

W-H Dim: `0 2 3 5 6 8 9 11`

`0 +2 -3 -1 -1 -3 +3 +2 = -1`

## Polar Ratio (PR)

Notes in a Chord or Scale:

> Amount in Lydian except Note `0` /
> Amount in Locrian except Note `0`

Lydian: `6:1`

Locrian: `1:6`

Dorian: `3:3`

Chromatic Scale: `6:6`