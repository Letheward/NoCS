# Tertian Form

## Tertian Form Notation

T(Lydian)

`0 2 4 5 7 9 11`

~~~
0 4 7 11 2 6 9
0 1 2 3  4 5 6
~~~

`0 4 7 2` > `0124`

## Pure Tertian Scale (PTS)

### Properties Of PTS

A Pure Tertian Scale's every third is `3` or `4`

Combination Of Seconds

`1 + 2`

`2 + 1`

`1 + 3`

`3 + 1`

`2 + 2`

> so every triad is traditional

Major: `4 + 3`

Minor: `3 + 4`

Diminished: `3 + 3`

Augmented: `4 + 4`

> every seventh chord is traditional

M7: `4 + 3 + 4`

Dominant 7: `4 + 3 + 3`

Augmented 7: `4 + 4 + 3`

m7: `3 + 4 + 3`

mM7: `3 + 4 + 4`

m7b5: `3 + 3 + 4`

dim7: `3 + 3 + 3`

A PTS's Mirror Scale is also a PTS

> Because all Interval inverted is the same

- Lydian & Locrian

Lydian  
`0 2 4 6 7 9 11`  
`2 2 2 1 2 2 1`  

Locrian  
`1 2 2 1 2 2 2`  
`0 1 3 5 6 8 10`

- Lydian Augmented & Altered Scale

Lydian Augmented    
`0 2 4 6 8 9 11`  
`2 2 2 2 1 2 1`  

Altered Scale  
`0 1 3 4 6 8 10`  
`1 2 1 2 2 2 2`

- Melodic Minor #4 & Locrian Natural 6

Melodic Minor #4: A Harmonic Major Mode    
`0 2 3 6 7 9 11`  
`(2 1 3 1 2) 2 1`

Locrian Natural 6: A Harmonic Minor Mode  
`0 1 3 5 6 9 10`  
`1 2 (2 1 3 1 2)`

### No PTS below 6-tone or above 8-tone

~~~
x * 1 + y * 2 + z * 3 = 12
x + y + z = 5

y + 2 * z = 7

y = 3, z = 2, x = 0

2 2 2 3 3
~~~

~~~
x * 1 + y * 2 + z * 3 = 12
x + y + z = 9
x < 5

y + 2 * z = 3

y = 1, z = 1, x = 7

y = 3, z = 0, x = 6
~~~

### 6-tone Pure Tertian Scales

~~~
x * 1 + y * 2 + z * 3 = 12
x + y + z = 6

y + 2 * z = 6

if y = 2, z = 2
x = 2

only have pattern 2 1 3

2 1 3 2 1 3, head and end are 3 2

so x = 0, y = 6, z = 0

or x = 3, y = 0, z = 3
~~~

Whole-tone Scale (IV `060301`):   
`0 2 4 6 8 10`  
`2 2 2 2 2 2`  

Augmented Scale Modes (IV `303620`):  
`0 1 4 5 8 9`  
`1 3 1 3 1 3`

### 7-tone Pure Tertian Scales

- Only use `1` or `2` as Second

~~~
x * 1 + y * 2 + z * 3 = 12
z = 0
x + y + z = 7

x = 2
y = 5
~~~

Lydian Modes (IV `254361`):  
`0 2 4 6 7 9 11`  
`2 2 2 1 2 2 1`  

Lydian Augmented (Melodic Minor) Modes (IV `254452`):  
`0 2 4 6 8 9 11`  
`2 2 2 2 1 2 1`  

- Use `3` as Second

~~~
x * 1 + y * 2 + z * 3 = 12
x + y + z = 7
x < 4
z > 0

y + 2 * z = 5

if y = 1, z = 2
x = 4

so x = 2, y = 3, z = 1
~~~

Harmonic Minor Modes (IV `335442`):  
`0 2 3 5 7 8 11`
`2 1 2 2 1 3 1`

Harmonic Major Modes (IV `335442`):  
`0 2 4 5 7 8 11`  
`2 2 1 2 1 3 1`

### 8-tone Pure Tertian Scales

~~~
x * 1 + y * 2 + z * 3 = 12
x + y + z = 8
x < 5

y + 2 * z = 4

if y = 0, z = 2
x = 6

if y = 2, z = 1
x = 5

so x = 4, y = 4, z = 0
~~~

Diminished Scale Modes (IV `448444`):  
`0 1 3 4 6 7 9 10`  
`1 2 1 2 1 2 1 2`

---

## Tertian Chromatic Scale

> We could try to extend the idea on Chromatic Scale itself.

By definition, A Tertian Chromatic Scale should be a Set with all `12` notes, and every distance to the note at next Index is either `3` or `4`.

We can draw a graph like this, which is a binary tree that some children will have same value:
~~~
                      0
                     / \
                    3   4
                   / \ / \
                  6   7   8
                 / \ / \ / 
                9  10  11   0
                 \ / \ / \
              0   1   2   3   4
                 / \ / \ / \
            3   4   5   6   7   8
               / \ / \ / \ / \
          6   7   8   9  10  11   0
             / \ /     \ / \ / \
        9  10  11   0   1   2   3   4
           / \ / \     / \ / \ / \
      0   1   2   3   4   5   6   7   8
         / \ / \ / \ / \ / \ / \ / \
    3   4   5   6   7   8   9  10  11   0
       / \ / \ / \ / \ /     \ / \ / \
  6   7   8   9  10  11   0   1   2   3   4
     / \ /     \ / \ / \     / \ / \ / \
9  10  11   0   1   2   3   4   5   6   7   8
~~~

Because it must contain all `12` notes, then the note at every level must be unique,  
therefore something like `0 3 6 9 0 3 6 9 0 3 6 9` is not valid, as showed in the graph.

Immediately we can see from the graph that the last note can't have a `3` or `4` distance to `0`.

Therefore there can't be a "looping" Tertian Chromatic Scale.

So we can try ignore the last note, see if "non-looping" ones are possible.  

By writing a program that list all possible path and check validity one by one, we find `4` valid paths:

~~~
0  3  6  9  1  4  7  10 2  5  8  11
0  4  7  10 2  5  8  11 3  6  9  1
0  4  7  10 2  6  9  1  5  8  11 3
0  4  8  11 3  7  10 2  6  9  1  5
~~~

These Sets are the only `4` Tertian Chromatic Scales (if non-looping is acceptable).

We can see they all have a kind of self symmetry:

~~~
under list means:
0 for +3
1 for +4

0   3   6   9   1   4   7   10  2   5   8   11
  0   0   0   1   0   0   0   1   0   0   0

0   4   7   10  2   5   8   11  3   6   9   1
  1   0   0   1   0   0   0   1   0   0   1

0   4   7   10  2   6   9   1   5   8   11  3
  1   0   0   1   1   0   1   1   0   0   1

0   4   8   11  3   7   10  2   6   9   1   5
  1   1   0   1   1   0   1   1   0   1   1
~~~

So their negative sets in reverse order (and making note at index [`0`] = `0`) is themselves:

Start from `0` and use `- 3` or `- 4` instead of `+ 3` or `+ 4`:

~~~
original:
0  3  6  9  1  4  7  10 2  5  8  11
negative version:
0  9  6  3  11 8  5  2  10 7  4  1
rearrange:
1  4  7  10 2  5  8  11 3  6  9  0
-1:
0  3  6  9  1  4  7  10 2  5  8  11
which is the same as itself
~~~

~~~
original:
0  4  7  10 2  5  8  11 3  6  9  1
negative version:
0  8  5  2  10 7  4  1  9  6  3  11
rearrange:
11 3  6  9  1  4  7  10 2  5  8  0
-11(or +1):
0  4  7  10 2  5  8  11 3  6  9  1
which is the same as itself
~~~

~~~
original:
0  4  7  10 2  6  9  1  5  8  11 3
negative version:
0  8  5  2  10 6  3  11 7  4  1  9
rearrange:
9  1  4  7  11 3  6  10 2  5  8  0 
-9(or +3):
0  4  7  10 2  6  9  1  5  8  11 3
which is the same as itself
~~~

~~~
original:
0  4  8  11 3  7  10 2  6  9  1  5
negative version:
0  8  4  1  9  5  2  10 6  3  11 7
rearrange:
7  11 3  6  10 2  5  9  1  4  8  0
-7(or +5):
0  4  8  11 3  7  10 2  6  9  1  5
which is the same as itself
~~~

---

## Neo-Riemannian Theory

### Tonnetz

~~~
7   2   9   4   11  6   1
  11  6   1   8   3   10  5
    3   10  5   0   7   2   9
      7   2   9   4   11  6   1
        11  6   1   8   3   10  5
          3   10  5   0   7   2   9
~~~

~~~
    [4]     [11]    [6]
      -4          +3
[1]     [8] -1  [3]     [10]
      +1  -4  +3  -2
    [5] -7  [0] +7  [7]
      +2  -3  +4  -1
[2]     [9] +1  [4]     [11]
      -3          +4
    [6]     [1]     [8]
~~~

### Triadic Transformations

- P (Parallel) 

Major (`0, -1, 0`): [`0, 4, 7`] --> [`0, 3, 7`]

Minor (`0, +1, 0`): [`0, 3, 7`] --> [`0, 4, 7`]

- R (Relative)

Major (`0, 0, +2`)/(`-3, -4, -3`):

[`0, 4, 7`] --> [`0, 4, 9`]/[`9, 0, 4`]/([`0, 3, 7`]`-3`)

Minor (`-2, 0, 0`)/(`+3, +4, +3`):

[`0, 3, 7`] --> [`10, 3, 7`]/[`3, 7, 10`]/([`0, 4, 7`]`+3`)

- L (Leading-Tone Exchange)

Major (`-1, 0, 0`)/(`+4, +3, +4`):

[`0, 4, 7`] --> [`11, 4, 7`]/[`4, 7, 11`]/([`0, 3, 7`]`+4`)

Minor (`0, 0, +1`)/(`-4, -3, -4`):

[`0, 3, 7`] --> [`0, 3, 8`]/[`8, 0, 3`]/([`0, 4, 7`]`-4`)

- N (Nebenverwandt)

R --> L --> P

Major: (`-3-4, -4-3-1, -3-4`) = (`-7, -8, -7`) = (`+5, +4, +5`)

[`0, 4, 7`] --> [`5, 8, 0`]

Minor: (`+3+4, +4+3+1, +3+4`) = (`+7, +8, +7`) = (`-5, -4, -5`)

[`0, 3, 7`] --> [`7, 11, 2`]

- S (Slide)

L --> P --> R

Major: (`+4-3, +3+1-4, +4-3`) = (`+1, 0, +1`)

[`0, 4, 7`] --> [`1, 4, 8`]

Minor: (`-4+3, -3-1+4, -4+3`) = (`-1, 0, -1`)

[`0, 3, 7`] --> [`11, 3, 6`]

- H (Hexatonic Pole)

L --> P --> L

Major: (`+4+4, +3+1+3, +4+4`) = (`+8, +7, +8`) = (`-4, -5, -4`)

[`0, 4, 7`] --> [`8, 11, 3`]

Minor: (`-4-4, -3-1-3, -4-4`) = (`-8, -7, -8`) = (`+4, +5, +4`)

[`0, 3, 7`] --> [`4, 8, 11`]