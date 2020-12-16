# Cheat Seat

## Cobination - Permutation - Selection of stuff:

#### Selection:
![](https://github.com/htsilvakt04/Elements-Of-Programming-Interview/blob/master/images/Screen%20Shot%202020-12-16%20at%2015.42.50.png)

Repetition allowed: `N^r`

Repetition is not allowed `N * N - 1 * N - 2 * ...`

---------------------

#### Cobination: When the order doesn't matter, it is a Combination


#### Permutation: N^N (When the order does matter it is a Permutation.)
![Alt Text](https://www.mathsisfun.com/combinatorics/images/permutation-lock.jpg)
>When repetition is allowed:

total choices: **N^r**

where N is the number of things to choose from,
and we choose r of them,
repetition is allowed,
and order matters.


>When repetition is **not** allowed:
After chose 1 elem, then N - 1 left. 
After chose another elem, then N - 2 left;

total choices: **N!**

![Permuation](https://github.com/htsilvakt04/Elements-Of-Programming-Interview/blob/master/images/Screen%20Shot%202020-12-16%20at%2013.32.49.png)


#### PowerSet: *2^N*
>Why: The power set of elems is determine by whether or not we chose the new element.

Example: _,_,_ => 2^3 of combination for 0 and 1
	  _,_,_,_ 2^4 of combination for 0 and 1



