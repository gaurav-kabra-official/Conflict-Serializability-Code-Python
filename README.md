**A program which shall read a concurrent schedule involving n transactions with read and write instructions on data items 
from an input file and find whether the schedule is _Conflict Serializable_ or not (using the graph-based 
method). <br>In case of conflict serializable schedule, the program also gives the serializability order 
and for non-serializable schedule, give the cycle(s) present in the graph.<br>The  program should be able to handle any finite number of transactions and data items.**

## Author : [Gaurav Kabra](https://www.quora.com/profile/Gaurav-Kabra-23)

### Input:
Input file name is asked. [Here](https://github.com/gaurav-kabra-official/Conflict-Serializable/tree/master/Inputs) three sample files have already been provided.<br>Input1 is about cycle.<br>Input2 is CS.<br>Input3 is again about cycle but only a part is cyclic unlike case#1 where whole graph was cyclic.<br>Input4 is of only one transaction.<br>Input5 is when input format is violated.

### Run
Type _python driver.py_<br>and that's it!

### Version
I am using ***Python 3.7***. However, any version of Python 3 should work fine.

### Bug-reporting
However tested on many random schedules, bugs may be there. _Kindly report that to gauravkabra.official@gmail.com_ or _create a Pull request_.
