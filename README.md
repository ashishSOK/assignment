# assignment
Let's go through the questions from your screenshot one by one:

✅ Q1: How can you output “Physics” and “Wallah” in two different lines in C++?
cpp
Copy
Edit
#include <iostream>
using namespace std;

int main() {
    cout << "Physics" << endl;
    cout << "Wallah" << endl;
    return 0;
}
✅ Q2: Write a program to print 10 using 2 positive numbers less than 6 in C++ as output.
Example:

cpp
Copy
Edit
#include <iostream>
using namespace std;

int main() {
    int a = 4, b = 6;
    cout << a + b;  // 4 + 6 = 10
    return 0;
}
Or:

cpp
Copy
Edit
int a = 5, b = 5;
cout << a + b;
✅ Q3: How much space do the following data types take?
(Size may vary by system, but typical for most 64-bit systems)

int → 4 bytes

bool → 1 byte

float → 4 bytes

✅ Q4: What is the output of this program?
cpp
Copy
Edit
int main() {
    int a = 4;
    int b = 5;
    a++;    // a becomes 5
    b--;    // b becomes 4
    cout << ++a << " " << b--;
}
Step-by-step:

a = 4 → a++ → 5

b = 5 → b-- → 4

++a → pre-increment → a becomes 6

b-- → post-decrement → prints 4, then b becomes 3

Output:

Copy
Edit
6 4
✅ Q5: Write a program to find the circumference of a circle with radius 10 in C++.
cpp
Copy
Edit
#include <iostream>
using namespace std;

int main() {
    float radius = 10;
    float circumference = 2 * 3.14 * radius;
    cout << "Circumference = " << circumference;
    return 0;
}
✅ Q6: How many of these can be a variable name?
Let’s check each:

01Pwskills ❌ Invalid (cannot start with digit)

_FLOAT ✅ Valid

int ❌ Invalid (C++ keyword)

FLOAT ✅ Valid

You will succeed ❌ Invalid (contains spaces)

Answer: 2 (_FLOAT, FLOAT)

