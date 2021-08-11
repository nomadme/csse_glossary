
## Sorting algorithm complexity
---

| algorithm | time complexity (best, avg, worst) | space | stable |
|---|---|---|---|
| selection | n^2 &emsp; n^2 &emsp; n^2 | constant | false
| bubble | n &emsp; n^2 &emsp; n^2 | constant | true
| insertion | n &emsp; n^2 &emsp; n^2 | constant | true
| heap | nlogn &emsp; nlogn &emsp; nlogn | constant | false
| quick | nlogn &emsp; nlogn &emsp; n^2 | constant | false
| merge | nlogn &emsp; nlogn &emsp; nlogn | n | true
| bucket | n + k &emsp; n + k &emsp; n + k | nk
| radix | nk &emsp; nk &emsp; nk


### Master Theorem
provides asymptotic analysis (time complexity) for many of the recursion algorithms that follow the patter of divide-and-conquer.

### Primitive data type
• a basic data type provided by the programming language.

* chars, int, floats, fixed-points, booleans, pointers

• a built-in type is a data type for which the programming language provides built-in support.

* tuple, list, complex number, rational number, arrays
* first-class function - JS, Lua, Go, Java, C++, C#