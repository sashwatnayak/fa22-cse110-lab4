1) Line 9 prints "values added: 20"
2) Line 13 prints "final result: 20". Since var is not contained within the if scope, it prints out the result from the function
3) Line 9 prints "values added: 20"
4) Line 13 will throw an error since the variable is only defined within the if scope due to it having the let keyword. The program will not store result beyond the scope and thus when referenced out of the scope it will throw an error
5) Line 9 will throw an error since the variable has the const keyword indicating that once it is initialized it cannot be initialized again. In this case, we initialize the variable in Line 5 when we state result = 0. Once this declaration occurs, we cannot redeclare the variable. This is the case in line 7, where we redeclare the value of result, thus throwing an error in Line 9 and not giving us an output
6) Similar to answer 4, irregardless of if an error occurs prior to it or not, Line 13 will throw an error since the variable is only defined within the if scope due to it having the const keyword. The program doesn't a result beyond this scope, so when it is referenced out of the scope it is bound to throw an error. 
