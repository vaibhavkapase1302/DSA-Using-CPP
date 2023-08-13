# DSA-Using-CPP


GPT Prompt:
<a href="https://chat.openai.com/share/36a36e96-f59d-4d1f-9aaa-43b1540dd688">DSA-Using-C++</a

Introduction to Basic Data Types in C++ with Output

```C++
#include <iostream>

using namespace std;

int main()
{
    // Declare and initialize an integer variable
    int a = 5;
    cout << "Value of a is: " << a << endl;

    // Declare and initialize a character variable
    char ch = 'v';
    cout << "Value of ch is: " << ch << endl;

    // Declare and initialize a boolean variable
    bool flag = true;
    cout << "Value of flag is: " << boolalpha << flag << endl;

    // Declare and initialize a floating-point variable
    float b = 2.5;
    cout << "Value of b is: " << b << endl;

    // Declare and initialize a double precision floating-point variable
    double c = 225555;
    cout << "Value of c is: " << c << endl;

    // Declare and initialize a long integer variable
    long d = 224424244;
    cout << "Value of d is: " << d << endl;

    return 0;
}
```

Output:

```C++
value of a is : 5
value of ch is :v
value of flag is:1
value of b is:2.5
value of c is:225555
value of d is:224424244
```


Exploring the Size of a bool Variable in C++

```C++
#include <iostream>

using namespace std;

int main()
{
    // Declare and initialize a bool variable
    bool a = true;  // true or false

    // Display the size (in bytes) of the bool variable
    cout << "Size of 'a' is: " << sizeof(a) << " bytes" << endl;

    return 0;
}
```

Output:

```C++
1
```


