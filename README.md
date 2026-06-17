# Nested Loops Demonstration in C++

A beginner-friendly C++ program demonstrating the use of **nested `for` loops**.

This project helps beginners understand how one loop can be placed inside another loop to perform repeated iterations and generate structured output patterns.

---

## 📌 Features

* Demonstrates nested `for` loops
* Uses an outer loop and an inner loop
* Prints loop iteration values
* Shows how nested loops execute step-by-step
* Beginner-friendly and easy to understand

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)

---

## 📂 Program Logic

The program:

1. Sets `N = 10`
2. Uses an outer loop (`i`) that runs from `0` to `10`
3. Prints the current value of `i`
4. Uses an inner loop (`j`) that runs from `0` to `10`
5. Prints all values of `j` for every iteration of `i`

This demonstrates how the inner loop executes completely for each iteration of the outer loop.

---

## 📸 Screenshot

<img width="1083" height="352" alt="image" src="https://github.com/user-attachments/assets/2e537a37-50e4-4f1e-bb5b-9cb58bc14cad" />

Example folder structure:

```txt
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp
#include<iostream>
using namespace std;

int main() {

    int N = 10;

    for (int i = 0; i <= N; i++) {

        cout << endl;
        cout << "i = " << i << endl;

        for (int j = 0; j <= N; j++) {
            cout << j << " ";
        }
    }

    return 0;
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash
g++ main.cpp -o main
```

2. Run the executable:

```bash
./main
```

---

## 📸 Example Output

```txt
i = 0
0 1 2 3 4 5 6 7 8 9 10

i = 1
0 1 2 3 4 5 6 7 8 9 10

i = 2
0 1 2 3 4 5 6 7 8 9 10

...
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* Nested loops
* Outer and inner loop execution
* Iteration control
* Loop variables
* Time complexity basics
* Console output formatting

---

## 🔍 Understanding Nested Loops

The outer loop:

```cpp
for (int i = 0; i <= N; i++)
```

controls how many times the inner loop runs.

The inner loop:

```cpp
for (int j = 0; j <= N; j++)
```

executes completely during every iteration of the outer loop.

As a result, the numbers `0` through `10` are printed **11 times**, once for each value of `i`.

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning nested loops and iteration concepts.
