            *********           VIRTUAL SODUKU                 **********

> About the Game:
 This is a logic based, combinatorial number placement puzzle. The objective of the game is to fill a 9x9 grid with digits so that each column, row and sub-grid compose of all the digits from 1-9 (repetition of digits is not allowed).

> How to Play: 

1.  Run the program named Soduku,C,
2.  Copy one of the test cases from the testcase.txt file and paste it on the output terminal of
    The program and hit enter,
3.  Now, as per your choice select numbers from 1-9 as there are 9 sub-grids in a 9x9 table. 
4.  Fill up the sub-grids.
5.  To check whether the sub-grids have been completely filled or not, enter digits from 1-9,
    The program will show how many empty boxes are left in each sub-grid,
6.  Now, as all the sub-grids would have been filled, press 0 to stop filling the boxes
7.  Hit Enter,
8.  If you filled the sub-grids correctly, the program will display, "Solved Successfully!!",otherwise, “Try Again!!".
 

    **************************
    
 ABOUT THE PROGRAM:

FUNCTIONS USED:

1.) row (): Checks if all the elements in each row are distinct or not.If true returns 1 else returns 0.
	          Arguments taken are 2-D array.

2.) col (): Checks if all the elements in each column are distinct or not.If true returns 1 else 0.
	          Arguments taken are 2-D array.

3.) showgrid(): Displays the sub-grid given by the user.Arguments taken are 2-D array and n.
		            (1<=n<=9)
  
4.) subgrid(): Calculates the number of empty boxes in the respective sub-grid and displays it.
	              Arguments taken are 2-D array and n. (1<=n<=9)

5.) calc_grid(): Fills the empty boxes with the digits given by the user in the sub-grid.
		             Arguments taken are 2-D array,n and u. 
                 (1<=n<=9)
		             You represent the number of empty boxes in the respective sub-grid.



