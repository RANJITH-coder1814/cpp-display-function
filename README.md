# C++ Hello World Using Function

This repository contains a simple C++ program that prints **Hello World** using a user-defined function.

## 📌 Program Explanation
- A function `display()` is defined to print a message.
- The `main()` function calls `display()`.
- Demonstrates basic function usage in C++.

## 💻 Source Code

```cpp
#include<iostream>
using namespace std;

void display() {
    cout << "hello world";
}

int main() {
    display();
    return 0;
}
