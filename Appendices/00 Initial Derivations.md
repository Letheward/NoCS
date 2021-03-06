# Appendix 00

Initial derivations on some phenomena that spark the whole project.

## Properities of IC`5` and IC`7`

- Mid-points of two Interval Cycles are also the mid-point of Chromatic Scale

> Tritone: `12 / 2 = 6`  

~~~
( 7 * 12 ) / 2 = ( 6 + 1 ) * 12 / 2

( 5 * 12 ) / 2 = ( 6 - 1 ) * 12 / 2

6 * 12 / 2 = 3 * 12

1 * 12 / 2 = 12 - ( 1 * 12 / 2 ) = 6
~~~

- Black Keys Form Pentatonic

Start from `F`

`0 7 2 9 4 11 6` is Lydian, and `F` Lydian have all the white keys  
The rest is black keys

> `7 * 7 = 1`

~~~
7 * 7  = 7 * (7 + 0) = 7 * 7 + 7 * 0 = 7 * 0 + 1 = 0 + 1
7 * 8  = 7 * (7 + 1) = 7 * 7 + 7 * 1 = 7 * 1 + 1 = 7 + 1
7 * 9  = 7 * (7 + 2) = 7 * 7 + 7 * 2 = 7 * 2 + 1 = 2 + 1
7 * 10 = 7 * (7 + 3) = 7 * 7 + 7 * 3 = 7 * 3 + 1 = 9 + 1
7 * 11 = 7 * (7 + 4) = 7 * 7 + 7 * 4 = 7 * 4 + 1 = 4 + 1
~~~

`0 7 2 9 4` is Major Pentatonic

---

## Lydian Chromatic Scale (LyCS)

### Laws of LyCS

> `P = 7 * d`

`P` is the result **P**itch   
`d` is the LyCS **d**egree  

> if `d` is even, `P = d`

> if `d` is odd, `P = 6 + d = d - 6`

> `d = 7 * P`

### LyCS Analyze

> `7 = 6 + 1`, `P = 7 * d = 6 * d + d`

~~~
7 * 0  = 6 * 0  + 0
7 * 1  = 6 * 1  + 1
7 * 2  = 6 * 2  + 2
7 * 3  = 6 * 3  + 3
7 * 4  = 6 * 4  + 4
7 * 5  = 6 * 5  + 5
7 * 6  = 6 * 6  + 6
7 * 7  = 6 * 7  + 7
7 * 8  = 6 * 8  + 8
7 * 9  = 6 * 9  + 9
7 * 10 = 6 * 10 + 10
7 * 11 = 6 * 11 + 11
7 * 12 = 6 * 12 + 12
~~~

> If `d` is even, `P = 7 * d = 6 * d + d = d`
> 
> If `d` is odd, `P = 7 * d = 6 * ( d - 1 ) + 6 + d = 6 + d`  
> `P = 7 * d = 6 * ( d + 1 ) - 6 + d = d - 6`

> When `d <= 6`

~~~
6 * 0 + 0 = 0 + 0 = 0
6 * 2 + 2 = 0 + 2 = 2
6 * 4 + 4 = 0 + 4 = 4
6 * 6 + 6 = 0 + 6 = 6
6 * 1 + 1 = 6 + 1 = 7
6 * 3 + 3 = 6 + 3 = 9
6 * 5 + 5 = 6 + 5 = 11

Form Lydian: 0 2 4 6 7 9 11
~~~

> When `d > 6`

> `d = 6 + x`  
> If `d` is odd, `P = 7 * d = 6 * ( d - 1 ) + 6 + ( 6 + x ) = x`

~~~
6 * 7  + 7  = 6 + ( 6 + 1 ) = 1
6 * 9  + 9  = 6 + ( 6 + 3 ) = 3
6 * 11 + 11 = 6 + ( 6 + 5 ) = 5
6 * 8  + 8  = 0 + 8         = 8
6 * 10 + 10 = 0 + 10        = 10
6 * 12 + 12 = 0 + 12        = 0
~~~

- Result

~~~
7 * 0  = 0
7 * 1  = 7
7 * 2  = 2
7 * 3  = 9
7 * 4  = 4
7 * 5  = 11
7 * 6  = 6
7 * 7  = 1
7 * 8  = 8
7 * 9  = 3
7 * 10 = 10
7 * 11 = 5
7 * 12 = 0
~~~

- In Chromatic Order

~~~
7 * 0  = 0
7 * 7  = 1
7 * 2  = 2
7 * 9  = 3
7 * 4  = 4
7 * 11 = 5
7 * 6  = 6
7 * 1  = 7
7 * 8  = 8
7 * 3  = 9
7 * 10 = 10
7 * 5  = 11
7 * 12 = 0
~~~

> We can see if `7 * d = P`, `7 * N = d`

> If `d` is even, `P = 7 * d = 6 * d + d = d`
>
> If `d` is odd, `P = 7 * d = 6 * ( d - 1 ) + 6 + d = 6 + d`  
> `7 * N = 7 * ( 6 + d ) = 7 * 6 + 7 * d`   
> `= ( 7 * 6 + d * 6 ) + d = (( 7 + d ) * 6) + d = d`

## Locrian Chromatic Scale (LoCS)

### Laws of LoCS

> `P = 5 * d`

`P` is the result **P**itch  
`d` is the LoCS **d**egree  

> If `d` is even, `P = - d`

> If `d` is odd, `P = 6 - d`

> When `d = 3 * k`, (`k` is natural number)  
> `P = d`

> `d = 5 * P`

### LoCS Analyze

> `5 = 6 - 1`, `5 * d = 6 * d - d`

~~~
5 * 0  = 6 * 0  - 0  
5 * 1  = 6 * 1  - 1  
5 * 2  = 6 * 2  - 2  
5 * 3  = 6 * 3  - 3  
5 * 4  = 6 * 4  - 4  
5 * 5  = 6 * 5  - 5  
5 * 6  = 6 * 6  - 6  
5 * 7  = 6 * 7  - 7  
5 * 8  = 6 * 8  - 8  
5 * 9  = 6 * 9  - 9  
5 * 10 = 6 * 10 - 10  
5 * 11 = 6 * 11 - 11  
5 * 12 = 6 * 12 - 12  
~~~

> If `d` is even, `5 * d = 6 * d - d = - d`  
> If `d` is odd, `5 * d = 6 * d - d = 6 * ( d - 1 ) + 6 - d = 6 - d`

> When `d <= 6`

~~~
6 * 0 - 0 = 0 - 0 = 0
6 * 5 - 5 = 6 - 5 = 1
6 * 3 - 3 = 6 - 3 = 3
6 * 1 - 1 = 6 - 1 = 5
6 * 6 - 6 = 0 - 6 = 6
6 * 4 - 4 = 0 - 4 = 8
6 * 2 - 2 = 0 - 2 = 10 

Form Locrian: 0 1 3 5 6 8 10
~~~

> When `d > 6`

~~~
6 * 10 - 10 = 0 - 10        = 2  
6 * 8  - 8  = 0 - 8         = 4  
6 * 11 - 11 = 6 - ( 6 + 5 ) = 7  
6 * 9  - 9  = 6 - ( 6 + 3 ) = 9  
6 * 7  - 7  = 6 - ( 6 + 1 ) = 11  
6 * 12 - 12 = 0 - 12        = 0  
~~~

- Result

~~~
5 * 0  = 0
5 * 1  = 5
5 * 2  = 10
5 * 3  = 3
5 * 4  = 8
5 * 5  = 1
5 * 6  = 6
5 * 7  = 11
5 * 8  = 4
5 * 9  = 9
5 * 10 = 2
5 * 11 = 7
5 * 12 = 0
~~~

- In Chromatic Order

~~~
5 * 0  = 0
5 * 5  = 1
5 * 10 = 2
5 * 3  = 3
5 * 8  = 4
5 * 1  = 5
5 * 6  = 6
5 * 11 = 7
5 * 4  = 8
5 * 9  = 9
5 * 2  = 10
5 * 7  = 11
5 * 12 = 0
~~~

> We can see if `5 * d = P`, `5 * N = d`

> If `d` is even, `P = 5 * d = 6 * d - d = - d`  
> `5 * N = 5 * ( - d ) = 6 * ( - d ) - 1 * ( - d ) = d`
>
> If `d` is odd, `P = 5 * d = 6 * d - d = 6 * ( d - 1 ) + 6 - d = 6 - d`   
> `5 * ( 6 - d ) = 5 * 6 - 5 * d = 5 * 6 - ( 6 - 1 ) * d`  
> `= 6 * 5 - 6 * d + d = 6 * ( 5 - d ) + d = d`

> And if `d = 3 * k`, (`k` is natural number)  
> `P = d`

> `P = 5 * d = ( 4 + 1 ) * d = 4 * 3 * k + d = d`

---

## Lydian Modes Analyze

- LyCS Degree:

> Up a Fifth (`7`) every time

~~~
Scale       0  1  2  3  4  5  6    LyCS Degree 

Lydian      0  2  4  6  7  9  11   0           
Ionian      0  2  4  5  7  9  11   1           
Mixolydian  0  2  4  5  7  9  10   2           
Dorian      0  2  3  5  7  9  10   3           
Aeolian     0  2  3  5  7  8  10   4           
Phrygian    0  1  3  5  7  8  10   5           
Locrian     0  1  3  5  6  8  10   6           
~~~

- Lydian:

~~~
7 * 0  = 0
7 * 1  = 7
7 * 2  = 2
7 * 3  = 9
7 * 4  = 4
7 * 5  = 11
7 * 6  = 6
~~~

> LyCS degree up `1`, Root Note up a Fifth (`7`)

- Form Ionian

~~~
7 * 1  = 7
7 * 2  = 2
7 * 3  = 9
7 * 4  = 4
7 * 5  = 11
7 * 6  = 6
7 * 0  = 0
~~~

> Make Scale Root Note the same as Original Lydian

~~~
7 * 1 - 7 = 7 * 0       = 0
7 * 2 - 7 = 7 * 1       = 7
7 * 3 - 7 = 7 * 2       = 2
7 * 4 - 7 = 7 * 3       = 9
7 * 5 - 7 = 7 * 4       = 4
7 * 6 - 7 = 7 * 5       = 11
7 * 0 - 7 = 7 * ( - 1 ) = 5
~~~

> We can see one Note in Ionian is different, and is `1` lower

~~~
7 * 6 - 7 * ( - 1 ) = 7 * 7
= ( 6 + 1 ) * ( 6 + 1 ) = 6^2 + 1^2 + 2 * 6 * 1
= 6 * ( 6 + 2 ) + 1^2 = 1
~~~

> From Ionian , LyCS degree up `1` Again

- Form Mixolydian

~~~
7 * 1 - 7     = 7 * 0     = 0 
7 * 2 - 7     = 7 * 1     = 7 
7 * 3 - 7     = 7 * 2     = 2 
7 * 4 - 7     = 7 * 3     = 9 
7 * 5 - 7     = 7 * 4     = 4 
7 * 6 - 1 - 7 = 7 * 5 - 1 = 10
7 * 0 - 7     = 7 * 6 - 1 = 5
~~~

> One Note in Mixolydian is different to Ionian, and is `1` lower

**As such**, we can form all the rest Modes:  

- Dorian

~~~
7 * 0     = 0 
7 * 1     = 7 
7 * 2     = 2 
7 * 3     = 9 
7 * 4 - 1 = 3 
7 * 5 - 1 = 10
7 * 6 - 1 = 5
~~~

- Aeolian

~~~
7 * 0     = 0   
7 * 1     = 7   
7 * 2     = 2   
7 * 3 - 1 = 8      
7 * 4 - 1 = 3   
7 * 5 - 1 = 10  
7 * 6 - 1 = 5  
~~~

- Phrygian

~~~
7 * 0     = 0   
7 * 1     = 7   
7 * 2 - 1 = 1   
7 * 3 - 1 = 8      
7 * 4 - 1 = 3   
7 * 5 - 1 = 10  
7 * 6 - 1 = 5  
~~~

- Locrian

~~~
7 * 0     = 0   
7 * 1 - 1 = 6   
7 * 2 - 1 = 1   
7 * 3 - 1 = 8      
7 * 4 - 1 = 3   
7 * 5 - 1 = 10  
7 * 6 - 1 = 5  
~~~

> we can see every LyCS Degree higher,  
> the result Scale is one Note `1` lower than the previous Scale,  
> and that Note is before the Note lowered in previous Scale  
> in LyCS Sequence

## Locrian Modes Analyze

- LoCS Degree:

> Up a Fourth (`5`) every time

~~~
Scale       0  1  2  3  4  5  6    LoCS Degree 
Locrian     0  1  3  5  6  8  10   0
Phrygian    0  1  3  5  7  8  10   1
Aeolian     0  2  3  5  7  8  10   2
Dorian      0  2  3  5  7  9  10   3
Mixolydian  0  2  4  5  7  9  10   4
Ionian      0  2  4  5  7  9  11   5
Lydian      0  2  4  6  7  9  11   6
~~~

- Locrian:

~~~
5 * 0  = 0
5 * 1  = 5
5 * 2  = 10
5 * 3  = 3
5 * 4  = 8
5 * 5  = 1
5 * 6  = 6
~~~

> LoCS degree up `1`, Root Note up a Fourth (`5`)

- Form Phrygian

~~~
5 * 1  = 5
5 * 2  = 10
5 * 3  = 3
5 * 4  = 8
5 * 5  = 1
5 * 6  = 6
5 * 0  = 0
~~~

> Make Scale Root Note the same as Original Locrian

~~~
5 * 1 - 5 = 5 * 0       = 0
5 * 2 - 5 = 5 * 1       = 5
5 * 3 - 5 = 5 * 2       = 10
5 * 4 - 5 = 5 * 3       = 3
5 * 5 - 5 = 5 * 4       = 8
5 * 6 - 5 = 5 * 5       = 1
5 * 0 - 5 = 5 * ( - 1 ) = 7
~~~

> We can see one Note in Phrygian is different, and is `1` higher

~~~
5 * 6 - 5 * ( - 1 ) = 5 * 7
= ( 6 - 1 ) * ( 6 + 1 ) = 6^2 + 1 * ( - 1 ) = - 1
~~~

> From Phrygian, LoCS degree up `1` Again

- Form Aeolian

~~~
5 * 1 - 5     = 5 * 0     = 0
5 * 2 - 5     = 5 * 1     = 5
5 * 3 - 5     = 5 * 2     = 10
5 * 4 - 5     = 5 * 3     = 3
5 * 5 - 5     = 5 * 4     = 8
5 * 6 + 1 - 5 = 5 * 5 + 1 = 2
5 * 0 - 5     = 5 * 6 + 1 = 7
~~~

> One Note in Aeolian is different to Phrygian, and is `1` higher

**As such**, we can form all the rest Modes:  

- Dorian

~~~
5 * 0     = 0
5 * 1     = 5
5 * 2     = 10
5 * 3     = 3
5 * 4 + 1 = 9
5 * 5 + 1 = 2
5 * 6 + 1 = 7
~~~

- Mixolydian

~~~
5 * 0     = 0
5 * 1     = 5
5 * 2     = 10
5 * 3 + 1 = 4
5 * 4 + 1 = 9
5 * 5 + 1 = 2
5 * 6 + 1 = 7
~~~

- Ionian

~~~
5 * 0     = 0
5 * 1     = 5
5 * 2 + 1 = 11
5 * 3 + 1 = 4
5 * 4 + 1 = 9
5 * 5 + 1 = 2
5 * 6 + 1 = 7
~~~

- Lydian

~~~
5 * 0     = 0
5 * 1 + 1 = 6
5 * 2 + 1 = 11
5 * 3 + 1 = 4
5 * 4 + 1 = 9
5 * 5 + 1 = 2
5 * 6 + 1 = 7
~~~

> we can see every LoCS Degree higher,  
> the result Scale is one Note `1` higher than the previous Scale,  
> and that Note is before the Note heightened in previous Scale  
> in LoCS Sequence