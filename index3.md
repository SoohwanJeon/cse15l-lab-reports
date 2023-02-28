1. Log into ieng6


![Image](1.png)
----------------------------------------------------------------------------------------------------------------------------
2. Clone your fork of the repository from your Github account
I use gitclone to clone the lab7 file in to my repository

![Image](6.png)

----------------------------------------------------------------------------------------------------------------------------
3. Run the tests, demonstrating that they fail

![Image](2.png)

----------------------------------------------------------------------------------------------------------------------------
4. Edit the code file to fix the failing test
I used nano command to edit the file through terminal 
keyword nano help to edit the file.

In the filter method, result.add(0, s) inserts elements at the beginning of the list so 
the method is not return list which is same order as original list so I change result.add(0, s)
to result.add(s) 

![Image](3.png)

Also in the 'merge' method last while loop index1 should be index2 because 
if the index2 is not increased then it can be infinite loop

![Image](4.png)

After finish editing the file I save the file by using <^o> and exit by typing <^x>
----------------------------------------------------------------------------------------------------------------------------
5. Run the tests, demonstrating that they now succeed

run the Junit test again and check all test is run successfully.

![Image](5.png)
