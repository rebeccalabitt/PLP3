# PLP3

Discussion questions:
1. What are the naming requirements for variables in your language?
  The naming requirments for Python are as follows. Variables names have to begin with an underscore or a letter, and the rest of the name can have letters and/or numbers, and they are case sensitive. It's also good practice to avoid using a lowercase "L" (l) and an uppercase "O" ('o' as in 'octopus') because they look like one's and zeroes. https://thehelloworldprogram.com/python/python-variable-assignment-statements-rules-conventions-naming/
2. What about naming conventions? Are they enforced by the compiler/interpreter, or are they just standards in the community?
  They are standards in the community.
3. Is your language statically or dynamically typed?
  It is dynamically typed because the variables can be any type.
  https://www.tutorialspoint.com/why-python-is-called-dynamically-typed#:~:text=Python%20don't%20have%20any,the%20runtime%20of%20the%20program.&text=So%2C%20Python%20is%20a%20dynamically%20typed%20language.
4. Strongly typed or weakly typed?
  Python is strongly typed because the value doesn't change in an unexpected way. https://stackoverflow.com/questions/11328920/is-python-strongly-typed
5. If you put this line (or something similar) in a program and try to print x, what does it
do? If it doesn't compile, why? Is there something you can do to make it compile? x = "5" + 6
  File "/Users/Rebecca/PycharmProjects/PLP#1/PLP3.py", line 2
    int x="5"+6:
        ^
SyntaxError: invalid syntax
6. Describe the limitations (or lack thereof) of your programming language as they relate to the coding portion of the assignment (adding ints and floats, storing different types in lists, etc). Are there other restrictions or pitfalls that the documentation mentions that you need to be aware of?
7. How do type conversions work in your language? Are the conversions narrowing or widening, and do they work by default or do they have to be declared by the programmer?
  There are two types of type conversion in Python, implicit and explicit type conversion. Implicit is default, and explicit has to be declared by the programmmer.
  https://www.programiz.com/python-programming/type-conversion-and-casting
