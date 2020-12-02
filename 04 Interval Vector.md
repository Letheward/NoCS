# Interval Vector

## Unordered Interval Vector (UIV)

UIV is the normal Interval Vector

- Computation Method

`S = {0, p1, p2, ... pn}`

~~~
p1-0 p2-0 ... pn-0

p2-p1 p3-p1 p4-p1 ... pn-p1

...

p(n-1)-p(n-2) pn-p(n-2)

pn-p(n-1)
~~~

`v1` = Total number of `1` and `11`  
`v2` = Total number of `2` and `10`  
`v3` = Total number of `3` and `9`  
`v4` = Total number of `4` and `8`  
`v5` = Total number of `5` and `7`  
`v6` = Total number of `6`

`UIV(S) = {v1, v2, v3, v4, v5, v6}`

## Ordered Interval Vector (OIV)

OIV is the new Interval Vector

- Computation Method

`S = {0, p1, p2, ... pn}`

~~~
p1-0 p2-0 ... pn-0

p2-p1 p3-p1 p4-p1 ... pn-p1

...

p(n-1)-p(n-2) pn-p(n-2)

pn-p(n-1)
~~~

`v1` = Total number of `1`  
`v2` = Total number of `2`  
`v3` = Total number of `3`  
`v4` = Total number of `4`  
`v5` = Total number of `5`  
`v6` = Total number of `6`  
`v7` = Total number of `7`  
`v8` = Total number of `8`  
`v9` = Total number of `9`  
`v10` = Total number of `10`  
`v11` = Total number of `11`

`OIV(S) = {v1, v2, v3, v4, v5, v6, v7, v8, v9, v10, v11}`

## Polarity Interval Vector (PIV)

PIV is the new Interval Vector in Chromatic Polarity Order

- Computation Method

`S = {0, p1, p2, ... pn}`

~~~
p1-0 p2-0 ... pn-0

p2-p1 p3-p1 p4-p1 ... pn-p1

...

p(n-1)-p(n-2) pn-p(n-2)

pn-p(n-1)
~~~

`v1` = Total number of `1`  
`v2` = Total number of `2`  
`v3` = Total number of `3`  
`v4` = Total number of `4`  
`v5` = Total number of `5`  
`v6` = Total number of `6`  
`v7` = Total number of `7`  
`v8` = Total number of `8`  
`v9` = Total number of `9`  
`v10` = Total number of `10`  
`v11` = Total number of `11`

`PIV(S) = {v7, v2, v9, v4, v11, v6, v1, v8, v3, v10, v5}`

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