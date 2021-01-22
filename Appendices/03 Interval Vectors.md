# Appendix 03

About Interval Vectors.

## Examples

- Lydian
 
`Lydian = {0, 2, 4, 6, 7, 9, 11}`

~~~
2 4 6 7 9 11

4-2 6-2 7-2 9-2 11-2

6-4 7-4 9-4 11-4

7-6 9-6 11-6

9-7 11-7

11-9
~~~

~~~
2 4 6 7 9 11

2 4 5 7 9

2 3 5 7

1 3 5

2 4

2
~~~

`UIV(Lydian) = 254361`

`OIV(Lydian) = 15233 1 30201`

`PIV(Lydian) = 35231 1 10203`

- Locrian

`Locrian = {0, 1, 3, 5, 6, 8, 10}`

~~~
1 3 5 6 8 10

3-1 5-1 6-1 8-1 10-1

5-3 6-3 8-3 10-3

6-5 8-5 10-5

8-6 10-6

10-8
~~~

~~~
1 3 5 6 8 10

2 4 5 7 9

2 3 5 7

1 3 5

2 4

2
~~~

`UIV(Locrian) = 254361`

`OIV(Locrian) = 24324 1 21110`

`PIV(Locrian) = 24120 1 21314`

- Wholetone

`Wholetone = {0, 2, 4, 6, 8, 10}`

~~~
2 4 6 8 10

4-2 6-2 8-2 10-2

6-4 8-4 10-4
 
8-6 10-6

10-8
~~~

~~~
2 4 6 8 10

2 4 6 8

2 4 6
 
2 4

2
~~~

`UIV(Wholetone) = 060603`

`OIV(Wholetone) = 05040 3 02010`

`PIV(Wholetone) = 05040 3 02010`

- Chromatic

`Chromatic = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11}`

~~~
1 2 3 4 5 6 7 8 9 10 11

1 2 3 4 5 6 7 8 9 10

1 2 3 4 5 6 7 8 9

1 2 3 4 5 6 7 8

1 2 3 4 5 6 7

1 2 3 4 5 6

1 2 3 4 5 

1 2 3 4

1 2 3

1 2 

1 
~~~

`UIV(Chromatic) = cccccc`

`OIV(Chromatic) = et987 6 54321`

`PIV(Chromatic) = 5t381 6 e4927`

`5+t+3+8+1+6 = 33`

`e+4+9+2+7 = 33`

- Else
~~~
Diminished {0 1 3 4 6 7 9 10}

1 3 4 6 7 9 10
2 3 5 6 8 9
1 3 4 6 7
2 3 5 6
1 3 4
2 3
1

448444
43632 4 21210
23230 4 41612

2+3+2+3+0+4 = 14
4+1+6+1+2   = 14

Major Pentatonic {0 2 4 7 9}

2 4 7 9
2 5 7
3 5
2

032140
03112 0 20100
23110 0 00102


Diatonic Scales


Lydian {0 2 4 6 7 9 11}

2 4 6 7 9 11
2 4 5 7 9
2 3 5 7
1 3 5
2 4
2

PIV(Lydian) = 35231 1 10203


Ionian {0 2 4 5 7 9 11}

2 4 5 7 9 11
2 3 5 7 9
1 3 5 7
2 4 6
2 4
2

PIV(Ionian) = 35231 1 10203


Mixolydian {0 2 4 5 7 9 10}

2 4 5 7 9 10
2 3 5 7 8
1 3 5 6
2 4 5
2 3
1

PIV(Mixolydian) = 24120 1 21314


Dorian {0 2 3 5 7 9 10}

2 3 5 7 9 10
1 3 5 7 8
2 4 6 7
2 4 5
2 3
1

PIV(Dorian) = 35120 1 21313


Aeolian {0 2 3 5 7 8 10}

2 3 5 7 8 10
1 3 5 6 8
2 4 5 7
2 3 5
1 3
2

PIV(Aeolian) = 24010 1 22414


Phrygian = {0 1 3 5 7 8 10}

1 3 5 7 8 10
2 4 6 7 9
2 4 5 7
2 3 5
1 3
2

PIV(Phrygian) = 34120 1 21313


Locrian {0 1 3 5 6 8 10}`

1 3 5 6 8 10
2 4 5 7 9
2 3 5 7
1 3 5
2 4
2

PIV(Locrian) = 24120 1 21314


By Circle Of Fifth

35231 1 10203 Lydian
35231 1 10203 Ionian
24120 1 21314 Mixolydian
35120 1 21313 Dorian
24010 1 22414 Aeolian
34120 1 21313 Phrygian
24120 1 21314 Locrian


By Polarity

35231 1 10203 Lydian
35231 1 10203 Ionian
35120 1 21313 Dorian
34120 1 21313 Phrygian
24120 1 21314 Mixolydian
24120 1 21314 Locrian
24010 1 22414 Aeolian


Sum

14 1 6  Lydian
14 1 6  Ionian
11 1 10 Dorian
10 1 10 Phrygian
9  1 11 Mixolydian
9  1 11 Locrian
7  1 13 Aeolian


Sum 2

15 6  Lydian
15 6  Ionian
12 10 Dorian
11 10 Phrygian
10 11 Mixolydian
10 11 Locrian
8  13 Aeolian
~~~

~~~
Chord Inverse Transpose

Major

0 4 7 

4 7

3

001110
00110 0 10000

First Inversion

0 3 8

3 8

5

001110
00101 0 01000

Second Inversion

0 5 9 

5 9

4

001110
00011 0 00100

Minor

0 3 7

3 7

4

001110
00110 0 10000

First Inversion

0 4 9

4 9

5

001110
00011 0 00100

Second Inversion

0 5 8

5 8

3

001110
00101 0 01000


Major up 1

0 1 5 8

1 5 8

4 7

3

101220
10111 0 11000

Major up 2

0 2 6 9

2 6 9

4 7

3

012151
01110 1 10100
~~~