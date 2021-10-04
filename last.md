 # Now, I'd like to have a short tutorial on C++
 1. Q: What is C++? <br />
    A: C++ is a __statically typed__, __compiled__, __general-purpose__, __case-sensitive__, __free-form__ programming language 
    that supports **procedural**, **object-oriented**, and **generic programming**.   
 2. Q: What to know about C++ for a beginner? <br />
    A: Click the link provided to get more information
    1. **Basic Syntax** :point_right: https://www.tutorialspoint.com/cprogramming/c_basic_syntax.htm.
    2. **Data Type** :point_right: https://www.tutorialspoint.com/cprogramming/c_data_types.htm
    3. **Data Structure and Algorithm** This is the most important thing.
  
  After learing fundanmental knowledge of C++, Let's look at "Hello Word" example:
```ruby
#include <iostream>

using namespace std;

int main() {
  // add codes below
  cout << "Hello World!" << endl;
  
  return 0;
}
```
```ruby
#include <iostream>

int main() {
   // add codes below
   std:: cout <<  "Hello Qiqi Hu" << std:: endl; 

    return 0;
}
```
Compare above two coding, having "using namespace std;" makes the code easier.<br />
Let us take a look at the various parts of the above program:

- [ ]  **#include** <iostream> is a preprocessor command, which tells a C compiler to include **iostream** file before going to actual compilation.

- [ ]  **int main()** is the main function where the program execution begins.

- [ ] **//** called comments will be ignored by the compiler and it has been put to add additional comments in the program. 

- [ ] **cout<< ... <<endl;** is another function available in C which causes the message **"Hello, World!"** to be displayed on the screen.

- [ ]  **return 0;** terminates the main() function and returns the value 0.
  
# It is the end of the page, hope you like this briefly tutorial on C++.
