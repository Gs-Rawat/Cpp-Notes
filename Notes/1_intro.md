# Introudction

C++ is a middle level language, which is close to the hardware. And can be used for low level programming.

Here's a simple hello world program in c++

```c++
  #include <iostream>

  int main() { // this is the main function it is the starting point of the program
    std::cout << "hello world";
    return 0;
  }
```

---

## Here's the explanation of the above code

The first line that you see i.e #include \<iostream\> can be broken down into two pieces.

> **#include \<iostream>**

1. **\#include** : it is a preprocessor directive which tells preprocessor to include the header file i.e is iostream which is the next part of this line.
2. **\<iostream\>** : This is the header file which we are going to include in the program which contains the prototype of the functions which we are going to use in the program. for eg: the cout is defined in the iostream.

---
>**int main() {**

Now the next line which is **int main()** is the starting point of the program. From here the execution of your program starts. It's  actually a function. Again you can break it into two parts _int_ and _main()_. **int** is the return type of the function and **main** is the name of the function and the braces i.e () around the main shows that it is a function. Now the next thing i.e is curly brace { is from where the body of the function start. Body means what would the function do or whatever we want to make it to do we write that it in the body. **Here we want to make it display hello world on the screen.** and the ending curly brace i.e } shows that this is the end of the body of this function.

---
>**std::cout << "hello world";**

The first statement that you see std::cout is a object which will help you to display the string at the monitor. And the next statement << is a insertion operator for the time being think of it like a pipe or a bridge which will help you to pass or insert your text to cout and then cout will display it to monitor. And in the last we write the text that we want to display to monitor inside double quotes. It's necessay to write text inside double quotes(" "). and in the last we write semicolon --> ;. which tells the compiler that it's the end of this whole statement.

---
>**return 0;**

This is the last statement of our main function body, do you remember that the return type of the main function is of integer type which i told in the int main section. so that's why before ending the main function we must return the integer value and we do that by returning some integer value, and here we are returning the 0 which is indeed an integer.
**More on 0**
0 is the exit code which is widely accepted which tells that your program executed successfully. Here we are returning 0 the operating system which invoked our program.

---
**PS:** I know there are lot of things which are left to cover for example the **std::** part. Don't worry i will cover them in future topic. If you find any mistake or typo feel free to leave a message.
