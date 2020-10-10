# Specifying Variable types simple aka Casting

Converting Data types comes in very handy when writting python code. It allows you to take a users input and conver it to a data type that python can process and than spit out. you can also convert python data types to take output from the code and convert it to a readable/ [printable](2-Print.md) format. 

### How it is done 
an example of how it can be used is in a simple calulator.
```python
num1 = input('Your First number: ')
num2 = input('Your Second number: ')
 
x = int(num1) + int(num2)
print(str(x))
```
While it is not neccecary to have "str()" in the print command as python can print out int's with no problem, It is advised to have it there to prevent any potential issues that may arise.

Next to read: [](), News and updates about this tutorial: [The Readme file](../README.md)