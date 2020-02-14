#### Background 
I have learned Python for one week, so I only know it a little. Next, I would like to share with you how I solved the problem.
#### Problem
The problem said that you design a program to first ask who you are, and then allow you to input your name. If the input name not your name, that the program will continue to ask you who you are, and let you input your name. When you input your name correctly, he will let you input the password. If the password is not correct, he will be back to ask your name at the beginning. If the password is proper, it will show that access granted. 
#### Code
~~~
while True:
	print('Who are you?')
	name=input()
	if name!='Joe':
		continue
	print('Hello, Joe. What is the password?')
	password=input()
	if password=='12345':
		break
print('Access granted.')
~~~

#### Process
First,  if you enter a name other than Joe, the continue statement returns the program to the beginning of the loop. Let you type in your name again. If you type in the name Joe, the program will ask you for a password. If the password is "12345", the break statement executes a loop that breaks out of the while and prints “Access granted”.
Of course, the process of writing the code is not very smooth. sometimes a colon is missed and the entire program will report an error. For example, if name!='Joe'
If I wrote this wrong code, the program will report an error which is called invalid syntax. Then, I will record the reason to correct codes.
