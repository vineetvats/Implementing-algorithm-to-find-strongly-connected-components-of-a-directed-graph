---------------------------- READ ME --------------------------

This is a readme file containing instructions for executing code for 

Short Project 10:  Implementing algorithm to find strongly connected components of a directed graph

Team No: 33

@Authors:
Vineet Vats: vxv180008
Yash Pradhan: ypp170130




Instructions to execute code:

The uploaded folder with name as my net id: ypp170130 contains java file "DFS.java", which also contains driver stub in main method


NOTE: while executing from command prompt, the pwd should be the directory containing the directory ypp170130

Steps for running code from the cmd prompt

1. Compile the "DFS.java" by executing the following command
> javac ypp170130/DFS.java

2. Run Driver stub by invoking main method
> java ypp170130/DFS


----------------------------- SAMPLE RUN --------------------------

Sample Input: 11 17   1 11 1   2 3 1   2 7 1   3 10 1   4 1 1   4 9 1   5 4 1   5 7 1   5 8 1   6 3 1   7 8 1   8 2 1   9 11 1   10 6 1   11 3 1   11 4 1   11 6 1 0

Sample Output:
______________________________________________
Graph: n: 11, m: 17, directed: true, Edge weights: false
1 :  (1,11)
2 :  (2,3) (2,7)
3 :  (3,10)
4 :  (4,1) (4,9)
5 :  (5,4) (5,7) (5,8)
6 :  (6,3)
7 :  (7,8)
8 :  (8,2)
9 :  (9,11)
10 :  (10,6)
11 :  (11,3) (11,4) (11,6)
______________________________________________

Number of Strongly Connected Components: 4
u       cno
1       3
2       2
3       4
4       3
5       1
6       4
7       2
8       2
9       3
10      4
11      3
