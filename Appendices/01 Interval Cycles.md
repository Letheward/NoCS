# Appendix 01

About Interval Cycles.

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