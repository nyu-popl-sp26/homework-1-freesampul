## Solution to Problem 1

(a) 

The value for pi in line 4 is bound at the line immedietly above, the 3.14159 on line 3 I'm not sure the exact term, but this is local reference, pi is redefined in the function, thus the more specific val here

The value of pi on line 7 is set on line 1, 3.14. This is because pi is only redefinied in the circumference def and so the area func uses the first val of pi it can access.


(b)
The x on line 3 is the integer that is input into the function, line 2. The function definition has a (x: Int), so whatever the match is looking for is the integer passed into the function
On line 6, the value is still the same as what was assigned on line 2, but the x is now bound to line 5 as the case x => creates a new binding. 
Line 10 is the same as line 6, where the value is whatever was defined as passed into the function (line 2), but the x on line 10 is bound to the case creation on line 5
on line 11, the val of x is three as it can't use the x passed into the funtion, it must use the x value defined on line 1. This applies to both x's on line 11. 


## Solution to Problem 2

(a) Execution trace:

```
???
```

(b) Tail-recursive implementation

```scala
???
```

Execution trace:

```
???
```