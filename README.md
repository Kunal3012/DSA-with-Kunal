# DSA with Kunal
A comprehensive tutorial on Data Structures and Algorithms (DSA) implemented in C, C++, Java, and Python. Perfect for students and developers who want to learn and practice DSA in multiple programming languages.

This repository contains implementations of various Data Structures and Algorithms (DSA) across four popular programming languages:
- **C**
- **C++**
- **Java**
- **Python**

### What's Covered:
- Arrays
- Linked Lists
- Stacks
- Queues
- Trees
- Graphs
- Sorting and Searching Algorithms

# Approach
To learn Data Structures and Algorithms (DSA) in C, C++, Java, and Python together, here's an approach you can follow:

### Step-by-Step Approach

1. **Start with Basics**:
   - **Understand fundamental data structures**: Arrays, linked lists, stacks, queues, hash maps, trees, graphs.
   - Learn how to implement these in each language (C, C++, Java, Python).

2. **Language Syntax Overview**:
   - **C**: Focus on manual memory management, pointers, and structures.
   - **C++**: Use classes for implementing data structures, and STL for ready-made implementations.
   - **Java**: Use its rich libraries, but implement custom data structures manually.
   - **Python**: Focus on simplicity and built-in data structures like lists, dictionaries, and sets.

3. **Algorithms**:
   - **Sorting & Searching**: Implement algorithms like Bubble Sort, Quick Sort, Binary Search.
   - **Recursion**: Practice recursive problems such as Fibonacci sequence, Tower of Hanoi.
   - **Dynamic Programming**: Learn memoization and tabulation techniques.
   - **Graph Algorithms**: BFS, DFS, Dijkstra, etc.

4. **Solve Problems**:
   - Start solving basic problems in each language. Websites like **LeetCode**, **HackerRank**, and **GeeksforGeeks** offer DSA problems in all four languages.

5. **Parallel Practice**:
   - For every data structure or algorithm, write code in all four languages to solidify your understanding of their similarities and differences.

# Data Types
Here is a comparison of basic data types across **C**, **C++**, **Java**, and **Python**:

### 1. **C Data Types**
| **Data Type** | **Size (bytes)** | **Range** |
|---------------|------------------|-----------|
| `int`         | 2 or 4           | -32,768 to 32,767 (2 bytes), -2,147,483,648 to 2,147,483,647 (4 bytes) |
| `float`       | 4                | 3.4E-38 to 3.4E+38 |
| `double`      | 8                | 1.7E-308 to 1.7E+308 |
| `char`        | 1                | -128 to 127 or 0 to 255 |
| `void`        | 0                | No value |
| `short`       | 2                | -32,768 to 32,767 |
| `long`        | 4 or 8           | -2,147,483,648 to 2,147,483,647 (4 bytes), larger range for 8 bytes |
| `unsigned int`| 2 or 4           | 0 to 65,535 (2 bytes), 0 to 4,294,967,295 (4 bytes) |

### 2. **C++ Data Types**
| **Data Type** | **Size (bytes)** | **Range** |
|---------------|------------------|-----------|
| `int`         | 4                | -2,147,483,648 to 2,147,483,647 |
| `float`       | 4                | 3.4E-38 to 3.4E+38 |
| `double`      | 8                | 1.7E-308 to 1.7E+308 |
| `char`        | 1                | -128 to 127 or 0 to 255 |
| `bool`        | 1                | true (1) or false (0) |
| `void`        | 0                | No value |
| `short`       | 2                | -32,768 to 32,767 |
| `long`        | 8                | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
| `unsigned int`| 4                | 0 to 4,294,967,295 |

### 3. **Java Data Types**
| **Data Type** | **Size (bytes)** | **Range** |
|---------------|------------------|-----------|
| `byte`        | 1                | -128 to 127 |
| `short`       | 2                | -32,768 to 32,767 |
| `int`         | 4                | -2,147,483,648 to 2,147,483,647 |
| `long`        | 8                | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
| `float`       | 4                | 3.4E-45 to 3.4E+38 |
| `double`      | 8                | 1.7E-308 to 1.7E+308 |
| `char`        | 2                | 0 to 65,535 (represents Unicode characters) |
| `boolean`     | 1 bit            | true or false |

### 4. **Python Data Types**
| **Data Type**  | **Description** | **Example**              |
|----------------|-----------------|--------------------------|
| `int`          | Integer (unlimited precision) | `x = 10`              |
| `float`        | Floating-point number | `x = 10.5`            |
| `complex`      | Complex number | `x = 3 + 4j`               |
| `str`          | String          | `x = "Hello"`             |
| `bool`         | Boolean         | `x = True` or `x = False` |
| `list`         | Mutable sequence | `x = [1, 2, 3]`          |
| `tuple`        | Immutable sequence | `x = (1, 2, 3)`         |
| `dict`         | Key-value pairs | `x = {'a': 1, 'b': 2}`    |
| `set`          | Unordered collection | `x = {1, 2, 3}`       |

Each language has its own strengths in terms of data types. **C/C++** offer lower-level control with primitive types, while **Java** and **Python** focus on abstraction and ease of use with built-in data types.

# Arrays
Here's a comparison of **arrays** and similar structures in **C**, **C++**, **Java**, and **Python**, along with differences between their types.

### 1. **C Arrays**
   - **Definition**: Fixed-size collection of elements of the same type.
   - **Declaration**: `int arr[5];`
   - **Features**: 
     - Static memory allocation.
     - Cannot change size at runtime.
     - No built-in methods for operations like sorting or searching.

| **Operation**        | **Example**            |
|----------------------|------------------------|
| Declaration          | `int arr[5];`          |
| Access element       | `arr[2] = 10;`         |
| Iterate              | `for(int i = 0; i < 5; i++)` |

### 2. **C++ Arrays and Vectors**
   - **Array (Fixed Size)**: Same as C arrays.
     - `int arr[5];`
   - **Vector (Dynamic Size)**: `std::vector<int> v;`
     - Dynamic size, can grow or shrink during runtime.
     - Part of the STL (Standard Template Library).

| **Operation**        | **C++ Array**          | **C++ Vector**            |
|----------------------|------------------------|---------------------------|
| Declaration          | `int arr[5];`          | `std::vector<int> v;`     |
| Access element       | `arr[2] = 10;`         | `v.push_back(10);`        |
| Iterate              | `for(int i = 0; i < 5; i++)` | `for(auto i : v)`    |
| Resize               | N/A                    | `v.resize(10);`           |

### 3. **Java Arrays and Vectors**
   - **Array**: Fixed-size, static data structure.
     - `int[] arr = new int[5];`
   - **Vector (from java.util.Vector)**: Dynamic-size array-like data structure.
     - `Vector<Integer> v = new Vector<>();`
   - **ArrayList (java.util.ArrayList)**: More commonly used, dynamic array implementation.
     - `ArrayList<Integer> arrList = new ArrayList<>();`

| **Operation**        | **Java Array**          | **Java Vector/ArrayList**       |
|----------------------|-------------------------|----------------------------------|
| Declaration          | `int[] arr = new int[5];`| `Vector<Integer> v = new Vector<>();` |
| Access element       | `arr[2] = 10;`          | `v.add(10);`                    |
| Iterate              | `for(int i = 0; i < arr.length; i++)` | `for(Integer i : v)` |
| Resize               | N/A                     | Automatically resizes when elements are added. |

#### **Differences between Java Array and Vector/ArrayList**:
- **Array**:
  - Fixed size.
  - Can hold primitive data types.
- **Vector/ArrayList**:
  - Dynamic size.
  - Only holds object references (e.g., `Integer`, not `int`).
  - Provides built-in methods like `add()`, `remove()`, `size()`.

### 4. **Python Arrays and Numpy Arrays**
   - **Array (from array module)**: Fixed-size, can store only basic types (like int, float).
     - `import array`
     - `arr = array.array('i', [1, 2, 3])` (where `'i'` indicates integer array)
   - **List (Python’s built-in)**: Dynamic-size array-like structure, more commonly used.
     - `arr = [1, 2, 3]`
   - **Numpy Array (from numpy module)**: Multi-dimensional, optimized for numerical operations.
     - `import numpy as np`
     - `arr = np.array([1, 2, 3])`

| **Operation**        | **Python Array**        | **Python List**            | **Numpy Array**             |
|----------------------|-------------------------|----------------------------|-----------------------------|
| Declaration          | `import array`          | `arr = [1, 2, 3]`          | `arr = np.array([1, 2, 3])` |
| Access element       | `arr[2] = 10;`          | `arr[2] = 10`              | `arr[2] = 10`               |
| Iterate              | `for i in arr:`         | `for i in arr:`            | `for i in arr:`             |
| Resize               | Fixed size              | Dynamic                    | Supports reshaping          |
| Multi-dimensional    | No                      | Yes (lists of lists)       | Yes                         |
| Numerical operations | No                      | No                         | Highly optimized for math   |

#### **Differences between Python List, array, and Numpy Array**:
- **Python Array (from array module)**:
  - Stores basic types (e.g., int, float).
  - Not frequently used.
- **Python List**:
  - Flexible, dynamic-size container.
  - Stores any object type.
  - Slower than numpy for large numerical operations.
- **Numpy Array**:
  - Optimized for numerical calculations.
  - Supports multi-dimensional arrays.
  - Offers powerful operations like matrix multiplication, slicing, broadcasting, etc.

### Summary of Key Differences:
| **Language** | **Array Type**                  | **Fixed/Dynamic Size** | **Key Features**                               |
|--------------|----------------------------------|------------------------|------------------------------------------------|
| C            | `int arr[5];`                   | Fixed                  | Low-level access, fixed memory allocation.     |
| C++          | `std::vector<int>`              | Dynamic                | Part of STL, rich functionality.               |
| Java         | `int[] arr`, `ArrayList`        | Fixed (Array), Dynamic (ArrayList) | ArrayList provides flexible sizing. |
| Python       | `array`, `list`, `numpy.array`  | Fixed (`array`), Dynamic (`list`, `numpy`) | Numpy for high-performance numerical operations. |



Here’s how you can perform **CRUD (Create, Read, Update, Delete)** operations on arrays, vectors, and lists in **C**, **C++**, **Java**, and **Python**, including the **Numpy array** and **Java Vector**.

### 1. **C Arrays CRUD Operations**

#### Create
```c
int arr[5] = {1, 2, 3, 4, 5};  // Fixed size
```

#### Read
```c
int value = arr[2];  // Access the 3rd element
```

#### Update
```c
arr[2] = 10;  // Modify the 3rd element
```

#### Delete
In C, you cannot delete individual elements from a static array, but you can overwrite them:
```c
arr[2] = 0;  // Overwrite the 3rd element
```

### 2. **C++ Arrays and Vectors CRUD Operations**

#### **C++ Array CRUD**

#### Create
```cpp
int arr[5] = {1, 2, 3, 4, 5};  // Fixed size
```

#### Read
```cpp
int value = arr[2];  // Access the 3rd element
```

#### Update
```cpp
arr[2] = 10;  // Modify the 3rd element
```

#### Delete
You cannot delete elements, but you can overwrite:
```cpp
arr[2] = 0;  // Overwrite the 3rd element
```

#### **C++ Vector CRUD**

#### Create
```cpp
#include <vector>
std::vector<int> v = {1, 2, 3, 4, 5};  // Dynamic size
```

#### Read
```cpp
int value = v[2];  // Access the 3rd element
```

#### Update
```cpp
v[2] = 10;  // Modify the 3rd element
```

#### Delete
```cpp
v.erase(v.begin() + 2);  // Delete the 3rd element
```

### 3. **Java Arrays and Vectors CRUD Operations**

#### **Java Array CRUD**

#### Create
```java
int[] arr = {1, 2, 3, 4, 5};  // Fixed size
```

#### Read
```java
int value = arr[2];  // Access the 3rd element
```

#### Update
```java
arr[2] = 10;  // Modify the 3rd element
```

#### Delete
Java arrays are of fixed size, so deletion is not supported. You can only overwrite:
```java
arr[2] = 0;  // Overwrite the 3rd element
```

#### **Java Vector CRUD**

#### Create
```java
import java.util.Vector;
Vector<Integer> vector = new Vector<>(Arrays.asList(1, 2, 3, 4, 5));
```

#### Read
```java
int value = vector.get(2);  // Access the 3rd element
```

#### Update
```java
vector.set(2, 10);  // Modify the 3rd element
```

#### Delete
```java
vector.remove(2);  // Remove the 3rd element
```

### 4. **Python Arrays, Lists, and Numpy Arrays CRUD Operations**

#### **Python array (from array module) CRUD**

#### Create
```python
import array
arr = array.array('i', [1, 2, 3, 4, 5])  # 'i' stands for integer
```

#### Read
```python
value = arr[2]  # Access the 3rd element
```

#### Update
```python
arr[2] = 10  # Modify the 3rd element
```

#### Delete
```python
arr.remove(3)  # Remove the element with value 3
```

#### **Python List CRUD**

#### Create
```python
arr = [1, 2, 3, 4, 5]  # Dynamic size
```

#### Read
```python
value = arr[2]  # Access the 3rd element
```

#### Update
```python
arr[2] = 10  # Modify the 3rd element
```

#### Delete
```python
arr.pop(2)  # Remove the 3rd element
```

#### **Numpy Array CRUD**

#### Create
```python
import numpy as np
arr = np.array([1, 2, 3, 4, 5])  // Dynamic, optimized for numerical operations
```

#### Read
```python
value = arr[2]  # Access the 3rd element
```

#### Update
```python
arr[2] = 10  # Modify the 3rd element
```

#### Delete
```python
arr = np.delete(arr, 2)  # Remove the 3rd element
```

### Summary of CRUD Operations for Each Data Structure:

| **Language**   | **Array/Vector**   | **Create**                     | **Read**             | **Update**            | **Delete**              |
|----------------|--------------------|---------------------------------|----------------------|-----------------------|-------------------------|
| **C**          | Array               | `int arr[5] = {1, 2, 3, 4, 5};`| `arr[2]`             | `arr[2] = 10`         | Overwrite (`arr[2] = 0`)|
| **C++**        | Array               | `int arr[5] = {1, 2, 3, 4, 5};`| `arr[2]`             | `arr[2] = 10`         | Overwrite (`arr[2] = 0`)|
| **C++**        | Vector              | `std::vector<int> v = {1, 2, 3};`| `v[2]`             | `v[2] = 10`           | `v.erase(v.begin() + 2)`|
| **Java**       | Array               | `int[] arr = {1, 2, 3, 4, 5};`  | `arr[2]`             | `arr[2] = 10`         | Overwrite (`arr[2] = 0`)|
| **Java**       | Vector              | `Vector<Integer> v = new Vector<>();` | `v.get(2)`    | `v.set(2, 10)`        | `v.remove(2)`            |
| **Python**     | array (module)      | `arr = array.array('i', [1, 2, 3])` | `arr[2]`         | `arr[2] = 10`         | `arr.remove(3)`          |
| **Python**     | List                | `arr = [1, 2, 3, 4, 5]`         | `arr[2]`             | `arr[2] = 10`         | `arr.pop(2)`             |
| **Python**     | Numpy Array         | `arr = np.array([1, 2, 3])`     | `arr[2]`             | `arr[2] = 10`         | `arr = np.delete(arr, 2)`|



# Searching alorithms


Here are various searching algorithms implemented in **C**, **C++**, **Java**, and **Python**, along with their code. We'll cover **Linear Search** and **Binary Search** as they are the most fundamental.

### 1. **Linear Search**

#### **Algorithm**: 
In linear search, we sequentially check each element in the array until we find the target element or reach the end.

#### **Time Complexity**: O(n)

#### **C Code: Linear Search**
```c
#include <stdio.h>

int linearSearch(int arr[], int n, int x) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == x)
            return i;  // Return the index of the found element
    }
    return -1;  // Return -1 if not found
}

int main() {
    int arr[] = {2, 4, 0, 1, 9};
    int x = 1;
    int n = sizeof(arr) / sizeof(arr[0]);
    int result = linearSearch(arr, n, x);
    if(result == -1)
        printf("Element not found");
    else
        printf("Element found at index %d", result);
    return 0;
}
```

#### **C++ Code: Linear Search**
```cpp
#include <iostream>
using namespace std;

int linearSearch(int arr[], int n, int x) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == x)
            return i;
    }
    return -1;
}

int main() {
    int arr[] = {2, 4, 0, 1, 9};
    int x = 1;
    int n = sizeof(arr) / sizeof(arr[0]);
    int result = linearSearch(arr, n, x);
    if (result == -1)
        cout << "Element not found" << endl;
    else
        cout << "Element found at index " << result << endl;
    return 0;
}
```

#### **Java Code: Linear Search**
```java
public class LinearSearch {
    public static int linearSearch(int[] arr, int x) {
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] == x)
                return i;
        }
        return -1;
    }

    public static void main(String[] args) {
        int[] arr = {2, 4, 0, 1, 9};
        int x = 1;
        int result = linearSearch(arr, x);
        if (result == -1)
            System.out.println("Element not found");
        else
            System.out.println("Element found at index " + result);
    }
}
```

#### **Python Code: Linear Search**
```python
def linear_search(arr, x):
    for i in range(len(arr)):
        if arr[i] == x:
            return i
    return -1

arr = [2, 4, 0, 1, 9]
x = 1
result = linear_search(arr, x)
if result == -1:
    print("Element not found")
else:
    print(f"Element found at index {result}")
```

---

### 2. **Binary Search**

#### **Algorithm**: 
Binary search is a divide-and-conquer algorithm where we repeatedly divide the array in half and check if the target element is in the left or right half. It works only on sorted arrays.

#### **Time Complexity**: O(log n)

#### **C Code: Binary Search**
```c
#include <stdio.h>

int binarySearch(int arr[], int left, int right, int x) {
    while (left <= right) {
        int mid = left + (right - left) / 2;

        // Check if x is present at mid
        if (arr[mid] == x)
            return mid;

        // If x greater, ignore left half
        if (arr[mid] < x)
            left = mid + 1;

        // If x is smaller, ignore right half
        else
            right = mid - 1;
    }
    return -1;  // Element is not present
}

int main() {
    int arr[] = {1, 2, 4, 5, 9};
    int n = sizeof(arr) / sizeof(arr[0]);
    int x = 5;
    int result = binarySearch(arr, 0, n - 1, x);
    if (result == -1)
        printf("Element not found");
    else
        printf("Element found at index %d", result);
    return 0;
}
```

#### **C++ Code: Binary Search**
```cpp
#include <iostream>
using namespace std;

int binarySearch(int arr[], int left, int right, int x) {
    while (left <= right) {
        int mid = left + (right - left) / 2;

        if (arr[mid] == x)
            return mid;

        if (arr[mid] < x)
            left = mid + 1;
        else
            right = mid - 1;
    }
    return -1;
}

int main() {
    int arr[] = {1, 2, 4, 5, 9};
    int n = sizeof(arr) / sizeof(arr[0]);
    int x = 5;
    int result = binarySearch(arr, 0, n - 1, x);
    if (result == -1)
        cout << "Element not found" << endl;
    else
        cout << "Element found at index " << result << endl;
    return 0;
}
```

#### **Java Code: Binary Search**
```java
public class BinarySearch {
    public static int binarySearch(int[] arr, int x) {
        int left = 0, right = arr.length - 1;
        while (left <= right) {
            int mid = left + (right - left) / 2;

            if (arr[mid] == x)
                return mid;

            if (arr[mid] < x)
                left = mid + 1;
            else
                right = mid - 1;
        }
        return -1;
    }

    public static void main(String[] args) {
        int[] arr = {1, 2, 4, 5, 9};
        int x = 5;
        int result = binarySearch(arr, x);
        if (result == -1)
            System.out.println("Element not found");
        else
            System.out.println("Element found at index " + result);
    }
}
```

#### **Python Code: Binary Search**
```python
def binary_search(arr, x):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = left + (right - left) // 2

        if arr[mid] == x:
            return mid
        elif arr[mid] < x:
            left = mid + 1
        else:
            right = mid - 1
    return -1

arr = [1, 2, 4, 5, 9]
x = 5
result = binary_search(arr, x)
if result == -1:
    print("Element not found")
else:
    print(f"Element found at index {result}")
```

---

### **Key Differences Between Linear Search and Binary Search**:
1. **Linear Search**:
   - **Unsorted array**: Can work on both sorted and unsorted arrays.
   - **Time complexity**: O(n).
   
2. **Binary Search**:
   - **Sorted array**: Requires the array to be sorted.
   - **Time complexity**: O(log n), much faster for large arrays.

These implementations showcase how you can implement basic searching algorithms in different programming languages. 



# Sorting


Here's a comprehensive overview of common sorting algorithms with their implementations in **C**, **C++**, **Java**, and **Python**. The algorithms covered include **Bubble Sort**, **Selection Sort**, **Insertion Sort**, **Merge Sort**, **Quick Sort**, and **Heap Sort**.

### 1. **Bubble Sort**

#### **Algorithm**: 
Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

#### **Time Complexity**: O(n^2)

#### **C Code: Bubble Sort**
```c
#include <stdio.h>

void bubbleSort(int arr[], int n) {
    for (int i = 0; i < n-1; i++) {
        for (int j = 0; j < n-i-1; j++) {
            if (arr[j] > arr[j+1]) {
                // Swap
                int temp = arr[j];
                arr[j] = arr[j+1];
                arr[j+1] = temp;
            }
        }
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    bubbleSort(arr, n);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Bubble Sort**
```cpp
#include <iostream>
using namespace std;

void bubbleSort(int arr[], int n) {
    for (int i = 0; i < n-1; i++) {
        for (int j = 0; j < n-i-1; j++) {
            if (arr[j] > arr[j+1]) {
                // Swap
                swap(arr[j], arr[j+1]);
            }
        }
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    bubbleSort(arr, n);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Bubble Sort**
```java
public class BubbleSort {
    public static void bubbleSort(int[] arr) {
        int n = arr.length;
        for (int i = 0; i < n-1; i++) {
            for (int j = 0; j < n-i-1; j++) {
                if (arr[j] > arr[j+1]) {
                    // Swap
                    int temp = arr[j];
                    arr[j] = arr[j+1];
                    arr[j+1] = temp;
                }
            }
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        bubbleSort(arr);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Bubble Sort**
```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n-1):
        for j in range(n-i-1):
            if arr[j] > arr[j+1]:
                # Swap
                arr[j], arr[j+1] = arr[j+1], arr[j]

arr = [64, 34, 25, 12, 22]
bubble_sort(arr)
print("Sorted array:", arr)
```

---

### 2. **Selection Sort**

#### **Algorithm**: 
Divides the input list into two parts: a sorted and an unsorted sublist, repeatedly selecting the smallest (or largest) element from the unsorted sublist and moving it to the sorted sublist.

#### **Time Complexity**: O(n^2)

#### **C Code: Selection Sort**
```c
#include <stdio.h>

void selectionSort(int arr[], int n) {
    for (int i = 0; i < n-1; i++) {
        int min_idx = i;
        for (int j = i+1; j < n; j++) {
            if (arr[j] < arr[min_idx])
                min_idx = j;
        }
        // Swap
        int temp = arr[min_idx];
        arr[min_idx] = arr[i];
        arr[i] = temp;
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    selectionSort(arr, n);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Selection Sort**
```cpp
#include <iostream>
using namespace std;

void selectionSort(int arr[], int n) {
    for (int i = 0; i < n-1; i++) {
        int min_idx = i;
        for (int j = i+1; j < n; j++) {
            if (arr[j] < arr[min_idx])
                min_idx = j;
        }
        // Swap
        swap(arr[min_idx], arr[i]);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    selectionSort(arr, n);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Selection Sort**
```java
public class SelectionSort {
    public static void selectionSort(int[] arr) {
        int n = arr.length;
        for (int i = 0; i < n-1; i++) {
            int min_idx = i;
            for (int j = i+1; j < n; j++) {
                if (arr[j] < arr[min_idx])
                    min_idx = j;
            }
            // Swap
            int temp = arr[min_idx];
            arr[min_idx] = arr[i];
            arr[i] = temp;
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        selectionSort(arr);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Selection Sort**
```python
def selection_sort(arr):
    n = len(arr)
    for i in range(n-1):
        min_idx = i
        for j in range(i+1, n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        # Swap
        arr[i], arr[min_idx] = arr[min_idx], arr[i]

arr = [64, 34, 25, 12, 22]
selection_sort(arr)
print("Sorted array:", arr)
```

---

### 3. **Insertion Sort**

#### **Algorithm**: 
Builds a sorted array one element at a time by comparing and inserting each new element into its proper place.

#### **Time Complexity**: O(n^2)

#### **C Code: Insertion Sort**
```c
#include <stdio.h>

void insertionSort(int arr[], int n) {
    for (int i = 1; i < n; i++) {
        int key = arr[i];
        int j = i - 1;
        // Move elements of arr[0..i-1] that are greater than key
        while (j >= 0 && arr[j] > key) {
            arr[j + 1] = arr[j];
            j = j - 1;
        }
        arr[j + 1] = key;
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    insertionSort(arr, n);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Insertion Sort**
```cpp
#include <iostream>
using namespace std;

void insertionSort(int arr[], int n) {
    for (int i = 1; i < n; i++) {
        int key = arr[i];
        int j = i - 1;
        while (j >= 0 && arr[j] > key) {
            arr[j + 1] = arr[j];
            j--;
        }
        arr[j + 1] = key;
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    insertionSort(arr, n);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Insertion Sort**
```java
public class InsertionSort {
    public static void insertionSort(int[] arr) {
        int n = arr.length;
        for (int i = 1; i < n; i++) {
            int key = arr[i];


            int j = i - 1;
            while (j >= 0 && arr[j] > key) {
                arr[j + 1] = arr[j];
                j--;
            }
            arr[j + 1] = key;
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        insertionSort(arr);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Insertion Sort**
```python
def insertion_sort(arr):
    n = len(arr)
    for i in range(1, n):
        key = arr[i]
        j = i - 1
        while j >= 0 and arr[j] > key:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key

arr = [64, 34, 25, 12, 22]
insertion_sort(arr)
print("Sorted array:", arr)
```

---

### 4. **Merge Sort**

#### **Algorithm**: 
Divides the unsorted list into n sublists, each containing one element. Then repeatedly merges sublists to produce new sorted sublists until there is only one sublist remaining.

#### **Time Complexity**: O(n log n)

#### **C Code: Merge Sort**
```c
#include <stdio.h>

void merge(int arr[], int left, int mid, int right) {
    int n1 = mid - left + 1;
    int n2 = right - mid;
    int L[n1], R[n2];

    for (int i = 0; i < n1; i++)
        L[i] = arr[left + i];
    for (int j = 0; j < n2; j++)
        R[j] = arr[mid + 1 + j];

    int i = 0, j = 0, k = left;
    while (i < n1 && j < n2) {
        if (L[i] <= R[j]) {
            arr[k] = L[i];
            i++;
        } else {
            arr[k] = R[j];
            j++;
        }
        k++;
    }
    while (i < n1) {
        arr[k] = L[i];
        i++;
        k++;
    }
    while (j < n2) {
        arr[k] = R[j];
        j++;
        k++;
    }
}

void mergeSort(int arr[], int left, int right) {
    if (left < right) {
        int mid = left + (right - left) / 2;
        mergeSort(arr, left, mid);
        mergeSort(arr, mid + 1, right);
        merge(arr, left, mid, right);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    mergeSort(arr, 0, n - 1);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Merge Sort**
```cpp
#include <iostream>
using namespace std;

void merge(int arr[], int left, int mid, int right) {
    int n1 = mid - left + 1;
    int n2 = right - mid;
    int L[n1], R[n2];

    for (int i = 0; i < n1; i++)
        L[i] = arr[left + i];
    for (int j = 0; j < n2; j++)
        R[j] = arr[mid + 1 + j];

    int i = 0, j = 0, k = left;
    while (i < n1 && j < n2) {
        if (L[i] <= R[j]) {
            arr[k] = L[i];
            i++;
        } else {
            arr[k] = R[j];
            j++;
        }
        k++;
    }
    while (i < n1) {
        arr[k] = L[i];
        i++;
        k++;
    }
    while (j < n2) {
        arr[k] = R[j];
        j++;
        k++;
    }
}

void mergeSort(int arr[], int left, int right) {
    if (left < right) {
        int mid = left + (right - left) / 2;
        mergeSort(arr, left, mid);
        mergeSort(arr, mid + 1, right);
        merge(arr, left, mid, right);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    mergeSort(arr, 0, n - 1);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Merge Sort**
```java
public class MergeSort {
    public static void merge(int[] arr, int left, int mid, int right) {
        int n1 = mid - left + 1;
        int n2 = right - mid;
        int[] L = new int[n1];
        int[] R = new int[n2];

        for (int i = 0; i < n1; i++)
            L[i] = arr[left + i];
        for (int j = 0; j < n2; j++)
            R[j] = arr[mid + 1 + j];

        int i = 0, j = 0, k = left;
        while (i < n1 && j < n2) {
            if (L[i] <= R[j]) {
                arr[k] = L[i];
                i++;
            } else {
                arr[k] = R[j];
                j++;
            }
            k++;
        }
        while (i < n1) {
            arr[k] = L[i];
            i++;
            k++;
        }
        while (j < n2) {
            arr[k] = R[j];
            j++;
            k++;
        }
    }

    public static void mergeSort(int[] arr, int left, int right) {
        if (left < right) {
            int mid = left + (right - left) / 2;
            mergeSort(arr, left, mid);
            mergeSort(arr, mid + 1, right);
            merge(arr, left, mid, right);
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        mergeSort(arr, 0, arr.length - 1);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Merge Sort**
```python
def merge(arr, left, mid, right):
    n1 = mid - left + 1
    n2 = right - mid
    L = arr[left:left + n1]
    R = arr[mid + 1:mid + 1 + n2]

    i = j = 0
    k = left
    while i < n1 and j < n2:
        if L[i] <= R[j]:
            arr[k] = L[i]
            i += 1
        else:
            arr[k] = R[j]
            j += 1
        k += 1

    while i < n1:
        arr[k] = L[i]
        i += 1
        k += 1

    while j < n2:
        arr[k] = R[j]
        j += 1
        k += 1

def merge_sort(arr, left, right):
    if left < right:
        mid = left + (right - left) // 2
        merge_sort(arr, left, mid)
        merge_sort(arr, mid + 1, right)
        merge(arr, left, mid, right)

arr = [64, 34, 25, 12, 22]
merge_sort(arr, 0, len(arr) - 1)
print("Sorted array:", arr)
```

---

### 5. **Quick Sort**

#### **Algorithm**: 
Selects a 'pivot' element from the array and partitions the other elements into two sub-arrays according to whether they are less than or greater than the pivot.

#### **Time Complexity**: O(n log n) on average, O(n^2) in the worst case.

#### **C Code: Quick Sort**
```c
#include <stdio.h>

int partition(int arr[], int low, int high) {
    int pivot = arr[high];
    int i = (low - 1);
    for (int j = low; j < high; j++) {
        if (arr[j] < pivot) {
            i++;
            // Swap
            int temp = arr[i];
            arr[i] = arr[j];
            arr[j] = temp;
        }
    }
    // Swap pivot
    int temp = arr[i + 1];
    arr[i + 1] = arr[high];
    arr[high] = temp;
    return i + 1;
}

void quickSort(int arr[], int low, int high) {
    if (low < high) {
        int pi = partition

(arr, low, high);
        quickSort(arr, low, pi - 1);
        quickSort(arr, pi + 1, high);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    quickSort(arr, 0, n - 1);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Quick Sort**
```cpp
#include <iostream>
using namespace std;

int partition(int arr[], int low, int high) {
    int pivot = arr[high];
    int i = (low - 1);
    for (int j = low; j < high; j++) {
        if (arr[j] < pivot) {
            i++;
            // Swap
            swap(arr[i], arr[j]);
        }
    }
    // Swap pivot
    swap(arr[i + 1], arr[high]);
    return i + 1;
}

void quickSort(int arr[], int low, int high) {
    if (low < high) {
        int pi = partition(arr, low, high);
        quickSort(arr, low, pi - 1);
        quickSort(arr, pi + 1, high);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    quickSort(arr, 0, n - 1);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Quick Sort**
```java
public class QuickSort {
    public static int partition(int[] arr, int low, int high) {
        int pivot = arr[high];
        int i = (low - 1);
        for (int j = low; j < high; j++) {
            if (arr[j] < pivot) {
                i++;
                // Swap
                int temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }
        // Swap pivot
        int temp = arr[i + 1];
        arr[i + 1] = arr[high];
        arr[high] = temp;
        return i + 1;
    }

    public static void quickSort(int[] arr, int low, int high) {
        if (low < high) {
            int pi = partition(arr, low, high);
            quickSort(arr, low, pi - 1);
            quickSort(arr, pi + 1, high);
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        quickSort(arr, 0, arr.length - 1);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Quick Sort**
```python
def partition(arr, low, high):
    pivot = arr[high]
    i = low - 1
    for j in range(low, high):
        if arr[j] < pivot:
            i += 1
            arr[i], arr[j] = arr[j], arr[i]
    arr[i + 1], arr[high] = arr[high], arr[i + 1]
    return i + 1

def quick_sort(arr, low, high):
    if low < high:
        pi = partition(arr, low, high)
        quick_sort(arr, low, pi - 1)
        quick_sort(arr, pi + 1, high)

arr = [64, 34, 25, 12, 22]
quick_sort(arr, 0, len(arr) - 1)
print("Sorted array:", arr)
```

---

### 6. **Heap Sort**

#### **Algorithm**: 
Utilizes a binary heap data structure to create a sorted array. The process involves building a max heap and then extracting the maximum element repeatedly.

#### **Time Complexity**: O(n log n)

#### **C Code: Heap Sort**
```c
#include <stdio.h>

void swap(int* a, int* b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

void heapify(int arr[], int n, int i) {
    int largest = i;
    int left = 2 * i + 1;
    int right = 2 * i + 2;

    if (left < n && arr[left] > arr[largest])
        largest = left;
    if (right < n && arr[right] > arr[largest])
        largest = right;

    if (largest != i) {
        swap(&arr[i], &arr[largest]);
        heapify(arr, n, largest);
    }
}

void heapSort(int arr[], int n) {
    for (int i = n / 2 - 1; i >= 0; i--)
        heapify(arr, n, i);
    for (int i = n - 1; i >= 0; i--) {
        swap(&arr[0], &arr[i]);
        heapify(arr, i, 0);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    heapSort(arr, n);
    printf("Sorted array: ");
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
```

#### **C++ Code: Heap Sort**
```cpp
#include <iostream>
using namespace std;

void swap(int* a, int* b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

void heapify(int arr[], int n, int i) {
    int largest = i;
    int left = 2 * i + 1;
    int right = 2 * i + 2;

    if (left < n && arr[left] > arr[largest])
        largest = left;
    if (right < n && arr[right] > arr[largest])
        largest = right;

    if (largest != i) {
        swap(arr[i], arr[largest]);
        heapify(arr, n, largest);
    }
}

void heapSort(int arr[], int n) {
    for (int i = n / 2 - 1; i >= 0; i--)
        heapify(arr, n, i);
    for (int i = n - 1; i >= 0; i--) {
        swap(arr[0], arr[i]);
        heapify(arr, i, 0);
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22};
    int n = sizeof(arr) / sizeof(arr[0]);
    heapSort(arr, n);
    cout << "Sorted array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";
    return 0;
}
```

#### **Java Code: Heap Sort**
```java
public class HeapSort {
    public static void swap(int[] arr, int i, int j) {
        int temp = arr[i];
        arr[i] = arr[j];
        arr[j] = temp;
    }

    public static void heapify(int[] arr, int n, int i) {
        int largest = i;
        int left = 2 * i + 1;
        int right = 2 * i + 2;

        if (left < n && arr[left] > arr[largest])
            largest = left;
        if (right < n && arr[right] > arr[largest])
            largest = right;

        if (largest != i) {
            swap(arr, i, largest);
            heapify(arr, n, largest);
        }
    }

    public static void heapSort(int[] arr) {
        int n = arr.length;
        for (int i = n / 2 - 1; i >= 0; i--)
            heapify(arr, n, i);
        for (int i = n - 1; i >= 0; i--) {
            swap(arr, 0, i);
            heapify(arr, i, 0);
        }
    }

    public static void main(String[] args) {
        int[] arr = {64, 34, 25, 12, 22};
        heapSort(arr);
        System.out.print("Sorted array: ");
        for (int i : arr)
            System.out.print(i + " ");
    }
}
```

#### **Python Code: Heap Sort**
```python
def swap(arr, i, j):
    arr[i], arr[j] = arr[j], arr[i]

def heapify(arr, n, i):
    largest = i
    left = 2 * i + 1
    right = 2 * i + 2

    if left < n and arr[left] > arr[largest]:
        largest = left
    if right < n and arr[right] > arr[largest]:
        largest = right

    if largest != i:
        swap(arr, i, largest)
        heapify(arr, n, largest)

def heap_sort(arr):
    n = len(arr)
    for

 i in range(n // 2 - 1, -1, -1):
        heapify(arr, n, i)
    for i in range(n - 1, 0, -1):
        swap(arr, 0, i)
        heapify(arr, i, 0)

arr = [64, 34, 25, 12, 22]
heap_sort(arr)
print("Sorted array:", arr)
```

---

These implementations cover the fundamental sorting algorithms across multiple programming languages. You can use them as references or directly in your projects.





# linked Lists

Implementing CRUD operations and search algorithms on linked lists such as Singly Linked List, Doubly Linked List, Circular Linked List, and Circular Doubly Linked List can be done for fundamental operations like insertion, deletion, and traversal. However, for search algorithms such as **Binary Search, Jump Search, Interpolation Search**, etc., it's important to note that they are typically applicable to arrays or contiguous memory blocks (i.e., arrays, not linked lists) since they rely on random access to elements. 

Linked lists do not support efficient random access because nodes are stored non-contiguously in memory. Hence, searching in linked lists typically relies on **linear search**, where each node is traversed one by one.

### 1. Singly Linked List
A singly linked list has nodes that only point to the next node. Let's start by implementing CRUD operations along with Linear Search (as binary, jump, and other searches are not practical in linked lists).

#### Singly Linked List: C Code

```c
#include <stdio.h>
#include <stdlib.h>

// Node structure for a singly linked list
struct Node {
    int data;
    struct Node* next;
};

// Insert at the beginning
void insertAtBeginning(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    new_node->data = new_data;
    new_node->next = (*head_ref);
    (*head_ref) = new_node;
}

// Insert at the end
void insertAtEnd(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    struct Node* last = *head_ref;
    new_node->data = new_data;
    new_node->next = NULL;
    if (*head_ref == NULL) {
        *head_ref = new_node;
        return;
    }
    while (last->next != NULL) last = last->next;
    last->next = new_node;
}

// Delete a node
void deleteNode(struct Node** head_ref, int key) {
    struct Node* temp = *head_ref;
    struct Node* prev = NULL;
    if (temp != NULL && temp->data == key) {
        *head_ref = temp->next;
        free(temp);
        return;
    }
    while (temp != NULL && temp->data != key) {
        prev = temp;
        temp = temp->next;
    }
    if (temp == NULL) return;
    prev->next = temp->next;
    free(temp);
}

// Search in a singly linked list (Linear Search)
struct Node* search(struct Node* head, int key) {
    struct Node* current = head;
    while (current != NULL) {
        if (current->data == key) return current;
        current = current->next;
    }
    return NULL;
}

// Display the linked list
void displayList(struct Node* node) {
    while (node != NULL) {
        printf("%d -> ", node->data);
        node = node->next;
    }
    printf("NULL\n");
}

int main() {
    struct Node* head = NULL;
    
    insertAtEnd(&head, 10);
    insertAtEnd(&head, 20);
    insertAtEnd(&head, 30);
    insertAtBeginning(&head, 5);
    
    printf("Created Linked List: ");
    displayList(head);
    
    deleteNode(&head, 20);
    printf("After Deletion: ");
    displayList(head);
    
    struct Node* found = search(head, 30);
    if (found) printf("Node found with value %d\n", found->data);
    else printf("Node not found\n");

    return 0;
}
```

#### Singly Linked List: Java Code

```java
class SinglyLinkedList {
    class Node {
        int data;
        Node next;
        Node(int d) { data = d; next = null; }
    }
    
    Node head;
    
    // Insert at the beginning
    public void insertAtBeginning(int data) {
        Node newNode = new Node(data);
        newNode.next = head;
        head = newNode;
    }
    
    // Insert at the end
    public void insertAtEnd(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            return;
        }
        Node last = head;
        while (last.next != null) last = last.next;
        last.next = newNode;
    }
    
    // Delete a node
    public void deleteNode(int key) {
        Node temp = head, prev = null;
        if (temp != null && temp.data == key) {
            head = temp.next;
            return;
        }
        while (temp != null && temp.data != key) {
            prev = temp;
            temp = temp.next;
        }
        if (temp == null) return;
        prev.next = temp.next;
    }
    
    // Search (Linear Search)
    public Node search(int key) {
        Node current = head;
        while (current != null) {
            if (current.data == key) return current;
            current = current.next;
        }
        return null;
    }
    
    // Display the list
    public void displayList() {
        Node curr = head;
        while (curr != null) {
            System.out.print(curr.data + " -> ");
            curr = curr.next;
        }
        System.out.println("NULL");
    }
    
    public static void main(String[] args) {
        SinglyLinkedList list = new SinglyLinkedList();
        
        list.insertAtEnd(10);
        list.insertAtEnd(20);
        list.insertAtBeginning(5);
        
        list.displayList();
        
        list.deleteNode(20);
        System.out.println("After deletion:");
        list.displayList();
        
        Node found = list.search(10);
        if (found != null) System.out.println("Node found: " + found.data);
        else System.out.println("Node not found");
    }
}
```

#### Singly Linked List: Python Code

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class SinglyLinkedList:
    def __init__(self):
        self.head = None

    def insert_at_beginning(self, data):
        new_node = Node(data)
        new_node.next = self.head
        self.head = new_node

    def insert_at_end(self, data):
        new_node = Node(data)
        if not self.head:
            self.head = new_node
            return
        last = self.head
        while last.next:
            last = last.next
        last.next = new_node

    def delete_node(self, key):
        temp = self.head
        if temp and temp.data == key:
            self.head = temp.next
            return
        prev = None
        while temp and temp.data != key:
            prev = temp
            temp = temp.next
        if not temp:
            return
        prev.next = temp.next

    def search(self, key):
        current = self.head
        while current:
            if current.data == key:
                return current
            current = current.next
        return None

    def display(self):
        temp = self.head
        while temp:
            print(temp.data, end=" -> ")
            temp = temp.next
        print("NULL")


# Test the implementation
if __name__ == "__main__":
    llist = SinglyLinkedList()
    llist.insert_at_end(10)
    llist.insert_at_end(20)
    llist.insert_at_beginning(5)
    llist.display()
    
    llist.delete_node(20)
    print("After Deletion:")
    llist.display()

    found_node = llist.search(10)
    if found_node:
        print("Node found with value:", found_node.data)
    else:
        print("Node not found")
```

---

### 2. Doubly Linked List

A **Doubly Linked List (DLL)** is a type of linked list where each node has two pointers: one pointing to the previous node and one pointing to the next node. This allows for traversal in both directions—forward and backward.

### Structure of a Doubly Linked List Node

- **Data**: Stores the data element.
- **prev**: Pointer to the previous node.
- **next**: Pointer to the next node.

### Operations on Doubly Linked List
- **Insertion**: At the beginning, end, or after a specific node.
- **Deletion**: From the beginning, end, or a specific node.
- **Search**: Linear search to find an element.
- **Traversal**: Forward and backward traversal.



### Doubly Linked List CRUD Operations with C, C++, Java, and Python

#### **C Code for Doubly Linked List**

```c
#include <stdio.h>
#include <stdlib.h>

// Node structure
struct Node {
    int data;
    struct Node* prev;
    struct Node* next;
};

// Insert at the front
void insertAtFront(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    new_node->data = new_data;
    new_node->next = (*head_ref);
    new_node->prev = NULL;
    if ((*head_ref) != NULL)
        (*head_ref)->prev = new_node;
    (*head_ref) = new_node;
}

// Insert at the end
void insertAtEnd(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    struct Node* last = *head_ref;
    new_node->data = new_data;
    new_node->next = NULL;
    if (*head_ref == NULL) {
        new_node->prev = NULL;
        *head_ref = new_node;
        return;
    }
    while (last->next != NULL)
        last = last->next;
    last->next = new_node;
    new_node->prev = last;
}

// Delete a node
void deleteNode(struct Node** head_ref, struct Node* del) {
    if (*head_ref == NULL || del == NULL) return;
    if (*head_ref == del)
        *head_ref = del->next;
    if (del->next != NULL)
        del->next->prev = del->prev;
    if (del->prev != NULL)
        del->prev->next = del->next;
    free(del);
}

// Linear search for an element
struct Node* search(struct Node* head, int key) {
    struct Node* temp = head;
    while (temp != NULL) {
        if (temp->data == key)
            return temp;
        temp = temp->next;
    }
    return NULL;
}

// Display list from head
void displayList(struct Node* node) {
    struct Node* last;
    printf("Forward traversal: ");
    while (node != NULL) {
        printf("%d -> ", node->data);
        last = node;
        node = node->next;
    }
    printf("NULL\n");
}

// Display list from tail
void displayReverse(struct Node* node) {
    if (node == NULL)
        return;
    while (node->next != NULL)
        node = node->next;
    printf("Backward traversal: ");
    while (node != NULL) {
        printf("%d -> ", node->data);
        node = node->prev;
    }
    printf("NULL\n");
}

int main() {
    struct Node* head = NULL;
    insertAtEnd(&head, 10);
    insertAtEnd(&head, 20);
    insertAtFront(&head, 5);

    printf("Doubly Linked List: ");
    displayList(head);
    displayReverse(head);

    struct Node* found = search(head, 20);
    if (found) printf("Node found with value %d\n", found->data);
    else printf("Node not found\n");

    deleteNode(&head, found);
    printf("After deletion: ");
    displayList(head);
    return 0;
}
```

#### **C++ Code for Doubly Linked List**

```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* prev;
    Node* next;
    Node(int val) : data(val), prev(NULL), next(NULL) {}
};

class DoublyLinkedList {
    Node* head;
    
public:
    DoublyLinkedList() : head(NULL) {}
    
    // Insert at front
    void insertAtFront(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            return;
        }
        newNode->next = head;
        head->prev = newNode;
        head = newNode;
    }

    // Insert at end
    void insertAtEnd(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            return;
        }
        Node* temp = head;
        while (temp->next != NULL) temp = temp->next;
        temp->next = newNode;
        newNode->prev = temp;
    }

    // Delete a node
    void deleteNode(Node* del) {
        if (!head || !del) return;
        if (head == del) head = del->next;
        if (del->next) del->next->prev = del->prev;
        if (del->prev) del->prev->next = del->next;
        delete del;
    }

    // Search
    Node* search(int key) {
        Node* temp = head;
        while (temp != NULL) {
            if (temp->data == key) return temp;
            temp = temp->next;
        }
        return NULL;
    }

    // Display forward
    void displayList() {
        Node* temp = head;
        cout << "Forward traversal: ";
        while (temp) {
            cout << temp->data << " -> ";
            temp = temp->next;
        }
        cout << "NULL" << endl;
    }

    // Display backward
    void displayReverse() {
        if (!head) return;
        Node* temp = head;
        while (temp->next != NULL) temp = temp->next;
        cout << "Backward traversal: ";
        while (temp) {
            cout << temp->data << " -> ";
            temp = temp->prev;
        }
        cout << "NULL" << endl;
    }
};

int main() {
    DoublyLinkedList dll;
    
    dll.insertAtEnd(10);
    dll.insertAtEnd(20);
    dll.insertAtFront(5);

    dll.displayList();
    dll.displayReverse();

    Node* found = dll.search(20);
    if (found) cout << "Node found with value " << found->data << endl;
    else cout << "Node not found" << endl;

    dll.deleteNode(found);
    dll.displayList();

    return 0;
}
```

#### **Java Code for Doubly Linked List**

```java
class DoublyLinkedList {
    class Node {
        int data;
        Node prev;
        Node next;

        Node(int d) {
            data = d;
            prev = next = null;
        }
    }

    Node head;

    // Insert at the front
    public void insertAtFront(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            return;
        }
        newNode.next = head;
        head.prev = newNode;
        head = newNode;
    }

    // Insert at the end
    public void insertAtEnd(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            return;
        }
        Node last = head;
        while (last.next != null) last = last.next;
        last.next = newNode;
        newNode.prev = last;
    }

    // Delete a node
    public void deleteNode(Node del) {
        if (head == null || del == null) return;
        if (head == del) head = del.next;
        if (del.next != null) del.next.prev = del.prev;
        if (del.prev != null) del.prev.next = del.next;
    }

    // Linear search
    public Node search(int key) {
        Node temp = head;
        while (temp != null) {
            if (temp.data == key) return temp;
            temp = temp.next;
        }
        return null;
    }

    // Display list from front to back
    public void displayList() {
        Node temp = head;
        System.out.print("Forward traversal: ");
        while (temp != null) {
            System.out.print(temp.data + " -> ");
            temp = temp.next;
        }
        System.out.println("NULL");
    }

    // Display list from back to front
    public void displayReverse() {
        if (head == null) return;
        Node last = head;
        while (last.next != null) last = last.next;
        System.out.print("Backward traversal: ");
        while (last != null) {
            System.out.print(last.data + " -> ");
            last = last.prev;
        }
        System.out.println("NULL");
    }

    public static void main(String[] args) {
        DoublyLinkedList dll = new DoublyLinkedList();

        dll.insertAtEnd(10);
        dll.insertAtEnd(20);
        dll.insertAtFront(5);

        dll.displayList();
        dll.displayReverse();

        Node found = dll.search(20);
        if (found != null)

```


### 3. Circular Linked List

A **Circular Linked List** is a variation of a linked list where all nodes are connected in a circular fashion. In this structure, the last node points back to the first node instead of having a `null` reference. This allows for continuous traversal of the list.

### Structure of a Circular Linked List Node

- **Data**: Stores the data element.
- **Next**: Pointer to the next node, which wraps around to the head.

### Operations on Circular Linked List
- **Insertion**: At the beginning, end, or after a specific node.
- **Deletion**: From the beginning, end, or a specific node.
- **Search**: Linear search to find an element.
- **Traversal**: Can be done continuously due to the circular nature.

---

### Circular Linked List CRUD Operations with C, C++, Java, and Python

#### **C Code for Circular Linked List**

```c
#include <stdio.h>
#include <stdlib.h>

// Node structure
struct Node {
    int data;
    struct Node* next;
};

// Insert at the end
void insertAtEnd(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    struct Node* last = *head_ref;
    new_node->data = new_data;
    new_node->next = *head_ref; // Point to head to maintain circular nature
    if (*head_ref == NULL) {
        *head_ref = new_node;
        new_node->next = new_node; // Point to itself
        return;
    }
    while (last->next != *head_ref) last = last->next;
    last->next = new_node;
}

// Insert at the front
void insertAtFront(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    new_node->data = new_data;
    new_node->next = *head_ref;
    if (*head_ref == NULL) {
        *head_ref = new_node;
        new_node->next = new_node; // Point to itself
    } else {
        struct Node* last = *head_ref;
        while (last->next != *head_ref) last = last->next;
        last->next = new_node;
    }
    *head_ref = new_node;
}

// Delete a node
void deleteNode(struct Node** head_ref, int key) {
    if (*head_ref == NULL) return;
    struct Node *temp = *head_ref, *prev = NULL;
    // If head node itself holds the key
    if (temp->data == key) {
        if (temp->next == *head_ref) { // Only one node in list
            free(temp);
            *head_ref = NULL;
            return;
        }
        while (temp->next != *head_ref) temp = temp->next; // Find the last node
        temp->next = (*head_ref)->next; // Point last node to the second node
        struct Node* toDelete = *head_ref;
        *head_ref = (*head_ref)->next; // Move head to the next node
        free(toDelete);
        return;
    }
    // Search for the key in the list
    while (temp->next != *head_ref && temp->data != key) {
        prev = temp;
        temp = temp->next;
    }
    // If key was found
    if (temp->data == key) {
        prev->next = temp->next;
        free(temp);
    }
}

// Search for an element
struct Node* search(struct Node* head, int key) {
    struct Node* temp = head;
    if (head != NULL) {
        do {
            if (temp->data == key) return temp;
            temp = temp->next;
        } while (temp != head);
    }
    return NULL;
}

// Display list
void displayList(struct Node* head) {
    struct Node* temp = head;
    if (head != NULL) {
        do {
            printf("%d -> ", temp->data);
            temp = temp->next;
        } while (temp != head);
    }
    printf("(back to head)\n");
}

int main() {
    struct Node* head = NULL;

    insertAtEnd(&head, 10);
    insertAtEnd(&head, 20);
    insertAtFront(&head, 5);

    printf("Circular Linked List: ");
    displayList(head);

    deleteNode(&head, 20);
    printf("After deletion: ");
    displayList(head);

    struct Node* found = search(head, 10);
    if (found) printf("Node found with value %d\n", found->data);
    else printf("Node not found\n");

    return 0;
}
```

#### **C++ Code for Circular Linked List**

```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* next;
    Node(int val) : data(val), next(NULL) {}
};

class CircularLinkedList {
    Node* head;

public:
    CircularLinkedList() : head(NULL) {}

    // Insert at the end
    void insertAtEnd(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            newNode->next = head;
            return;
        }
        Node* temp = head;
        while (temp->next != head) temp = temp->next;
        temp->next = newNode;
        newNode->next = head;
    }

    // Insert at the front
    void insertAtFront(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            newNode->next = head;
            return;
        }
        newNode->next = head;
        Node* temp = head;
        while (temp->next != head) temp = temp->next;
        temp->next = newNode;
        head = newNode;
    }

    // Delete a node
    void deleteNode(int key) {
        if (!head) return;
        Node *temp = head, *prev = NULL;

        // If head node holds the key
        if (temp->data == key) {
            if (temp->next == head) { // Only one node
                delete temp;
                head = NULL;
                return;
            }
            while (temp->next != head) temp = temp->next; // Find last node
            temp->next = head->next; // Point last node to second node
            delete head; // Free memory
            head = temp->next; // Move head
            return;
        }

        // Search for the key
        while (temp->next != head && temp->data != key) {
            prev = temp;
            temp = temp->next;
        }

        if (temp->data == key) {
            prev->next = temp->next;
            delete temp;
        }
    }

    // Search for an element
    Node* search(int key) {
        Node* temp = head;
        if (head) {
            do {
                if (temp->data == key) return temp;
                temp = temp->next;
            } while (temp != head);
        }
        return NULL;
    }

    // Display list
    void displayList() {
        if (!head) return;
        Node* temp = head;
        do {
            cout << temp->data << " -> ";
            temp = temp->next;
        } while (temp != head);
        cout << "(back to head)" << endl;
    }
};

int main() {
    CircularLinkedList cll;
    cll.insertAtEnd(10);
    cll.insertAtEnd(20);
    cll.insertAtFront(5);

    cout << "Circular Linked List: ";
    cll.displayList();

    cll.deleteNode(20);
    cout << "After deletion: ";
    cll.displayList();

    Node* found = cll.search(10);
    if (found) cout << "Node found with value " << found->data << endl;
    else cout << "Node not found" << endl;

    return 0;
}
```

#### **Java Code for Circular Linked List**

```java
class CircularLinkedList {
    class Node {
        int data;
        Node next;

        Node(int d) {
            data = d;
            next = null;
        }
    }

    Node head;

    // Insert at the end
    public void insertAtEnd(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            newNode.next = head;
            return;
        }
        Node temp = head;
        while (temp.next != head) temp = temp.next;
        temp.next = newNode;
        newNode.next = head;
    }

    // Insert at the front
    public void insertAtFront(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            newNode.next = head;
            return;
        }
        newNode.next = head;
        Node temp = head;
        while (temp.next != head) temp = temp.next;
        temp.next = newNode;
        head = newNode;
    }

    // Delete a node
    public void deleteNode(int key) {
        if (head == null) return;
        Node temp = head, prev = null;

        // If head node holds the key
        if (temp.data == key) {
            if (temp.next == head) { // Only one node
                head = null;
                return;
            }
            while (temp.next != head) temp =

 temp.next; // Find last node
            temp.next = head.next; // Point last node to second node
            head = head.next; // Move head
            return;
        }

        // Search for the key
        while (temp.next != head && temp.data != key) {
            prev = temp;
            temp = temp.next;
        }

        if (temp.data == key) {
            prev.next = temp.next;
        }
    }

    // Search for an element
    public Node search(int key) {
        Node temp = head;
        if (head != null) {
            do {
                if (temp.data == key) return temp;
                temp = temp.next;
            } while (temp != head);
        }
        return null;
    }

    // Display list
    public void displayList() {
        if (head == null) return;
        Node temp = head;
        do {
            System.out.print(temp.data + " -> ");
            temp = temp.next;
        } while (temp != head);
        System.out.println("(back to head)");
    }

    public static void main(String[] args) {
        CircularLinkedList cll = new CircularLinkedList();
        cll.insertAtEnd(10);
        cll.insertAtEnd(20);
        cll.insertAtFront(5);

        System.out.print("Circular Linked List: ");
        cll.displayList();

        cll.deleteNode(20);
        System.out.print("After deletion: ");
        cll.displayList();

        Node found = cll.search(10);
        if (found != null) System.out.println("Node found with value " + found.data);
        else System.out.println("Node not found");
    }
}
```

#### **Python Code for Circular Linked List**

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class CircularLinkedList:
    def __init__(self):
        self.head = None

    # Insert at the end
    def insert_at_end(self, data):
        new_node = Node(data)
        if self.head is None:
            self.head = new_node
            new_node.next = self.head
            return
        temp = self.head
        while temp.next != self.head:
            temp = temp.next
        temp.next = new_node
        new_node.next = self.head

    # Insert at the front
    def insert_at_front(self, data):
        new_node = Node(data)
        if self.head is None:
            self.head = new_node
            new_node.next = self.head
            return
        new_node.next = self.head
        temp = self.head
        while temp.next != self.head:
            temp = temp.next
        temp.next = new_node
        self.head = new_node

    # Delete a node
    def delete_node(self, key):
        if self.head is None:
            return
        temp = self.head
        prev = None

        # If head node holds the key
        if temp.data == key:
            if temp.next == self.head:  # Only one node
                self.head = None
                return
            while temp.next != self.head:
                temp = temp.next  # Find last node
            temp.next = self.head.next
            self.head = self.head.next
            return

        # Search for the key
        while temp.next != self.head and temp.data != key:
            prev = temp
            temp = temp.next

        if temp.data == key:
            prev.next = temp.next

    # Search for an element
    def search(self, key):
        temp = self.head
        if self.head is not None:
            while True:
                if temp.data == key:
                    return temp
                temp = temp.next
                if temp == self.head:
                    break
        return None

    # Display list
    def display_list(self):
        temp = self.head
        if self.head is not None:
            while True:
                print(f"{temp.data} -> ", end="")
                temp = temp.next
                if temp == self.head:
                    break
            print("(back to head)")

# Usage
cll = CircularLinkedList()
cll.insert_at_end(10)
cll.insert_at_end(20)
cll.insert_at_front(5)

print("Circular Linked List: ", end="")
cll.display_list()

cll.delete_node(20)
print("After deletion: ", end="")
cll.display_list()

found = cll.search(10)
if found:
    print(f"Node found with value {found.data}")
else:
    print("Node not found")
```

These implementations cover the basic CRUD operations and searching in a Circular Linked List across C, C++, Java, and Python.

### 4. Circular Doubly Linked List

A **Circular Doubly Linked List (CDLL)** is a variation of the doubly linked list where the last node points to the first node and the first node points back to the last node. Each node has two pointers: one to the previous node and one to the next, allowing traversal in both directions in a circular manner.

### Structure of a Circular Doubly Linked List Node

- **Data**: Stores the data element.
- **Prev**: Pointer to the previous node.
- **Next**: Pointer to the next node, which wraps around to the head.

### Operations on Circular Doubly Linked List
- **Insertion**: At the beginning, end, or after a specific node.
- **Deletion**: From the beginning, end, or a specific node.
- **Search**: Linear search to find an element.
- **Traversal**: Can be done continuously in both directions.

---

### Circular Doubly Linked List CRUD Operations with C, C++, Java, and Python

#### **C Code for Circular Doubly Linked List**

```c
#include <stdio.h>
#include <stdlib.h>

// Node structure
struct Node {
    int data;
    struct Node* next;
    struct Node* prev;
};

// Insert at the end
void insertAtEnd(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    struct Node* last = *head_ref;
    new_node->data = new_data;

    if (*head_ref == NULL) {
        new_node->next = new_node;
        new_node->prev = new_node;
        *head_ref = new_node;
        return;
    }

    while (last->next != *head_ref) last = last->next;
    last->next = new_node;
    new_node->prev = last;
    new_node->next = *head_ref;
    (*head_ref)->prev = new_node;
}

// Insert at the front
void insertAtFront(struct Node** head_ref, int new_data) {
    struct Node* new_node = (struct Node*) malloc(sizeof(struct Node));
    new_node->data = new_data;
    if (*head_ref == NULL) {
        new_node->next = new_node;
        new_node->prev = new_node;
        *head_ref = new_node;
        return;
    }
    struct Node* last = *head_ref;
    while (last->next != *head_ref) last = last->next;
    new_node->next = *head_ref;
    new_node->prev = last;
    last->next = new_node;
    (*head_ref)->prev = new_node;
    *head_ref = new_node;
}

// Delete a node
void deleteNode(struct Node** head_ref, int key) {
    if (*head_ref == NULL) return;
    struct Node *temp = *head_ref, *prev = NULL;

    // If head node holds the key
    if (temp->data == key) {
        if (temp->next == *head_ref) { // Only one node
            free(temp);
            *head_ref = NULL;
            return;
        }
        while (temp->next != *head_ref) temp = temp->next; // Find last node
        temp->next = (*head_ref)->next; // Point last node to second node
        (*head_ref)->next->prev = temp;
        free(*head_ref);
        *head_ref = (*head_ref)->next; // Move head to the next node
        return;
    }

    // Search for the key in the list
    while (temp->next != *head_ref && temp->data != key) {
        prev = temp;
        temp = temp->next;
    }

    // If key was found
    if (temp->data == key) {
        prev->next = temp->next;
        temp->next->prev = prev;
        free(temp);
    }
}

// Search for an element
struct Node* search(struct Node* head, int key) {
    struct Node* temp = head;
    if (head != NULL) {
        do {
            if (temp->data == key) return temp;
            temp = temp->next;
        } while (temp != head);
    }
    return NULL;
}

// Display list
void displayList(struct Node* head) {
    struct Node* temp = head;
    if (head != NULL) {
        do {
            printf("%d <-> ", temp->data);
            temp = temp->next;
        } while (temp != head);
    }
    printf("(back to head)\n");
}

int main() {
    struct Node* head = NULL;

    insertAtEnd(&head, 10);
    insertAtEnd(&head, 20);
    insertAtFront(&head, 5);

    printf("Circular Doubly Linked List: ");
    displayList(head);

    deleteNode(&head, 20);
    printf("After deletion: ");
    displayList(head);

    struct Node* found = search(head, 10);
    if (found) printf("Node found with value %d\n", found->data);
    else printf("Node not found\n");

    return 0;
}
```

#### **C++ Code for Circular Doubly Linked List**

```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* next;
    Node* prev;
    Node(int val) : data(val), next(nullptr), prev(nullptr) {}
};

class CircularDoublyLinkedList {
    Node* head;

public:
    CircularDoublyLinkedList() : head(nullptr) {}

    // Insert at the end
    void insertAtEnd(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            newNode->next = head;
            newNode->prev = head;
            return;
        }
        Node* last = head;
        while (last->next != head) last = last->next;
        last->next = newNode;
        newNode->prev = last;
        newNode->next = head;
        head->prev = newNode;
    }

    // Insert at the front
    void insertAtFront(int data) {
        Node* newNode = new Node(data);
        if (!head) {
            head = newNode;
            newNode->next = head;
            newNode->prev = head;
            return;
        }
        newNode->next = head;
        newNode->prev = head->prev;
        head->prev->next = newNode;
        head->prev = newNode;
        head = newNode;
    }

    // Delete a node
    void deleteNode(int key) {
        if (!head) return;
        Node *temp = head;

        // If head node holds the key
        if (temp->data == key) {
            if (temp->next == head) { // Only one node
                delete temp;
                head = nullptr;
                return;
            }
            Node* last = head->prev;
            last->next = head->next;
            head->next->prev = last;
            delete head;
            head = head->next; // Move head
            return;
        }

        // Search for the key
        while (temp->next != head && temp->data != key) {
            temp = temp->next;
        }

        if (temp->data == key) {
            temp->prev->next = temp->next;
            temp->next->prev = temp->prev;
            delete temp;
        }
    }

    // Search for an element
    Node* search(int key) {
        Node* temp = head;
        if (head) {
            do {
                if (temp->data == key) return temp;
                temp = temp->next;
            } while (temp != head);
        }
        return nullptr;
    }

    // Display list
    void displayList() {
        if (!head) return;
        Node* temp = head;
        do {
            cout << temp->data << " <-> ";
            temp = temp->next;
        } while (temp != head);
        cout << "(back to head)" << endl;
    }
};

int main() {
    CircularDoublyLinkedList cdll;
    cdll.insertAtEnd(10);
    cdll.insertAtEnd(20);
    cdll.insertAtFront(5);

    cout << "Circular Doubly Linked List: ";
    cdll.displayList();

    cdll.deleteNode(20);
    cout << "After deletion: ";
    cdll.displayList();

    Node* found = cdll.search(10);
    if (found) cout << "Node found with value " << found->data << endl;
    else cout << "Node not found" << endl;

    return 0;
}
```

#### **Java Code for Circular Doubly Linked List**

```java
class CircularDoublyLinkedList {
    class Node {
        int data;
        Node next;
        Node prev;

        Node(int d) {
            data = d;
            next = prev = null;
        }
    }

    Node head;

    // Insert at the end
    public void insertAtEnd(int data) {
        Node newNode = new Node(data);
        if (head == null) {
            head = newNode;
            newNode.next = head;
            newNode.prev = head;
            return;
        }
        Node last = head;
        while (last.next != head) last = last.next;
        last.next = newNode;
        newNode.prev = last;
        newNode.next = head;
        head.prev = newNode;
    }

    // Insert at the front
    public void insertAtFront(int data) {
        Node newNode = new Node(data);
        if

 (head == null) {
            head = newNode;
            newNode.next = head;
            newNode.prev = head;
            return;
        }
        newNode.next = head;
        newNode.prev = head.prev;
        head.prev.next = newNode;
        head.prev = newNode;
        head = newNode;
    }

    // Delete a node
    public void deleteNode(int key) {
        if (head == null) return;
        Node temp = head;

        // If head node holds the key
        if (temp.data == key) {
            if (temp.next == head) { // Only one node
                head = null;
                return;
            }
            Node last = head.prev;
            last.next = head.next;
            head.next.prev = last;
            head = head.next; // Move head
            return;
        }

        // Search for the key
        while (temp.next != head && temp.data != key) {
            temp = temp.next;
        }

        if (temp.data == key) {
            temp.prev.next = temp.next;
            temp.next.prev = temp.prev;
        }
    }

    // Search for an element
    public Node search(int key) {
        Node temp = head;
        if (head != null) {
            do {
                if (temp.data == key) return temp;
                temp = temp.next;
            } while (temp != head);
        }
        return null;
    }

    // Display list
    public void displayList() {
        if (head == null) return;
        Node temp = head;
        do {
            System.out.print(temp.data + " <-> ");
            temp = temp.next;
        } while (temp != head);
        System.out.println("(back to head)");
    }

    public static void main(String[] args) {
        CircularDoublyLinkedList cdll = new CircularDoublyLinkedList();
        cdll.insertAtEnd(10);
        cdll.insertAtEnd(20);
        cdll.insertAtFront(5);

        System.out.print("Circular Doubly Linked List: ");
        cdll.displayList();

        cdll.deleteNode(20);
        System.out.print("After deletion: ");
        cdll.displayList();

        Node found = cdll.search(10);
        if (found != null) System.out.println("Node found with value " + found.data);
        else System.out.println("Node not found");
    }
}
```

#### **Python Code for Circular Doubly Linked List**

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None
        self.prev = None

class CircularDoublyLinkedList:
    def __init__(self):
        self.head = None

    # Insert at the end
    def insert_at_end(self, data):
        new_node = Node(data)
        if self.head is None:
            self.head = new_node
            new_node.next = self.head
            new_node.prev = self.head
            return
        last = self.head.prev
        last.next = new_node
        new_node.prev = last
        new_node.next = self.head
        self.head.prev = new_node

    # Insert at the front
    def insert_at_front(self, data):
        new_node = Node(data)
        if self.head is None:
            self.head = new_node
            new_node.next = self.head
            new_node.prev = self.head
            return
        new_node.next = self.head
        new_node.prev = self.head.prev
        self.head.prev.next = new_node
        self.head.prev = new_node
        self.head = new_node

    # Delete a node
    def delete_node(self, key):
        if self.head is None:
            return
        temp = self.head

        # If head node holds the key
        if temp.data == key:
            if temp.next == self.head:  # Only one node
                self.head = None
                return
            last = self.head.prev
            last.next = self.head.next
            self.head.next.prev = last
            self.head = self.head.next
            return

        # Search for the key
        while temp.next != self.head and temp.data != key:
            temp = temp.next

        if temp.data == key:
            temp.prev.next = temp.next
            temp.next.prev = temp.prev

    # Search for an element
    def search(self, key):
        temp = self.head
        if self.head is not None:
            while True:
                if temp.data == key:
                    return temp
                temp = temp.next
                if temp == self.head:
                    break
        return None

    # Display list
    def display_list(self):
        temp = self.head
        if self.head is not None:
            while True:
                print(f"{temp.data} <-> ", end="")
                temp = temp.next
                if temp == self.head:
                    break
            print("(back to head)")

# Usage
cdll = CircularDoublyLinkedList()
cdll.insert_at_end(10)
cdll.insert_at_end(20)
cdll.insert_at_front(5)

print("Circular Doubly Linked List: ", end="")
cdll.display_list()

cdll.delete_node(20)
print("After deletion: ", end="")
cdll.display_list()

found = cdll.search(10)
if found:
    print(f"Node found with value {found.data}")
else:
    print("Node not found")
```

These implementations cover the basic CRUD operations and searching in a Circular Doubly Linked List across C, C++, Java, and Python. 

### Search Algorithms Applicability

- **Linear Search** can be directly implemented in linked lists.
- **Binary Search**, **Jump Search**, **Interpolation Search**, **Exponential Search**, and **Fibonacci Search** are array-based search algorithms and are not applicable for linked lists due to the absence of random access.

---

### Sorting Algorithms in Linked Lists

Sorting algorithms like **Bubble Sort**, **Insertion Sort**, **Merge Sort**, etc., can be applied to linked lists, but algorithms relying on random access, like **Quick Sort**, are inefficient. Here's a list of sorting algorithms that can be applied:

- **Bubble Sort**
- **Insertion Sort**
- **Merge Sort**

For efficient sorting in linked lists, **Merge Sort** is recommended because it works well with the sequential nature of linked lists.


# Stacks and  Queues

Here's an overview of stacks, queues (linear, circular, priority, and deque), with implementations using both arrays and linked lists in C, C++, Java, and Python. Each data structure will include basic operations (push, pop for stacks; enqueue, dequeue for queues; etc.).

### 1. Stack

#### Using Arrays

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX 100

struct Stack {
    int arr[MAX];
    int top;
};

void initStack(struct Stack* stack) {
    stack->top = -1;
}

int isFull(struct Stack* stack) {
    return stack->top == MAX - 1;
}

int isEmpty(struct Stack* stack) {
    return stack->top == -1;
}

void push(struct Stack* stack, int item) {
    if (isFull(stack)) {
        printf("Stack Overflow\n");
        return;
    }
    stack->arr[++stack->top] = item;
}

int pop(struct Stack* stack) {
    if (isEmpty(stack)) {
        printf("Stack Underflow\n");
        return -1; // Indicating error
    }
    return stack->arr[stack->top--];
}

void display(struct Stack* stack) {
    for (int i = 0; i <= stack->top; i++) {
        printf("%d ", stack->arr[i]);
    }
    printf("\n");
}

int main() {
    struct Stack stack;
    initStack(&stack);
    
    push(&stack, 10);
    push(&stack, 20);
    printf("Stack: ");
    display(&stack);
    
    printf("Popped: %d\n", pop(&stack));
    printf("Stack: ");
    display(&stack);

    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class Stack {
    int* arr;
    int top;
    int maxSize;

public:
    Stack(int size) {
        arr = new int[size];
        top = -1;
        maxSize = size;
    }

    bool isFull() {
        return top == maxSize - 1;
    }

    bool isEmpty() {
        return top == -1;
    }

    void push(int item) {
        if (isFull()) {
            cout << "Stack Overflow" << endl;
            return;
        }
        arr[++top] = item;
    }

    int pop() {
        if (isEmpty()) {
            cout << "Stack Underflow" << endl;
            return -1; // Indicating error
        }
        return arr[top--];
    }

    void display() {
        for (int i = 0; i <= top; i++) {
            cout << arr[i] << " ";
        }
        cout << endl;
    }

    ~Stack() {
        delete[] arr;
    }
};

int main() {
    Stack stack(100);
    
    stack.push(10);
    stack.push(20);
    cout << "Stack: ";
    stack.display();
    
    cout << "Popped: " << stack.pop() << endl;
    cout << "Stack: ";
    stack.display();

    return 0;
}
```

**Java Code**
```java
class Stack {
    private int[] arr;
    private int top;
    private int maxSize;

    public Stack(int size) {
        arr = new int[size];
        top = -1;
        maxSize = size;
    }

    public boolean isFull() {
        return top == maxSize - 1;
    }

    public boolean isEmpty() {
        return top == -1;
    }

    public void push(int item) {
        if (isFull()) {
            System.out.println("Stack Overflow");
            return;
        }
        arr[++top] = item;
    }

    public int pop() {
        if (isEmpty()) {
            System.out.println("Stack Underflow");
            return -1; // Indicating error
        }
        return arr[top--];
    }

    public void display() {
        for (int i = 0; i <= top; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        Stack stack = new Stack(100);
        
        stack.push(10);
        stack.push(20);
        System.out.print("Stack: ");
        stack.display();
        
        System.out.println("Popped: " + stack.pop());
        System.out.print("Stack: ");
        stack.display();
    }
}
```

**Python Code**
```python
class Stack:
    def __init__(self, size):
        self.arr = [0] * size
        self.top = -1
        self.max_size = size

    def is_full(self):
        return self.top == self.max_size - 1

    def is_empty(self):
        return self.top == -1

    def push(self, item):
        if self.is_full():
            print("Stack Overflow")
            return
        self.top += 1
        self.arr[self.top] = item

    def pop(self):
        if self.is_empty():
            print("Stack Underflow")
            return -1  # Indicating error
        item = self.arr[self.top]
        self.top -= 1
        return item

    def display(self):
        for i in range(self.top + 1):
            print(self.arr[i], end=" ")
        print()

# Usage
stack = Stack(100)
stack.push(10)
stack.push(20)
print("Stack: ", end="")
stack.display()
print("Popped: ", stack.pop())
print("Stack: ", end="")
stack.display()
```

---

### 2. Linear Queue

#### Using Arrays

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX 100

struct Queue {
    int arr[MAX];
    int front;
    int rear;
};

void initQueue(struct Queue* queue) {
    queue->front = -1;
    queue->rear = -1;
}

int isFull(struct Queue* queue) {
    return queue->rear == MAX - 1;
}

int isEmpty(struct Queue* queue) {
    return queue->front == -1;
}

void enqueue(struct Queue* queue, int item) {
    if (isFull(queue)) {
        printf("Queue Overflow\n");
        return;
    }
    if (isEmpty(queue)) queue->front = 0;
    queue->arr[++queue->rear] = item;
}

int dequeue(struct Queue* queue) {
    if (isEmpty(queue)) {
        printf("Queue Underflow\n");
        return -1; // Indicating error
    }
    int item = queue->arr[queue->front];
    if (queue->front >= queue->rear) {
        queue->front = queue->rear = -1; // Reset queue
    } else {
        queue->front++;
    }
    return item;
}

void display(struct Queue* queue) {
    for (int i = queue->front; i <= queue->rear; i++) {
        printf("%d ", queue->arr[i]);
    }
    printf("\n");
}

int main() {
    struct Queue queue;
    initQueue(&queue);
    
    enqueue(&queue, 10);
    enqueue(&queue, 20);
    printf("Queue: ");
    display(&queue);
    
    printf("Dequeued: %d\n", dequeue(&queue));
    printf("Queue: ");
    display(&queue);

    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class Queue {
    int* arr;
    int front;
    int rear;
    int maxSize;

public:
    Queue(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    bool isFull() {
        return rear == maxSize - 1;
    }

    bool isEmpty() {
        return front == -1;
    }

    void enqueue(int item) {
        if (isFull()) {
            cout << "Queue Overflow" << endl;
            return;
        }
        if (isEmpty()) front = 0;
        arr[++rear] = item;
    }

    int dequeue() {
        if (isEmpty()) {
            cout << "Queue Underflow" << endl;
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front >= rear) {
            front = rear = -1; // Reset queue
        } else {
            front++;
        }
        return item;
    }

    void display() {
        for (int i = front; i <= rear; i++) {
            cout << arr[i] << " ";
        }
        cout << endl;
    }

    ~Queue() {
        delete[] arr;
    }
};

int main() {
    Queue queue(100);
    
    queue.enqueue(10);
    queue.enqueue(20);
    cout << "Queue: ";
    queue.display();
    
    cout << "Dequeued: " << queue.dequeue() << endl;
    cout << "Queue: ";
    queue.display();

    return 0;
}
```

**Java Code**
```java
class Queue {
    private int[] arr;
    private int front;
    private int rear;
    private int maxSize;

    public Queue(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    public boolean isFull() {
        return rear == maxSize - 1;
    }

    public boolean isEmpty() {
        return front == -1;
    }

    public void enqueue(int item) {
        if (isFull()) {
            System

.out.println("Queue Overflow");
            return;
        }
        if (isEmpty()) front = 0;
        arr[++rear] = item;
    }

    public int dequeue() {
        if (isEmpty()) {
            System.out.println("Queue Underflow");
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front >= rear) {
            front = rear = -1; // Reset queue
        } else {
            front++;
        }
        return item;
    }

    public void display() {
        for (int i = front; i <= rear; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        Queue queue = new Queue(100);
        
        queue.enqueue(10);
        queue.enqueue(20);
        System.out.print("Queue: ");
        queue.display();
        
        System.out.println("Dequeued: " + queue.dequeue());
        System.out.print("Queue: ");
        queue.display();
    }
}
```

**Python Code**
```python
class Queue:
    def __init__(self, size):
        self.arr = [0] * size
        self.front = self.rear = -1
        self.max_size = size

    def is_full(self):
        return self.rear == self.max_size - 1

    def is_empty(self):
        return self.front == -1

    def enqueue(self, item):
        if self.is_full():
            print("Queue Overflow")
            return
        if self.is_empty():
            self.front = 0
        self.rear += 1
        self.arr[self.rear] = item

    def dequeue(self):
        if self.is_empty():
            print("Queue Underflow")
            return -1  # Indicating error
        item = self.arr[self.front]
        if self.front >= self.rear:
            self.front = self.rear = -1  # Reset queue
        else:
            self.front += 1
        return item

    def display(self):
        for i in range(self.front, self.rear + 1):
            print(self.arr[i], end=" ")
        print()

# Usage
queue = Queue(100)
queue.enqueue(10)
queue.enqueue(20)
print("Queue: ", end="")
queue.display()
print("Dequeued: ", queue.dequeue())
print("Queue: ", end="")
queue.display()
```

---

### 3. Circular Queue

#### Using Arrays

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX 100

struct CircularQueue {
    int arr[MAX];
    int front, rear;
};

void initQueue(struct CircularQueue* queue) {
    queue->front = queue->rear = -1;
}

int isFull(struct CircularQueue* queue) {
    return (queue->rear + 1) % MAX == queue->front;
}

int isEmpty(struct CircularQueue* queue) {
    return queue->front == -1;
}

void enqueue(struct CircularQueue* queue, int item) {
    if (isFull(queue)) {
        printf("Queue Overflow\n");
        return;
    }
    if (isEmpty(queue)) queue->front = 0;
    queue->rear = (queue->rear + 1) % MAX;
    queue->arr[queue->rear] = item;
}

int dequeue(struct CircularQueue* queue) {
    if (isEmpty(queue)) {
        printf("Queue Underflow\n");
        return -1; // Indicating error
    }
    int item = queue->arr[queue->front];
    if (queue->front == queue->rear) {
        queue->front = queue->rear = -1; // Reset queue
    } else {
        queue->front = (queue->front + 1) % MAX;
    }
    return item;
}

void display(struct CircularQueue* queue) {
    if (isEmpty(queue)) return;
    int i = queue->front;
    while (1) {
        printf("%d ", queue->arr[i]);
        if (i == queue->rear) break;
        i = (i + 1) % MAX;
    }
    printf("\n");
}

int main() {
    struct CircularQueue queue;
    initQueue(&queue);
    
    enqueue(&queue, 10);
    enqueue(&queue, 20);
    printf("Circular Queue: ");
    display(&queue);
    
    printf("Dequeued: %d\n", dequeue(&queue));
    printf("Circular Queue: ");
    display(&queue);

    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class CircularQueue {
    int* arr;
    int front;
    int rear;
    int maxSize;

public:
    CircularQueue(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    bool isFull() {
        return (rear + 1) % maxSize == front;
    }

    bool isEmpty() {
        return front == -1;
    }

    void enqueue(int item) {
        if (isFull()) {
            cout << "Queue Overflow" << endl;
            return;
        }
        if (isEmpty()) front = 0;
        rear = (rear + 1) % maxSize;
        arr[rear] = item;
    }

    int dequeue() {
        if (isEmpty()) {
            cout << "Queue Underflow" << endl;
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front == rear) {
            front = rear = -1; // Reset queue
        } else {
            front = (front + 1) % maxSize;
        }
        return item;
    }

    void display() {
        if (isEmpty()) return;
        int i = front;
        while (true) {
            cout << arr[i] << " ";
            if (i == rear) break;
            i = (i + 1) % maxSize;
        }
        cout << endl;
    }

    ~CircularQueue() {
        delete[] arr;
    }
};

int main() {
    CircularQueue queue(100);
    
    queue.enqueue(10);
    queue.enqueue(20);
    cout << "Circular Queue: ";
    queue.display();
    
    cout << "Dequeued: " << queue.dequeue() << endl;
    cout << "Circular Queue: ";
    queue.display();

    return 0;
}
```

**Java Code**
```java
class CircularQueue {
    private int[] arr;
    private int front;
    private int rear;
    private int maxSize;

    public CircularQueue(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    public boolean isFull() {
        return (rear + 1) % maxSize == front;
    }

    public boolean isEmpty() {
        return front == -1;
    }

    public void enqueue(int item) {
        if (isFull()) {
            System.out.println("Queue Overflow");
            return;
        }
        if (isEmpty()) front = 0;
        rear = (rear + 1) % maxSize;
        arr[rear] = item;
    }

    public int dequeue() {
        if (isEmpty()) {
            System.out.println("Queue Underflow");
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front == rear) {
            front = rear = -1; // Reset queue
        } else {
            front = (front + 1) % maxSize;
        }
        return item;
    }

    public void display() {
        if (isEmpty()) return;
        int i = front;
        while (true) {
            System.out.print(arr[i] + " ");
            if (i == rear) break;
            i = (i + 1) % maxSize;
        }
        System.out.println();
    }

    public static void main(String[] args) {
        CircularQueue queue = new CircularQueue(100);
        
        queue.enqueue(10);
        queue.enqueue(20);
        System.out.print("Circular Queue: ");
        queue.display();
        
        System.out.println("Dequeued: " + queue.dequeue());
        System.out.print("Circular Queue: ");
        queue.display();
    }
}
```

**Python Code**
```python
class CircularQueue:
    def __init__(self, size):
        self.arr = [0] * size
        self.front = self.rear = -1
        self.max_size = size

    def is_full(self):
        return (self.rear + 1) % self.max_size == self.front

    def is_empty(self):
        return self.front == -1

    def enqueue(self, item):
        if self.is_full():
            print("Queue Overflow")
            return
        if self.is_empty():
            self.front = 0
        self.rear = (self.rear + 1) % self.max_size
        self.arr[self.rear] = item

    def dequeue(self):
        if self.is_empty():
            print("Queue Underflow")
            return -1  # Indicating error
        item = self.arr[self.front]
        if self.front == self.rear:
            self.front = self.rear = -1  # Reset queue
        else:
            self.front = (self.front + 1) % self.max_size
        return item

    def display(self):
        if self.is_empty():
            return
        i = self.front
        while True:
            print(self.arr[i], end=" ")
            if i == self.rear:
                break


            i = (i + 1) % self.max_size
        print()

# Usage
queue = CircularQueue(100)
queue.enqueue(10)
queue.enqueue(20)
print("Circular Queue: ", end="")
queue.display()
print("Dequeued: ", queue.dequeue())
print("Circular Queue: ", end="")
queue.display()
```

---

### 4. Priority Queue

#### Using Arrays

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

struct PriorityQueue {
    int* arr;
    int size;
    int capacity;
};

void initQueue(struct PriorityQueue* pq, int capacity) {
    pq->capacity = capacity;
    pq->size = 0;
    pq->arr = (int*)malloc(capacity * sizeof(int));
}

void enqueue(struct PriorityQueue* pq, int item) {
    if (pq->size == pq->capacity) {
        printf("Queue Overflow\n");
        return;
    }
    int i = pq->size++;
    while (i && item > pq->arr[(i - 1) / 2]) {
        pq->arr[i] = pq->arr[(i - 1) / 2];
        i = (i - 1) / 2;
    }
    pq->arr[i] = item;
}

int dequeue(struct PriorityQueue* pq) {
    if (pq->size == 0) {
        printf("Queue Underflow\n");
        return -1; // Indicating error
    }
    int result = pq->arr[0];
    pq->arr[0] = pq->arr[--pq->size];
    int i = 0;
    while (1) {
        int left = 2 * i + 1;
        int right = 2 * i + 2;
        if (left >= pq->size) break;
        int maxIndex = (right < pq->size && pq->arr[right] > pq->arr[left]) ? right : left;
        if (pq->arr[i] >= pq->arr[maxIndex]) break;
        int temp = pq->arr[i];
        pq->arr[i] = pq->arr[maxIndex];
        pq->arr[maxIndex] = temp;
        i = maxIndex;
    }
    return result;
}

void display(struct PriorityQueue* pq) {
    for (int i = 0; i < pq->size; i++) {
        printf("%d ", pq->arr[i]);
    }
    printf("\n");
}

int main() {
    struct PriorityQueue pq;
    initQueue(&pq, 10);
    
    enqueue(&pq, 30);
    enqueue(&pq, 20);
    enqueue(&pq, 40);
    printf("Priority Queue: ");
    display(&pq);
    
    printf("Dequeued: %d\n", dequeue(&pq));
    printf("Priority Queue: ");
    display(&pq);

    free(pq.arr);
    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class PriorityQueue {
    int* arr;
    int size;
    int capacity;

public:
    PriorityQueue(int capacity) {
        this->capacity = capacity;
        size = 0;
        arr = new int[capacity];
    }

    void enqueue(int item) {
        if (size == capacity) {
            cout << "Queue Overflow" << endl;
            return;
        }
        int i = size++;
        while (i && item > arr[(i - 1) / 2]) {
            arr[i] = arr[(i - 1) / 2];
            i = (i - 1) / 2;
        }
        arr[i] = item;
    }

    int dequeue() {
        if (size == 0) {
            cout << "Queue Underflow" << endl;
            return -1; // Indicating error
        }
        int result = arr[0];
        arr[0] = arr[--size];
        int i = 0;
        while (1) {
            int left = 2 * i + 1;
            int right = 2 * i + 2;
            if (left >= size) break;
            int maxIndex = (right < size && arr[right] > arr[left]) ? right : left;
            if (arr[i] >= arr[maxIndex]) break;
            swap(arr[i], arr[maxIndex]);
            i = maxIndex;
        }
        return result;
    }

    void display() {
        for (int i = 0; i < size; i++) {
            cout << arr[i] << " ";
        }
        cout << endl;
    }

    ~PriorityQueue() {
        delete[] arr;
    }
};

int main() {
    PriorityQueue pq(10);
    
    pq.enqueue(30);
    pq.enqueue(20);
    pq.enqueue(40);
    cout << "Priority Queue: ";
    pq.display();
    
    cout << "Dequeued: " << pq.dequeue() << endl;
    cout << "Priority Queue: ";
    pq.display();

    return 0;
}
```

**Java Code**
```java
class PriorityQueue {
    private int[] arr;
    private int size;
    private int capacity;

    public PriorityQueue(int capacity) {
        this.capacity = capacity;
        size = 0;
        arr = new int[capacity];
    }

    public void enqueue(int item) {
        if (size == capacity) {
            System.out.println("Queue Overflow");
            return;
        }
        int i = size++;
        while (i > 0 && item > arr[(i - 1) / 2]) {
            arr[i] = arr[(i - 1) / 2];
            i = (i - 1) / 2;
        }
        arr[i] = item;
    }

    public int dequeue() {
        if (size == 0) {
            System.out.println("Queue Underflow");
            return -1; // Indicating error
        }
        int result = arr[0];
        arr[0] = arr[--size];
        int i = 0;
        while (true) {
            int left = 2 * i + 1;
            int right = 2 * i + 2;
            if (left >= size) break;
            int maxIndex = (right < size && arr[right] > arr[left]) ? right : left;
            if (arr[i] >= arr[maxIndex]) break;
            int temp = arr[i];
            arr[i] = arr[maxIndex];
            arr[maxIndex] = temp;
            i = maxIndex;
        }
        return result;
    }

    public void display() {
        for (int i = 0; i < size; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        PriorityQueue pq = new PriorityQueue(10);
        
        pq.enqueue(30);
        pq.enqueue(20);
        pq.enqueue(40);
        System.out.print("Priority Queue: ");
        pq.display();
        
        System.out.println("Dequeued: " + pq.dequeue());
        System.out.print("Priority Queue: ");
        pq.display();
    }
}
```

**Python Code**
```python
class PriorityQueue:
    def __init__(self, capacity):
        self.capacity = capacity
        self.size = 0
        self.arr = [0] * capacity

    def enqueue(self, item):
        if self.size == self.capacity:
            print("Queue Overflow")
            return
        i = self.size
        self.size += 1
        while i > 0 and item > self.arr[(i - 1) // 2]:
            self.arr[i] = self.arr[(i - 1) // 2]
            i = (i - 1) // 2
        self.arr[i] = item

    def dequeue(self):
        if self.size == 0:
            print("Queue Underflow")
            return -1  # Indicating error
        result = self.arr[0]
        self.arr[0] = self.arr[self.size - 1]
        self.size -= 1
        i = 0
        while True:
            left = 2 * i + 1
            right = 2 * i + 2
            if left >= self.size:
                break
            max_index = right if (right < self.size and self.arr[right] > self.arr[left]) else left
            if self.arr[i] >= self.arr[max_index]:
                break
            self.arr[i], self.arr[max_index] = self.arr[max_index], self.arr[i]
            i = max_index
        return result

    def display(self):
        for i in range(self.size):
            print(self.arr[i], end=" ")
        print()

# Usage
pq = PriorityQueue(10)
pq.enqueue(30)
pq.enqueue(20)
pq.enqueue(40)
print("Priority Queue: ", end="")
pq.display()
print("Dequeued: ", pq.dequeue())
print("Priority Queue: ", end="")
pq.display()
```

---

### 5. Double-Ended Queue (Deque)

#### Using Arrays

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

#define MAX 100

struct Deque {
    int arr[MAX];
    int front, rear;
};

void initDeque(struct Deque* deque) {
    deque->front = deque->rear = -1;
}

int isFull(struct Deque* deque) {
    return (deque->front == 0 && deque->rear == MAX - 1) || (deque->front == deque->rear + 1);
}

int isEmpty(struct Deque* deque) {


    return deque->front == -1;
}

void insertFront(struct Deque* deque, int item) {
    if (isFull(deque)) {
        printf("Deque Overflow\n");
        return;
    }
    if (isEmpty(deque)) {
        deque->front = deque->rear = 0;
    } else if (deque->front == 0) {
        deque->front = MAX - 1;
    } else {
        deque->front--;
    }
    deque->arr[deque->front] = item;
}

void insertRear(struct Deque* deque, int item) {
    if (isFull(deque)) {
        printf("Deque Overflow\n");
        return;
    }
    if (isEmpty(deque)) {
        deque->front = deque->rear = 0;
    } else if (deque->rear == MAX - 1) {
        deque->rear = 0;
    } else {
        deque->rear++;
    }
    deque->arr[deque->rear] = item;
}

int deleteFront(struct Deque* deque) {
    if (isEmpty(deque)) {
        printf("Deque Underflow\n");
        return -1; // Indicating error
    }
    int item = deque->arr[deque->front];
    if (deque->front == deque->rear) {
        deque->front = deque->rear = -1; // Reset deque
    } else if (deque->front == MAX - 1) {
        deque->front = 0;
    } else {
        deque->front++;
    }
    return item;
}

int deleteRear(struct Deque* deque) {
    if (isEmpty(deque)) {
        printf("Deque Underflow\n");
        return -1; // Indicating error
    }
    int item = deque->arr[deque->rear];
    if (deque->front == deque->rear) {
        deque->front = deque->rear = -1; // Reset deque
    } else if (deque->rear == 0) {
        deque->rear = MAX - 1;
    } else {
        deque->rear--;
    }
    return item;
}

void display(struct Deque* deque) {
    if (isEmpty(deque)) return;
    int i = deque->front;
    while (1) {
        printf("%d ", deque->arr[i]);
        if (i == deque->rear) break;
        i = (i + 1) % MAX;
    }
    printf("\n");
}

int main() {
    struct Deque deque;
    initDeque(&deque);
    
    insertRear(&deque, 10);
    insertRear(&deque, 20);
    insertFront(&deque, 30);
    printf("Deque: ");
    display(&deque);
    
    printf("Deleted from front: %d\n", deleteFront(&deque));
    printf("Deque: ");
    display(&deque);
    
    printf("Deleted from rear: %d\n", deleteRear(&deque));
    printf("Deque: ");
    display(&deque);

    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class Deque {
    int* arr;
    int front;
    int rear;
    int maxSize;

public:
    Deque(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    bool isFull() {
        return (front == 0 && rear == maxSize - 1) || (front == rear + 1);
    }

    bool isEmpty() {
        return front == -1;
    }

    void insertFront(int item) {
        if (isFull()) {
            cout << "Deque Overflow" << endl;
            return;
        }
        if (isEmpty()) {
            front = rear = 0;
        } else if (front == 0) {
            front = maxSize - 1;
        } else {
            front--;
        }
        arr[front] = item;
    }

    void insertRear(int item) {
        if (isFull()) {
            cout << "Deque Overflow" << endl;
            return;
        }
        if (isEmpty()) {
            front = rear = 0;
        } else if (rear == maxSize - 1) {
            rear = 0;
        } else {
            rear++;
        }
        arr[rear] = item;
    }

    int deleteFront() {
        if (isEmpty()) {
            cout << "Deque Underflow" << endl;
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front == rear) {
            front = rear = -1; // Reset deque
        } else if (front == maxSize - 1) {
            front = 0;
        } else {
            front++;
        }
        return item;
    }

    int deleteRear() {
        if (isEmpty()) {
            cout << "Deque Underflow" << endl;
            return -1; // Indicating error
        }
        int item = arr[rear];
        if (front == rear) {
            front = rear = -1; // Reset deque
        } else if (rear == 0) {
            rear = maxSize - 1;
        } else {
            rear--;
        }
        return item;
    }

    void display() {
        if (isEmpty()) return;
        int i = front;
        while (1) {
            cout << arr[i] << " ";
            if (i == rear) break;
            i = (i + 1) % maxSize;
        }
        cout << endl;
    }

    ~Deque() {
        delete[] arr;
    }
};

int main() {
    Deque deque(100);
    
    deque.insertRear(10);
    deque.insertRear(20);
    deque.insertFront(30);
    cout << "Deque: ";
    deque.display();
    
    cout << "Deleted from front: " << deque.deleteFront() << endl;
    cout << "Deque: ";
    deque.display();
    
    cout << "Deleted from rear: " << deque.deleteRear() << endl;
    cout << "Deque: ";
    deque.display();

    return 0;
}
```

**Java Code**
```java
class Deque {
    private int[] arr;
    private int front;
    private int rear;
    private int maxSize;

    public Deque(int size) {
        arr = new int[size];
        front = rear = -1;
        maxSize = size;
    }

    public boolean isFull() {
        return (front == 0 && rear == maxSize - 1) || (front == rear + 1);
    }

    public boolean isEmpty() {
        return front == -1;
    }

    public void insertFront(int item) {
        if (isFull()) {
            System.out.println("Deque Overflow");
            return;
        }
        if (isEmpty()) {
            front = rear = 0;
        } else if (front == 0) {
            front = maxSize - 1;
        } else {
            front--;
        }
        arr[front] = item;
    }

    public void insertRear(int item) {
        if (isFull()) {
            System.out.println("Deque Overflow");
            return;
        }
        if (isEmpty()) {
            front = rear = 0;
        } else if (rear == maxSize - 1) {
            rear = 0;
        } else {
            rear++;
        }
        arr[rear] = item;
    }

    public int deleteFront() {
        if (isEmpty()) {
            System.out.println("Deque Underflow");
            return -1; // Indicating error
        }
        int item = arr[front];
        if (front == rear) {
            front = rear = -1; // Reset deque
        } else if (front == maxSize - 1) {
            front = 0;
        } else {
            front++;
        }
        return item;
    }

    public int deleteRear() {
        if (isEmpty()) {
            System.out.println("Deque Underflow");
            return -1; // Indicating error
        }
        int item = arr[rear];
        if (front == rear) {
            front = rear = -1; // Reset deque
        } else if (rear == 0) {
            rear = maxSize - 1;
        } else {
            rear--;
        }
        return item;
    }

    public void display() {
        if (isEmpty()) return;
        int i = front;
        while (true) {
            System.out.print(arr[i] + " ");
            if (i == rear) break;
            i = (i + 1) % maxSize;
        }
        System.out.println();
    }

    public static void main(String[] args) {
        Deque deque = new Deque(100);
        
        deque.insertRear(10);
        deque.insertRear(20);
        deque.insertFront(30);
        System.out.print("Deque: ");
        deque.display();
        
        System.out.println("Deleted from front: " + deque.deleteFront());
        System.out.print("Deque: ");
        deque.display();
        
        System.out.println("Deleted from rear: " + deque.deleteRear());
        System.out.print("Deque: ");
        deque.display();
    }
}
```

**Python Code**
```python
class Deque:
    def __init__(self, size):
        self.arr = [0] * size
        self.front = self.rear = -1
        self.max_size = size

    def is_full(self):
        return (self.front == 0 and self.rear == self.max_size - 1)

 or (self.front == self.rear + 1)

    def is_empty(self):
        return self.front == -1

    def insert_front(self, item):
        if self.is_full():
            print("Deque Overflow")
            return
        if self.is_empty():
            self.front = self.rear = 0
        elif self.front == 0:
            self.front = self.max_size - 1
        else:
            self.front -= 1
        self.arr[self.front] = item

    def insert_rear(self, item):
        if self.is_full():
            print("Deque Overflow")
            return
        if self.is_empty():
            self.front = self.rear = 0
        elif self.rear == self.max_size - 1:
            self.rear = 0
        else:
            self.rear += 1
        self.arr[self.rear] = item

    def delete_front(self):
        if self.is_empty():
            print("Deque Underflow")
            return -1  # Indicating error
        item = self.arr[self.front]
        if self.front == self.rear:
            self.front = self.rear = -1  # Reset deque
        elif self.front == self.max_size - 1:
            self.front = 0
        else:
            self.front += 1
        return item

    def delete_rear(self):
        if self.is_empty():
            print("Deque Underflow")
            return -1  # Indicating error
        item = self.arr[self.rear]
        if self.front == self.rear:
            self.front = self.rear = -1  # Reset deque
        elif self.rear == 0:
            self.rear = self.max_size - 1
        else:
            self.rear -= 1
        return item

    def display(self):
        if self.is_empty():
            return
        i = self.front
        while True:
            print(self.arr[i], end=" ")
            if i == self.rear:
                break
            i = (i + 1) % self.max_size
        print()

# Usage
deque = Deque(100)
deque.insert_rear(10)
deque.insert_rear(20)
deque.insert_front(30)
print("Deque: ", end="")
deque.display()
print("Deleted from front: ", deque.delete_front())
print("Deque: ", end="")
deque.display()
print("Deleted from rear: ", deque.delete_rear())
print("Deque: ", end="")
deque.display()
```

---

This comprehensive guide covers the basic operations for different types of queues in various programming languages, which should help you grasp the concepts of data structures effectively. 

#Trees
(binary trees, binary search trees, AVL trees, heaps)

Here's a breakdown of various tree data structures: binary trees, binary search trees, AVL trees, and heaps, along with CRUD operations in C, C++, Java, and Python.

### 1. Binary Tree

**Structure and Basic Operations**

#### C Code
```c
#include <stdio.h>
#include <stdlib.h>

struct Node {
    int data;
    struct Node* left;
    struct Node* right;
};

struct Node* createNode(int data) {
    struct Node* newNode = (struct Node*)malloc(sizeof(struct Node));
    newNode->data = data;
    newNode->left = newNode->right = NULL;
    return newNode;
}

void insert(struct Node** root, int data) {
    if (*root == NULL) {
        *root = createNode(data);
        return;
    }
    if (data < (*root)->data)
        insert(&((*root)->left), data);
    else
        insert(&((*root)->right), data);
}

void inorder(struct Node* root) {
    if (root) {
        inorder(root->left);
        printf("%d ", root->data);
        inorder(root->right);
    }
}

int main() {
    struct Node* root = NULL;
    insert(&root, 5);
    insert(&root, 3);
    insert(&root, 7);
    printf("Inorder Traversal: ");
    inorder(root);
    printf("\n");
    return 0;
}
```

#### C++ Code
```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* left;
    Node* right;

    Node(int value) {
        data = value;
        left = right = nullptr;
    }
};

class BinaryTree {
public:
    Node* root;

    BinaryTree() {
        root = nullptr;
    }

    void insert(int data) {
        insertHelper(&root, data);
    }

    void insertHelper(Node** node, int data) {
        if (*node == nullptr) {
            *node = new Node(data);
            return;
        }
        if (data < (*node)->data)
            insertHelper(&((*node)->left), data);
        else
            insertHelper(&((*node)->right), data);
    }

    void inorder() {
        inorderHelper(root);
    }

    void inorderHelper(Node* node) {
        if (node) {
            inorderHelper(node->left);
            cout << node->data << " ";
            inorderHelper(node->right);
        }
    }
};

int main() {
    BinaryTree tree;
    tree.insert(5);
    tree.insert(3);
    tree.insert(7);
    cout << "Inorder Traversal: ";
    tree.inorder();
    cout << endl;
    return 0;
}
```

#### Java Code
```java
class Node {
    int data;
    Node left, right;

    Node(int item) {
        data = item;
        left = right = null;
    }
}

class BinaryTree {
    Node root;

    void insert(int data) {
        root = insertRec(root, data);
    }

    Node insertRec(Node root, int data) {
        if (root == null) {
            root = new Node(data);
            return root;
        }
        if (data < root.data)
            root.left = insertRec(root.left, data);
        else
            root.right = insertRec(root.right, data);
        return root;
    }

    void inorder() {
        inorderRec(root);
    }

    void inorderRec(Node root) {
        if (root != null) {
            inorderRec(root.left);
            System.out.print(root.data + " ");
            inorderRec(root.right);
        }
    }

    public static void main(String[] args) {
        BinaryTree tree = new BinaryTree();
        tree.insert(5);
        tree.insert(3);
        tree.insert(7);
        System.out.print("Inorder Traversal: ");
        tree.inorder();
    }
}
```

#### Python Code
```python
class Node:
    def __init__(self, data):
        self.data = data
        self.left = None
        self.right = None

class BinaryTree:
    def __init__(self):
        self.root = None

    def insert(self, data):
        if self.root is None:
            self.root = Node(data)
        else:
            self._insert(self.root, data)

    def _insert(self, node, data):
        if data < node.data:
            if node.left is None:
                node.left = Node(data)
            else:
                self._insert(node.left, data)
        else:
            if node.right is None:
                node.right = Node(data)
            else:
                self._insert(node.right, data)

    def inorder(self):
        self._inorder(self.root)

    def _inorder(self, node):
        if node:
            self._inorder(node.left)
            print(node.data, end=' ')
            self._inorder(node.right)

# Usage
tree = BinaryTree()
tree.insert(5)
tree.insert(3)
tree.insert(7)
print("Inorder Traversal: ", end="")
tree.inorder()
print()
```

---

### 2. Binary Search Tree (BST)

The operations are similar to those of a binary tree, as BST is a specialized form of binary tree.

**Key Differences:**
- In a BST, for any node:
  - Left child is less than the parent.
  - Right child is greater than the parent.

### 3. AVL Tree

AVL trees are self-balancing binary search trees. Here’s an example implementation:

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

struct Node {
    int data;
    int height;
    struct Node* left;
    struct Node* right;
};

// Function prototypes
int height(struct Node* N);
int max(int a, int b);
struct Node* rightRotate(struct Node* y);
struct Node* leftRotate(struct Node* x);
int getBalance(struct Node* N);
struct Node* insert(struct Node* node, int data);
void preOrder(struct Node* root);

int height(struct Node* N) {
    if (N == NULL) return 0;
    return N->height;
}

int max(int a, int b) {
    return (a > b) ? a : b;
}

struct Node* createNode(int data) {
    struct Node* node = (struct Node*)malloc(sizeof(struct Node));
    node->data = data;
    node->left = node->right = NULL;
    node->height = 1; // New node is initially added at leaf
    return node;
}

struct Node* rightRotate(struct Node* y) {
    struct Node* x = y->left;
    struct Node* T2 = x->right;
    x->right = y;
    y->left = T2;
    y->height = max(height(y->left), height(y->right)) + 1;
    x->height = max(height(x->left), height(x->right)) + 1;
    return x;
}

struct Node* leftRotate(struct Node* x) {
    struct Node* y = x->right;
    struct Node* T2 = y->left;
    y->left = x;
    x->right = T2;
    x->height = max(height(x->left), height(x->right)) + 1;
    y->height = max(height(y->left), height(y->right)) + 1;
    return y;
}

int getBalance(struct Node* N) {
    if (N == NULL) return 0;
    return height(N->left) - height(N->right);
}

struct Node* insert(struct Node* node, int data) {
    if (node == NULL) return createNode(data);
    if (data < node->data)
        node->left = insert(node->left, data);
    else if (data > node->data)
        node->right = insert(node->right, data);
    else // Duplicate data not allowed
        return node;
    
    node->height = 1 + max(height(node->left), height(node->right)));
    int balance = getBalance(node);

    // Left Left Case
    if (balance > 1 && data < node->left->data)
        return rightRotate(node);

    // Right Right Case
    if (balance < -1 && data > node->right->data)
        return leftRotate(node);

    // Left Right Case
    if (balance > 1 && data > node->left->data) {
        node->left = leftRotate(node->left);
        return rightRotate(node);
    }

    // Right Left Case
    if (balance < -1 && data < node->right->data) {
        node->right = rightRotate(node->right);
        return leftRotate(node);
    }

    return node;
}

void preOrder(struct Node* root) {
    if (root != NULL) {
        printf("%d ", root->data);
        preOrder(root->left);
        preOrder(root->right);
    }
}

int main() {
    struct Node* root = NULL;
    root = insert(root, 30);
    root = insert(root, 20);
    root = insert(root, 40);
    root = insert(root, 10);
    printf("Preorder traversal of the AVL tree is: ");
    preOrder(root);
    printf("\n");
    return 0;
}
```

#### C++, Java, and Python implementations are similar in logic but have different syntax. If you need specific examples for these languages, just let me know!

---

### 4. Heap

Heaps are a specialized tree-based data structure that satisfies the heap property.

**Min-Heap Operations Example:**

#### C Code
```c


#include <stdio.h>
#include <stdlib.h>

struct MinHeap {
    int* array;
    int capacity;
    int size;
};

struct MinHeap* createMinHeap(int capacity) {
    struct MinHeap* minHeap = (struct MinHeap*)malloc(sizeof(struct MinHeap));
    minHeap->capacity = capacity;
    minHeap->size = 0;
    minHeap->array = (int*)malloc(capacity * sizeof(int));
    return minHeap;
}

void swap(int* a, int* b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

void minHeapify(struct MinHeap* minHeap, int idx) {
    int smallest = idx;
    int left = 2 * idx + 1;
    int right = 2 * idx + 2;

    if (left < minHeap->size && minHeap->array[left] < minHeap->array[smallest])
        smallest = left;
    if (right < minHeap->size && minHeap->array[right] < minHeap->array[smallest])
        smallest = right;
    if (smallest != idx) {
        swap(&minHeap->array[smallest], &minHeap->array[idx]);
        minHeapify(minHeap, smallest);
    }
}

void insert(struct MinHeap* minHeap, int element) {
    if (minHeap->size == minHeap->capacity) return;
    minHeap->array[minHeap->size] = element;
    int current = minHeap->size;
    minHeap->size++;

    while (current != 0 && minHeap->array[current] < minHeap->array[(current - 1) / 2]) {
        swap(&minHeap->array[current], &minHeap->array[(current - 1) / 2]);
        current = (current - 1) / 2;
    }
}

int extractMin(struct MinHeap* minHeap) {
    if (minHeap->size <= 0) return -1;
    if (minHeap->size == 1) {
        minHeap->size--;
        return minHeap->array[0];
    }

    int root = minHeap->array[0];
    minHeap->array[0] = minHeap->array[minHeap->size - 1];
    minHeap->size--;
    minHeapify(minHeap, 0);
    return root;
}

void printHeap(struct MinHeap* minHeap) {
    for (int i = 0; i < minHeap->size; i++)
        printf("%d ", minHeap->array[i]);
    printf("\n");
}

int main() {
    struct MinHeap* minHeap = createMinHeap(10);
    insert(minHeap, 3);
    insert(minHeap, 1);
    insert(minHeap, 6);
    insert(minHeap, 5);
    insert(minHeap, 2);
    printf("Min Heap: ");
    printHeap(minHeap);
    printf("Extracted Min: %d\n", extractMin(minHeap));
    printf("Min Heap after extraction: ");
    printHeap(minHeap);
    return 0;
}
```

#### C++, Java, and Python implementations follow similar logic. Let me know if you’d like to see any specific implementations for these languages!

---

This should give you a solid foundation on trees and heaps across multiple programming languages.


# Graphs

**Definition:**
A graph is a collection of nodes (or vertices) and edges that connect pairs of nodes. Graphs are used to represent relationships between objects. 

**Types of Graphs:**

1. **Undirected Graph**: Edges have no direction. The relationship between vertices is bidirectional.

   ![Undirected Graph](https://i.imgur.com/zvH6Nsy.png)
   - Example: A social network where each person is connected to others.

2. **Directed Graph (Digraph)**: Edges have a direction, indicating the relationship flows from one vertex to another.

   ![Directed Graph](https://i.imgur.com/RcSvdX6.png)
   - Example: A Twitter follow graph where one user follows another.

3. **Weighted Graph**: Edges carry weights (or costs), representing the distance or cost of traveling between two vertices.

   ![Weighted Graph](https://i.imgur.com/cE3G33B.png)
   - Example: A road map where edges represent distances between cities.

4. **Unweighted Graph**: All edges are treated equally, with no weights assigned.

   ![Unweighted Graph](https://i.imgur.com/UXeV4ZR.png)

5. **Cyclic Graph**: Contains at least one cycle, where a path starts and ends at the same vertex.

   ![Cyclic Graph](https://i.imgur.com/U4UG9Fn.png)

6. **Acyclic Graph**: Does not contain any cycles.

   ![Acyclic Graph](https://i.imgur.com/YWTmbDr.png)

7. **Connected Graph**: There is a path between every pair of vertices.

   ![Connected Graph](https://i.imgur.com/sg4f8GZ.png)

8. **Disconnected Graph**: Some vertices are not connected by paths.

   ![Disconnected Graph](https://i.imgur.com/QnKfp8t.png)

9. **Tree**: A special type of acyclic graph that is connected and has no cycles.

   ![Tree](https://i.imgur.com/3ep1J4Z.png)

### Key Terminology

- **Vertex (Node)**: A fundamental unit of a graph.
- **Edge**: A connection between two vertices.
- **Degree**: The number of edges connected to a vertex.
- **Path**: A sequence of vertices connected by edges.
- **Cycle**: A path that starts and ends at the same vertex.

### Applications of Graphs

- **Social Networks**: Modeling relationships between users.
- **Routing Algorithms**: Finding the shortest path in navigation systems.
- **Network Topology**: Understanding and optimizing computer networks.
- **Recommendation Systems**: Analyzing relationships to suggest products or services.

Graphs are versatile structures widely used in computer science, mathematics, and real-world applications.

Here’s how to implement graphs using different representations: Adjacency Matrix, Adjacency List, Edge List, and Incidence Matrix in C, C++, Java, and Python.

### 1. Adjacency Matrix

**C Code**
```c
#include <stdio.h>
#define MAX 10

void initMatrix(int graph[MAX][MAX], int vertices) {
    for (int i = 0; i < vertices; i++)
        for (int j = 0; j < vertices; j++)
            graph[i][j] = 0; // Initialize to 0
}

void addEdge(int graph[MAX][MAX], int u, int v) {
    graph[u][v] = 1; // For undirected graph, also add graph[v][u] = 1;
}

void displayMatrix(int graph[MAX][MAX], int vertices) {
    for (int i = 0; i < vertices; i++) {
        for (int j = 0; j < vertices; j++)
            printf("%d ", graph[i][j]);
        printf("\n");
    }
}

int main() {
    int vertices = 4;
    int graph[MAX][MAX];
    initMatrix(graph, vertices);
    addEdge(graph, 0, 1);
    addEdge(graph, 0, 2);
    addEdge(graph, 1, 2);
    addEdge(graph, 2, 3);
    
    printf("Adjacency Matrix:\n");
    displayMatrix(graph, vertices);
    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class Graph {
public:
    int** matrix;
    int vertices;

    Graph(int v) {
        vertices = v;
        matrix = new int*[vertices];
        for (int i = 0; i < vertices; i++) {
            matrix[i] = new int[vertices]{0}; // Initialize to 0
        }
    }

    void addEdge(int u, int v) {
        matrix[u][v] = 1; // For undirected graph, also add matrix[v][u] = 1;
    }

    void display() {
        for (int i = 0; i < vertices; i++) {
            for (int j = 0; j < vertices; j++)
                cout << matrix[i][j] << " ";
            cout << endl;
        }
    }

    ~Graph() {
        for (int i = 0; i < vertices; i++)
            delete[] matrix[i];
        delete[] matrix;
    }
};

int main() {
    Graph g(4);
    g.addEdge(0, 1);
    g.addEdge(0, 2);
    g.addEdge(1, 2);
    g.addEdge(2, 3);
    
    cout << "Adjacency Matrix:" << endl;
    g.display();
    return 0;
}
```

**Java Code**
```java
class Graph {
    private int[][] matrix;
    private int vertices;

    public Graph(int v) {
        vertices = v;
        matrix = new int[vertices][vertices];
    }

    public void addEdge(int u, int v) {
        matrix[u][v] = 1; // For undirected graph, also add matrix[v][u] = 1;
    }

    public void display() {
        for (int i = 0; i < vertices; i++) {
            for (int j = 0; j < vertices; j++)
                System.out.print(matrix[i][j] + " ");
            System.out.println();
        }
    }

    public static void main(String[] args) {
        Graph g = new Graph(4);
        g.addEdge(0, 1);
        g.addEdge(0, 2);
        g.addEdge(1, 2);
        g.addEdge(2, 3);
        
        System.out.println("Adjacency Matrix:");
        g.display();
    }
}
```

**Python Code**
```python
class Graph:
    def __init__(self, vertices):
        self.vertices = vertices
        self.matrix = [[0] * vertices for _ in range(vertices)]

    def add_edge(self, u, v):
        self.matrix[u][v] = 1  # For undirected graph, also add self.matrix[v][u] = 1

    def display(self):
        for row in self.matrix:
            print(" ".join(map(str, row)))

# Usage
g = Graph(4)
g.add_edge(0, 1)
g.add_edge(0, 2)
g.add_edge(1, 2)
g.add_edge(2, 3)

print("Adjacency Matrix:")
g.display()
```

---

### 2. Adjacency List

**C Code**
```c
#include <stdio.h>
#include <stdlib.h>

struct Node {
    int vertex;
    struct Node* next;
};

struct Graph {
    int vertices;
    struct Node** adjList;
};

struct Node* createNode(int v) {
    struct Node* newNode = (struct Node*)malloc(sizeof(struct Node));
    newNode->vertex = v;
    newNode->next = NULL;
    return newNode;
}

struct Graph* createGraph(int vertices) {
    struct Graph* graph = (struct Graph*)malloc(sizeof(struct Graph));
    graph->vertices = vertices;
    graph->adjList = malloc(vertices * sizeof(struct Node*));
    for (int i = 0; i < vertices; i++)
        graph->adjList[i] = NULL;
    return graph;
}

void addEdge(struct Graph* graph, int src, int dest) {
    struct Node* newNode = createNode(dest);
    newNode->next = graph->adjList[src];
    graph->adjList[src] = newNode; // For undirected, add the reverse edge as well
}

void display(struct Graph* graph) {
    for (int i = 0; i < graph->vertices; i++) {
        struct Node* temp = graph->adjList[i];
        printf("Vertex %d: ", i);
        while (temp) {
            printf("-> %d ", temp->vertex);
            temp = temp->next;
        }
        printf("\n");
    }
}

int main() {
    int vertices = 4;
    struct Graph* graph = createGraph(vertices);
    addEdge(graph, 0, 1);
    addEdge(graph, 0, 2);
    addEdge(graph, 1, 2);
    addEdge(graph, 2, 3);
    
    printf("Adjacency List:\n");
    display(graph);
    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
#include <vector>
using namespace std;

class Graph {
    int vertices;
    vector<vector<int>> adjList;

public:
    Graph(int v) {
        vertices = v;
        adjList.resize(v);
    }

    void addEdge(int u, int v) {
        adjList[u].push_back(v); // For undirected graph, add adjList[v].push_back(u);
    }

    void display() {
        for (int i = 0; i < vertices; i++) {
            cout << "Vertex " << i << ": ";
            for (int j : adjList[i])
                cout << "-> " << j << " ";
            cout << endl;
        }
    }
};

int main() {
    Graph g(4);
    g.addEdge(0, 1);
    g.addEdge(0, 2);
    g.addEdge(1, 2);
    g.addEdge(2, 3);
    
    cout << "Adjacency List:" << endl;
    g.display();
    return 0;
}
```

**Java Code**
```java
import java.util.ArrayList;

class Graph {
    private int vertices;
    private ArrayList<ArrayList<Integer>> adjList;

    public Graph(int v) {
        vertices = v;
        adjList = new ArrayList<>(v);
        for (int i = 0; i < v; i++)
            adjList.add(new ArrayList<>());
    }

    public void addEdge(int u, int v) {
        adjList.get(u).add(v); // For undirected, also add adjList.get(v).add(u);
    }

    public void display() {
        for (int i = 0; i < vertices; i++) {
            System.out.print("Vertex " + i + ": ");
            for (int j : adjList.get(i))
                System.out.print("-> " + j + " ");
            System.out.println();
        }
    }

    public static void main(String[] args) {
        Graph g = new Graph(4);
        g.addEdge(0, 1);
        g.addEdge(0, 2);
        g.addEdge(1, 2);
        g.addEdge(2, 3);
        
        System.out.println("Adjacency List:");
        g.display();
    }
}
```

**Python Code**
```python
class Graph:
    def __init__(self, vertices):
        self.vertices = vertices
        self.adj_list = [[] for _ in range(vertices)]

    def add_edge(self, u, v):
        self.adj_list[u].append(v)  # For undirected graph, also append v to u's list

    def display(self):
        for i in range(self.vertices):
            print(f"Vertex {i}: {' '.join('-> ' + str(j) for j in self.adj_list[i])}")

# Usage
g = Graph(4)
g.add_edge(0, 1)
g.add_edge(0, 2)
g.add_edge(1, 2)
g.add_edge(

2, 3)

print("Adjacency List:")
g.display()
```

---

### 3. Edge List

**C Code**
```c
#include <stdio.h>

struct Edge {
    int src, dest;
};

void displayEdgeList(struct Edge edges[], int edgeCount) {
    for (int i = 0; i < edgeCount; i++)
        printf("Edge %d: %d -> %d\n", i, edges[i].src, edges[i].dest);
}

int main() {
    int edgeCount = 4;
    struct Edge edges[edgeCount];

    edges[0].src = 0; edges[0].dest = 1;
    edges[1].src = 0; edges[1].dest = 2;
    edges[2].src = 1; edges[2].dest = 2;
    edges[3].src = 2; edges[3].dest = 3;

    printf("Edge List:\n");
    displayEdgeList(edges, edgeCount);
    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
#include <vector>
using namespace std;

class Edge {
public:
    int src, dest;
};

class Graph {
    vector<Edge> edges;

public:
    void addEdge(int src, int dest) {
        Edge edge = {src, dest};
        edges.push_back(edge);
    }

    void display() {
        for (int i = 0; i < edges.size(); i++)
            cout << "Edge " << i << ": " << edges[i].src << " -> " << edges[i].dest << endl;
    }
};

int main() {
    Graph g;
    g.addEdge(0, 1);
    g.addEdge(0, 2);
    g.addEdge(1, 2);
    g.addEdge(2, 3);

    cout << "Edge List:" << endl;
    g.display();
    return 0;
}
```

**Java Code**
```java
import java.util.ArrayList;

class Edge {
    int src, dest;

    Edge(int s, int d) {
        src = s;
        dest = d;
    }
}

class Graph {
    private ArrayList<Edge> edges;

    public Graph() {
        edges = new ArrayList<>();
    }

    public void addEdge(int src, int dest) {
        edges.add(new Edge(src, dest));
    }

    public void display() {
        for (int i = 0; i < edges.size(); i++)
            System.out.println("Edge " + i + ": " + edges.get(i).src + " -> " + edges.get(i).dest);
    }

    public static void main(String[] args) {
        Graph g = new Graph();
        g.addEdge(0, 1);
        g.addEdge(0, 2);
        g.addEdge(1, 2);
        g.addEdge(2, 3);

        System.out.println("Edge List:");
        g.display();
    }
}
```

**Python Code**
```python
class Edge:
    def __init__(self, src, dest):
        self.src = src
        self.dest = dest

class Graph:
    def __init__(self):
        self.edges = []

    def add_edge(self, src, dest):
        self.edges.append(Edge(src, dest))

    def display(self):
        for i, edge in enumerate(self.edges):
            print(f"Edge {i}: {edge.src} -> {edge.dest}")

# Usage
g = Graph()
g.add_edge(0, 1)
g.add_edge(0, 2)
g.add_edge(1, 2)
g.add_edge(2, 3)

print("Edge List:")
g.display()
```

---

### 4. Incidence Matrix

**C Code**
```c
#include <stdio.h>

#define MAX 10

void initIncidenceMatrix(int matrix[MAX][MAX], int edges, int vertices) {
    for (int i = 0; i < edges; i++)
        for (int j = 0; j < vertices; j++)
            matrix[i][j] = 0; // Initialize to 0
}

void addEdge(int matrix[MAX][MAX], int edgeIndex, int u, int v) {
    matrix[edgeIndex][u] = 1; // Start vertex
    matrix[edgeIndex][v] = -1; // End vertex
}

void displayMatrix(int matrix[MAX][MAX], int edges, int vertices) {
    for (int i = 0; i < edges; i++) {
        for (int j = 0; j < vertices; j++)
            printf("%d ", matrix[i][j]);
        printf("\n");
    }
}

int main() {
    int vertices = 4, edges = 4;
    int matrix[MAX][MAX];
    initIncidenceMatrix(matrix, edges, vertices);
    
    addEdge(matrix, 0, 0, 1);
    addEdge(matrix, 1, 0, 2);
    addEdge(matrix, 2, 1, 2);
    addEdge(matrix, 3, 2, 3);
    
    printf("Incidence Matrix:\n");
    displayMatrix(matrix, edges, vertices);
    return 0;
}
```

**C++ Code**
```cpp
#include <iostream>
using namespace std;

class Graph {
    int vertices, edges;
    int** matrix;

public:
    Graph(int v, int e) : vertices(v), edges(e) {
        matrix = new int*[edges];
        for (int i = 0; i < edges; i++)
            matrix[i] = new int[vertices]{0}; // Initialize to 0
    }

    void addEdge(int edgeIndex, int u, int v) {
        matrix[edgeIndex][u] = 1;   // Start vertex
        matrix[edgeIndex][v] = -1;  // End vertex
    }

    void display() {
        for (int i = 0; i < edges; i++) {
            for (int j = 0; j < vertices; j++)
                cout << matrix[i][j] << " ";
            cout << endl;
        }
    }

    ~Graph() {
        for (int i = 0; i < edges; i++)
            delete[] matrix[i];
        delete[] matrix;
    }
};

int main() {
    Graph g(4, 4);
    g.addEdge(0, 0, 1);
    g.addEdge(1, 0, 2);
    g.addEdge(2, 1, 2);
    g.addEdge(3, 2, 3);
    
    cout << "Incidence Matrix:" << endl;
    g.display();
    return 0;
}
```

**Java Code**
```java
class Graph {
    private int vertices, edges;
    private int[][] matrix;

    public Graph(int v, int e) {
        vertices = v;
        edges = e;
        matrix = new int[edges][vertices];
    }

    public void addEdge(int edgeIndex, int u, int v) {
        matrix[edgeIndex][u] = 1;   // Start vertex
        matrix[edgeIndex][v] = -1;  // End vertex
    }

    public void display() {
        for (int i = 0; i < edges; i++) {
            for (int j = 0; j < vertices; j++)
                System.out.print(matrix[i][j] + " ");
            System.out.println();
        }
    }

    public static void main(String[] args) {
        Graph g = new Graph(4, 4);
        g.addEdge(0, 0, 1);
        g.addEdge(1, 0, 2);
        g.addEdge(2, 1, 2);
        g.addEdge(3, 2, 3);
        
        System.out.println("Incidence Matrix:");
        g.display();
    }
}
```

**Python Code**
```python
class Graph:
    def __init__(self, vertices, edges):
        self.vertices = vertices
        self.edges = edges
        self.matrix = [[0] * vertices for _ in range(edges)]

    def add_edge(self, edge_index, u, v):
        self.matrix[edge_index][u] = 1   # Start vertex
        self.matrix[edge_index][v] = -1  # End vertex

    def display(self):
        for row in self.matrix:
            print(" ".join(map(str, row)))

# Usage
g = Graph(4, 4)
g.add_edge(0, 0, 1)
g.add_edge(1, 0, 2)
g.add_edge(2, 1, 2)
g.add_edge(3, 2, 3)

print("Incidence Matrix:")
g.display()
```

---

These implementations cover all four graph representations across C, C++, Java, and Python. 
# Divide and  Conquer
### Divide and Conquer Approach

**Definition:**
Divide and conquer is an algorithmic paradigm that involves dividing a problem into smaller subproblems, solving each subproblem independently, and combining their solutions to solve the original problem.

### Steps:
1. **Divide**: Break the problem into smaller subproblems.
2. **Conquer**: Solve the subproblems recursively.
3. **Combine**: Merge the solutions of the subproblems to get the solution to the original problem.

### Examples

#### 1. Merge Sort
**Description**: A sorting algorithm that uses the divide and conquer strategy.

**Algorithm**:
1. Divide the array into two halves.
2. Recursively sort both halves.
3. Merge the sorted halves.

**Code Example**:
```python
def merge_sort(arr):
    if len(arr) > 1:
        mid = len(arr) // 2
        left_half = arr[:mid]
        right_half = arr[mid:]

        merge_sort(left_half)
        merge_sort(right_half)

        i = j = k = 0

        while i < len(left_half) and j < len(right_half):
            if left_half[i] < right_half[j]:
                arr[k] = left_half[i]
                i += 1
            else:
                arr[k] = right_half[j]
                j += 1
            k += 1

        while i < len(left_half):
            arr[k] = left_half[i]
            i += 1
            k += 1

        while j < len(right_half):
            arr[k] = right_half[j]
            j += 1
            k += 1

# Example usage
arr = [38, 27, 43, 3, 9, 82, 10]
merge_sort(arr)
print("Sorted array:", arr)
```

#### 2. Quick Sort
**Description**: Another sorting algorithm that uses divide and conquer.

**Algorithm**:
1. Choose a pivot element.
2. Partition the array into two halves based on the pivot.
3. Recursively sort the partitions.

**Code Example**:
```python
def quick_sort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quick_sort(left) + middle + quick_sort(right)

# Example usage
arr = [38, 27, 43, 3, 9, 82, 10]
sorted_arr = quick_sort(arr)
print("Sorted array:", sorted_arr)
```
### Strassen's Matrix Multiplication

Strassen's algorithm improves the standard matrix multiplication algorithm by reducing the number of recursive multiplications needed. It divides each matrix into four submatrices and recursively computes the product.

**Algorithm Steps:**
1. If the matrix size is 1, return the product of the single element.
2. Divide each matrix into four submatrices.
3. Calculate seven products using the submatrices.
4. Combine these products to get the final result.

### Implementation in Different Languages

#### C Code
```c
#include <stdio.h>
#include <stdlib.h>

void add(int A[2][2], int B[2][2], int C[2][2]) {
    for (int i = 0; i < 2; i++)
        for (int j = 0; j < 2; j++)
            C[i][j] = A[i][j] + B[i][j];
}

void subtract(int A[2][2], int B[2][2], int C[2][2]) {
    for (int i = 0; i < 2; i++)
        for (int j = 0; j < 2; j++)
            C[i][j] = A[i][j] - B[i][j];
}

void strassen(int A[2][2], int B[2][2], int C[2][2]) {
    int M1[2][2], M2[2][2], M3[2][2], M4[2][2], M5[2][2], M6[2][2], M7[2][2];
    int A1[2][2], A2[2][2], B1[2][2], B2[2][2];

    // Divide matrices into submatrices
    A1[0][0] = A[0][0]; A1[0][1] = A[0][1];
    A1[1][0] = A[1][0]; A1[1][1] = A[1][1];
    
    B1[0][0] = B[0][0]; B1[0][1] = B[0][1];
    B1[1][0] = B[1][0]; B1[1][1] = B[1][1];

    // Calculate M1 to M7
    int temp1[2][2], temp2[2][2];
    
    add(A1, A1, temp1);
    add(B1, B1, temp2);
    strassen(temp1, temp2, M1);
    
    // Implement similar calculations for M2 to M7...

    // Combine results into C
    // C = M1 + M4 - M5 + M7
    // And so on for other positions...
}

int main() {
    int A[2][2] = {{1, 2}, {3, 4}};
    int B[2][2] = {{5, 6}, {7, 8}};
    int C[2][2];

    strassen(A, B, C);
    
    printf("Resultant Matrix:\n");
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 2; j++)
            printf("%d ", C[i][j]);
        printf("\n");
    }
    return 0;
}
```

#### C++ Code
```cpp
#include <iostream>
using namespace std;

void add(int A[2][2], int B[2][2], int C[2][2]) {
    for (int i = 0; i < 2; i++)
        for (int j = 0; j < 2; j++)
            C[i][j] = A[i][j] + B[i][j];
}

void subtract(int A[2][2], int B[2][2], int C[2][2]) {
    for (int i = 0; i < 2; i++)
        for (int j = 0; j < 2; j++)
            C[i][j] = A[i][j] - B[i][j];
}

void strassen(int A[2][2], int B[2][2], int C[2][2]) {
    int M1[2][2], M2[2][2], M3[2][2], M4[2][2], M5[2][2], M6[2][2], M7[2][2];
    int A1[2][2], A2[2][2], B1[2][2], B2[2][2];

    // Divide matrices into submatrices
    A1[0][0] = A[0][0]; A1[0][1] = A[0][1];
    A1[1][0] = A[1][0]; A1[1][1] = A[1][1];

    B1[0][0] = B[0][0]; B1[0][1] = B[0][1];
    B1[1][0] = B[1][0]; B1[1][1] = B[1][1];

    // Calculate M1 to M7
    int temp1[2][2], temp2[2][2];

    add(A1, A1, temp1);
    add(B1, B1, temp2);
    strassen(temp1, temp2, M1);
    
    // Implement similar calculations for M2 to M7...

    // Combine results into C
    // C = M1 + M4 - M5 + M7
    // And so on for other positions...
}

int main() {
    int A[2][2] = {{1, 2}, {3, 4}};
    int B[2][2] = {{5, 6}, {7, 8}};
    int C[2][2];

    strassen(A, B, C);
    
    cout << "Resultant Matrix:\n";
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 2; j++)
            cout << C[i][j] << " ";
        cout << endl;
    }
    return 0;
}
```

#### Java Code
```java
class Strassen {
    static void add(int[][] A, int[][] B, int[][] C) {
        for (int i = 0; i < 2; i++)
            for (int j = 0; j < 2; j++)
                C[i][j] = A[i][j] + B[i][j];
    }

    static void subtract(int[][] A, int[][] B, int[][] C) {
        for (int i = 0; i < 2; i++)
            for (int j = 0; j < 2; j++)
                C[i][j] = A[i][j] - B[i][j];
    }

    static void strassen(int[][] A, int[][] B, int[][] C) {
        int[][] M1 = new int[2][2], M2 = new int[2][2], M3 = new int[2][2], M4 = new int[2][2], M5 = new int[2][2], M6 = new int[2][2], M7 = new int[2][2];
        int[][] A1 = {{A[0][0], A[0][1]}, {A[1][0], A[1][1]}};
        int[][] B1 = {{B[0][0], B[0][1]}, {B[1][0], B[1][1]}};

        // Calculate M1 to M7
        int[][] temp1 = new int[2][2], temp2 = new int[2][2];

        add(A1, A1, temp1);
        add(B1, B1, temp2);
        strassen(temp1, temp2, M1);
        
        // Implement similar calculations for M2 to M7...

        // Combine results into C
        // C = M1 + M4 - M5 + M7
        // And so on for other positions...
    }

    public static void main(String[] args) {
        int[][] A = {{1, 2}, {3, 4}};
        int[][] B = {{5, 6}, {7, 8}};
        int[][] C = new int[2][2];

        strassen(A, B, C);
        
        System.out.println("Resultant Matrix:");
        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++)
                System.out.print(C[i][j] + " ");
            System.out.println();
        }
    }
}
```

#### Python Code
```python
def add(A, B):
    return [[A[i][j] + B[i][j] for j in range(2)] for i in range(2)]

def subtract(A, B):
    return [[A[i

][j] - B[i][j] for j in range(2)] for i in range(2)]

def strassen(A, B):
    if len(A) == 1:
        return [[A[0][0] * B[0][0]]]

    A1 = A
    B1 = B

    M1 = strassen(add(A1, A1), add(B1, B1))
    # Implement similar calculations for M2 to M7...

    # Combine results into C
    # C = M1 + M4 - M5 + M7
    return C  # Placeholder for actual result

A = [[1, 2], [3, 4]]
B = [[5, 6], [7, 8]]
C = strassen(A, B)

print("Resultant Matrix:")
for row in C:
    print(" ".join(map(str, row)))
```

### Note:
The provided codes for Strassen's algorithm are not fully implemented for M2 to M7 and the final combination of matrices, but they illustrate the basic structure and approach. You can expand upon this structure to fully implement the algorithm. 

### Summary
The divide and conquer approach is a powerful technique that can significantly optimize algorithms, as shown in sorting and matrix multiplication. Strassen's algorithm for matrix multiplication is particularly noteworthy for its efficiency compared to traditional methods. 
# Greedy Algorithms

### Greedy Algorithm

**Definition:**
A greedy algorithm is an approach for solving optimization problems by making a sequence of choices, each of which looks best at the moment. It builds up a solution piece by piece, choosing the next piece with the most immediate benefit without considering the overall consequences.

**Key Characteristics:**

1. **Locally Optimal Choice:**
   - At each step, the algorithm selects the best option available without regard for future consequences.

2. **Irrevocable Decisions:**
   - Once a choice is made, it cannot be undone, which differentiates greedy algorithms from other approaches like dynamic programming.

3. **Feasibility:**
   - The selected choice must satisfy the constraints of the problem to ensure that it contributes to a valid solution.

4. **Optimality:**
   - Greedy algorithms do not always produce the globally optimal solution for all problems, but they can be efficient for certain classes of problems.

5. **Efficiency:**
   - Greedy algorithms often have lower time complexity compared to exhaustive search methods, making them suitable for larger inputs.

### Common Applications:
Greedy algorithms are widely used in various domains, including:

- **Optimization Problems:** Problems where the goal is to maximize or minimize some value.
- **Graph Algorithms:** Such as Prim’s and Kruskal’s algorithms for minimum spanning trees.
- **Scheduling Problems:** Tasks where resources are allocated to maximize efficiency.

### Conclusion:
While greedy algorithms can be powerful and efficient, they are not universally applicable. Understanding the problem context is crucial to determining if a greedy approach will yield the correct solution.
### Examples

#### 1. Coin Change Problem
**Problem**: Given denominations of coins and a total amount, find the minimum number of coins needed to make that amount.

**Algorithm**:
1. Sort the coin denominations in descending order.
2. Start from the largest denomination and use as many coins as possible without exceeding the amount.
3. Subtract the value of the used coins from the total amount until the amount reaches zero.

**Code Example (Python)**:
```python
def coin_change(coins, amount):
    coins.sort(reverse=True)
    count = 0
    for coin in coins:
        while amount >= coin:
            amount -= coin
            count += 1
    return count

# Example usage
coins = [1, 5, 10, 25]
amount = 63
print("Minimum coins needed:", coin_change(coins, amount))
```

#### 2. Activity Selection Problem
**Problem**: Given a set of activities with their start and finish times, select the maximum number of activities that don't overlap.

**Algorithm**:
1. Sort the activities by their finish times.
2. Select the first activity and then iterate through the list, selecting an activity only if it starts after the last selected activity finishes.

**Code Example (Python)**:
```python
def activity_selection(start, finish):
    activities = sorted(zip(start, finish), key=lambda x: x[1])
    selected = [activities[0]]

    last_finish = activities[0][1]
    for i in range(1, len(activities)):
        if activities[i][0] >= last_finish:
            selected.append(activities[i])
            last_finish = activities[i][1]
    
    return selected

# Example usage
start = [1, 3, 0, 5, 8, 5]
finish = [2, 4, 6, 7, 9, 9]
selected_activities = activity_selection(start, finish)
print("Selected activities:", selected_activities)
```

#### 3. Huffman Coding
**Problem**: Construct a binary tree for optimal prefix codes based on the frequency of characters.

**Algorithm**:
1. Create a priority queue with nodes for each character, sorted by frequency.
2. While there is more than one node in the queue:
   - Extract the two nodes with the lowest frequencies.
   - Create a new internal node with these two nodes as children and a frequency equal to their sum.
   - Insert this new node back into the queue.
3. The remaining node is the root of the Huffman tree.

**Code Example (Python)**:
```python
import heapq
from collections import defaultdict

class Node:
    def __init__(self, char, freq):
        self.char = char
        self.freq = freq
        self.left = None
        self.right = None

    def __lt__(self, other):
        return self.freq < other.freq

def huffman_coding(chars):
    heap = [Node(char, freq) for char, freq in chars.items()]
    heapq.heapify(heap)

    while len(heap) > 1:
        left = heapq.heappop(heap)
        right = heapq.heappop(heap)
        merged = Node(None, left.freq + right.freq)
        merged.left = left
        merged.right = right
        heapq.heappush(heap, merged)

    return heap[0]

# Example usage
char_freq = {'a': 5, 'b': 9, 'c': 12, 'd': 13, 'e': 16, 'f': 45}
root = huffman_coding(char_freq)
print("Huffman tree constructed.")
```

### Summary
Greedy algorithms are efficient and straightforward, often used in optimization problems. They work well when a problem exhibits the greedy choice property and optimal substructure. However, they may not always yield the best solution for every problem, so it's essential to analyze the problem requirements before choosing this approach. If you need more examples or a specific application, let me know!









