#Question - 2

Alice has a machine which stopped working, your job is to create a machine for alice which does the same operations.

the machine take 3 inputs:

Q : Number of queries

X : array of operations

P : array of parameters for operation

the operations that the machine does are :

'1' : insert into parameter value into array.

'2' : remove all occurance of parameter value.

'3' : XOR parameter value will all the elements in the array and sum and display.

assumptions:
- initally the array of the machine is empty[]
- there is aleast one '3' operation
- size of X and P are same

eg:
input :
3
1 1 3
4 5 6

output: 
5

explaination: 
- first operation is '1' with parameter '4', so insert '4' into array.
- array = [4]
- 2nd operation is '1' with parameter '5', so insert '5' into array.
- array = [4, 5]
- 3rd operation is '3' with parameter '6', so (4^6 + 5^6) = (2 + 3) = 5




Hint for optimal solution :
operation '2' remove all occurance of the parameter so any insert operation can be removed.

