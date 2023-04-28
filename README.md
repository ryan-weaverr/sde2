sde2.caml - Implementation file for the four functions outlined in the project info doc

sde2.log - Log file with output of two test cases for each function

Test cases:

first_duplicate: 
first_duplicate [1;2;3;4;5;6;7;4;5;8;9];;     Expected output : int = 4
first_duplicate [1;2;3;4;5;6;7;8;9;10];;      Expected output : int = -10000

first_nonrepeating:
first_nonrepeating [1;2;3;2;7;5;6;1;3];;      Expected output : int= 7
first_nonrepeating [1;1;1;2;2;2];;            Expected output : : int = -10000

sumOfTwo:
sumOfTwo([1;2;3],[10;20;30;40],42);;          Expected output : bool = true
sumOfTwo([1;2;3],[10;20;30;40],44);;          Expected output : bool = false

cyk_sublists:
cyk_sublists 4;;                              Expected output : (int * int) list = [(1, 3); (2, 2); (3, 1)]
cyk_sublists 3;;                              Expected output : (int * int) list = [(1, 2); (2, 1)]

Pledge: On my honor I have neither given nor received aid on this exam.
