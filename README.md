# 2WayStack
Repo Having Stack Implementation in DSA
## Functions:

push1(int x) –> pushes x to first stack 
push2(int x) –> pushes x to second stack
pop1() –> pops an element from first stack and return the popped element 
pop2() –> pops an element from second stack and return the popped element

![1_HgSDnflZkAjg9aXD5Fq9ZA](https://user-images.githubusercontent.com/101993714/210789308-83d7e0f0-e2be-4e43-899e-28e9e9670c25.jpg)


To implement push1():
First, check whether the top1 is greater than 0 
If it is then add an element at the top1 index and decrement top1 by 1
Else return ...


To implement push2():


First, check whether top2 is less than n – 1
If it is then add an element at the top2 index and increment the top2 by 1
Else return ...


To implement pop1():
First, check whether the top1 is less than or equal to n / 2
If it is then increment the top1 by 1 and return that element.
Else return ...

To implement pop2():
First, check whether the top2 is greater than or equal to (n + 1) / 2
If it is then decrement the top2 by 1 and return that element.
Else return ...


