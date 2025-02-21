# Variables
Think of a variable as a box to store information. They can hold different types, such as strings, integers, lists, etc.
Usually, you have to __define__ a variable before you can use it. Here is an example of defining a variable in Python:  

  __↓__ This is the __name__ of the variable  
`foo = "Hello World!"`  
This is its __value ↑__

In most languages, (Java, C#, C++, Swift, etc.) you have to define the variable type.  
`int foo = 5`  
And if you don't quite know the type yet, you can usually use `var` instead of the type. But keep in mind this may make the code slower.

You can also change the value of a variable later.  
```
int foo = 1

foo = 12
```  
But keep in mind that in most cases you will get an error if you try to change the variable type.

## Accessing variables
Using variables in your code is quite simple. Just use the name.  
```
message = "Hello World!"

print(message)


output: Hello World!
```
