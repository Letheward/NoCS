# Lydian & Locrian

## Lydian Chromatic Scale (LyCS)

### Laws of LyCS

> `N = 7 * d`

`N` is the result **N**ote  
`d` is the LyCS **d**egree  

> if `d` is even, `N = d`

> if `d` is odd, `N = 6 + d = d - 6`

> `d = 7 * N`

### LyCS Analyze

> `7 = 6 + 1`, `N = 7 * d = 6 * d + d`

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

> If `d` is even, `N = 7 * d = 6 * d + d = d`
> 
> If `d` is odd, `N = 7 * d = 6 * ( d - 1 ) + 6 + d = 6 + d`  
> `N = 7 * d = 6 * ( d + 1 ) - 6 + d = d - 6`

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
> If `d` is odd, `N = 7 * d = 6 * ( d - 1 ) + 6 + ( 6 + x ) = x`

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

> We can see if `7 * d = N`, `7 * N = d`

> If `d` is even, `N = 7 * d = 6 * d + d = d`
>
> If `d` is odd, `N = 7 * d = 6 * ( d - 1 ) + 6 + d = 6 + d`  
> `7 * N = 7 * ( 6 + d ) = 7 * 6 + 7 * d`   
> `= ( 7 * 6 + d * 6 ) + d = (( 7 + d ) * 6) + d = d`

## Locrian Chromatic Scale (LoCS)

### Laws of LoCS

> `N = 5 * d`

`N` is the result **N**ote  
`d` is the LoCS **d**egree  

> If `d` is even, `N = - d`

> If `d` is odd, `N = 6 - d`

> When `d = 3 * k`, (`k` is natural number)  
> `N = d`

> `d = 5 * N`

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

> We can see if `5 * d = N`, `5 * N = d`

> If `d` is even, `N = 5 * d = 6 * d - d = - d`  
> `5 * N = 5 * ( - d ) = 6 * ( - d ) - 1 * ( - d ) = d`
>
> If `d` is odd, `N = 5 * d = 6 * d - d = 6 * ( d - 1 ) + 6 - d = 6 - d`   
> `5 * ( 6 - d ) = 5 * 6 - 5 * d = 5 * 6 - ( 6 - 1 ) * d`  
> `= 6 * 5 - 6 * d + d = 6 * ( 5 - d ) + d = d`

> And if `d = 3 * k`, (`k` is natural number)  
> `N = d`

> `N = 5 * d = ( 4 + 1 ) * d = 4 * 3 * k + d = d`

---

## Lydian Modes Analyze

- LyCS Degree:

> Up a Fifth (`7`) every time

| Scale      | 0 | 1 | 2 | 3 | 4 | 5 | 6 | LyCS Degree |
| -          | - | - | - | - | - | - | - | :-:         |
| Lydian     | 0 | 2 | 4 | 6 | 7 | 9 | 11| 0           |
| Ionian     | 0 | 2 | 4 | 5 | 7 | 9 | 11| 1           |
| Mixolydian | 0 | 2 | 4 | 5 | 7 | 9 | 10| 2           |
| Dorian     | 0 | 2 | 3 | 5 | 7 | 9 | 10| 3           |
| Aeolian    | 0 | 2 | 3 | 5 | 7 | 8 | 10| 4           |
| Phrygian   | 0 | 1 | 3 | 5 | 7 | 8 | 10| 5           |
| Locrian    | 0 | 1 | 3 | 5 | 6 | 8 | 10| 6           |

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

| Scale      | 0 | 1 | 2 | 3 | 4 | 5 | 6 | LoCS Degree |
| -          | - | - | - | - | - | - | - | :-:         |
| Locrian    | 0 | 1 | 3 | 5 | 6 | 8 | 10| 0           |
| Phrygian   | 0 | 1 | 3 | 5 | 7 | 8 | 10| 1           |
| Aeolian    | 0 | 2 | 3 | 5 | 7 | 8 | 10| 2           |
| Dorian     | 0 | 2 | 3 | 5 | 7 | 9 | 10| 3           |
| Mixolydian | 0 | 2 | 4 | 5 | 7 | 9 | 10| 4           |
| Ionian     | 0 | 2 | 4 | 5 | 7 | 9 | 11| 5           |
| Lydian     | 0 | 2 | 4 | 6 | 7 | 9 | 11| 6           |

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

## w Lydian Chords Analyze

> Chords are related to Scale 

> As part of different sequence of a Scale

`d`:Chord degree

`t`:Chord tone

Lydian:

~~~
d t
0 0  7 * 0 = 0
1 1  7 * 2 = 2
2 2  7 * 4 = 4
3 3  7 * 6 = 6
4 4  7 * 1 = 7
5 5  7 * 3 = 9
6 6  7 * 5 = 11
~~~

### Tertian Sequence

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

### Quartal Sequence

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

### Negative Chords

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

---

### Chained Chords 

In 7-Note Scales, Chords can be chained to create the full Tertian Sequence (13th Chord)

- Triads

Lydian
~~~
0 4 7 11 2 6 9
0 1 2 3  4 5 6
0 2 4 6  1 3 5

0 4 7  7 11 2  2 6 9
0 1 2  2 3  4  4 5 6
0 2 4  4 6  1  1 3 5
~~~

Ionian
~~~
0 4 7 11 2 5 9
0 1 2 3  4 5 6
0 2 4 6  1 3 5

IV     I      V
5 9 0  0 4 7  7 11 2
5 6 0  0 1 2  2 3  4
3 5 0  0 2 4  4 6  1
~~~

- Seventh Chords

Lydian
~~~
0 4 7 11 2 6 9
0 1 2 3  4 5 6
0 2 4 6  1 3 5

0 4 7 11   11 2 6 9
0 1 2 3    3  4 5 6
0 2 4 6    6  1 3 5
~~~

Ionian

~~~
0 4 7 11 2 5 9
0 1 2 3  4 5 6
0 2 4 6  1 3 5

IMaj7     VIIm7b5
0 4 7 11  11 2 5 9
0 1 2 3   3  4 5 6      
0 2 4 6   6  1 3 5
~~~

### Tertian Lydian Chromatic Scales

Tertian Lydian Chromatic Scales are closely related to Tonnetz

Upper one is Minor based, lower one is Major based

`7 = 3 + 4`
~~~
 3 t 5 0 7 2 9 4 e 6 1 8 3 t 5 0 7 2 9 4 e 6 1 
0 7 2 9 4 e 6 1 8 3 t 5 0 7 2 9 4 e 6 1 8 3 t 5
 4 e 6 1 8 3 t 5 0 7 2 9 4 e 6 1 8 3 t 5 0 7 2
~~~

cover all Major and Minor Triads in every key

### Tertian Locrian Chromatic Scales

Negative Tonnetz

`5 = 2 + 3`

~~~
 2 7 0 5 t 3 8 1 6 e 4 9 2 7 0 5 t 3 8 1 6 e 4 9 
0 5 t 3 8 1 6 e 4 9 2 7 0 5 t 3 8 1 6 e 4 9 2 7 0
 3 8 1 6 e 4 9 2 7 0 5 t 3 8 1 6 e 4 9 2 7 0 5 t 
~~~
