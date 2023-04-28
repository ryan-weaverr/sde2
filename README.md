sde2.caml - Implementation file for the four functions outlined in the project info doc

sde2.log - Log file with output of test cases for each function

Test cases:

# first_duplicate [1;2;3;4;5;6;7;4;5;8;9];;
: int = 4
# first_duplicate [1;2;3;4;5;6;7;4;5;2;9];;
: int = 2
# first_duplicate [1;2;3;4;5;6;7;8;9;10];;
: int = -10000

# first_nonrepeating [1;2;3;2;7;5;6;1;3];;
: int = 7
# first_nonrepeating [1;2;9;3;2;7;5;6;1;3];;
: int = 9
# first_nonrepeating [1;2;9;3;2;7;5;6;10;30];;
: int = 1
# first_nonrepeating [1;2;9;3;2;7;5;6;1;10;30];;
: int = 9
# first_nonrepeating [1;2;9;3;2;7;5;9;6;1;10;30];;
: int = 3
# first_nonrepeating [1;2;3;2;7;5;6;1;3];;
: int = 7
# first_nonrepeating [1;2;3;4;5;1;2;3;4;5];;
: int = -10000
# first_nonrepeating [1;2;3;4;5;1;2;3;4;9];;
: int = 5
# first_nonrepeating [1;1;1;2;2;2];;
: int = -10000

# sumOfTwo([1;2;3],[10;20;30;40],42);;
: bool = true
# sumOfTwo([1;2;3],[10;20;30;40],40);;
: bool = false
# sumOfTwo([1;2;3],[10;20;30;40],41);;
: bool = true
# sumOfTwo([1;2;3],[10;20;30;40],43);;
: bool = true
# sumOfTwo([1;2;3],[10;20;30;40],44);;
: bool = false
# sumOfTwo([1;2;3],[10;20;30;40],11);;
: bool = true
# sumOfTwo([1;2;3],[10;20;30;40],15);;
: bool = false

# cyk_sublists 4;;
: (int * int) list = [(1, 3); (2, 2); (3, 1)]
# cyk_sublists 3;;
: (int * int) list = [(1, 2); (2, 1)]
# cyk_sublists 5;;
: (int * int) list = [(1, 4); (2, 3); (3, 2); (4, 1)]
# cyk_sublists(6);;
: (int * int) list = [(1, 5); (2, 4); (3, 3); (4, 2); (5, 1)]

Pledge: On my honor I have neither given nor received aid on this exam.
