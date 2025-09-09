# Ex.No: 5   Logic Programming – Factorial of number   
### DATE: 09/09/2025                                                                           
### REGISTER NUMBER : 212223040177
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0,1).
factorial(A,B) :-  
           A > 0, 
           C is A-1,
           factorial(C,D),
           B is A*D.


?- factorial(5, B).
```


### Output:

<img width="216" height="51" alt="image" src="https://github.com/user-attachments/assets/e6dce559-4a11-44f6-acf9-973bc88987ae" />
<img width="219" height="54" alt="image" src="https://github.com/user-attachments/assets/7e1d0e94-476d-4489-996d-458c217fd219" />


### Result:
Thus the factorial of given number was found by logic programming. 
