Data Structures - List, Dictionary, Set 
& Conditional Statements 

## 📌 Overview

This assignment focuses on fundamental Python concepts related to **List, Dictionary, Set, and Conditional Statements**.

The objective is to understand how different Python data structures are created, modified, accessed, and used in practical programs.

## 🧠 Topics Covered

* Lists
* List Creation and Modification
* List Indexing and Slicing
* List Methods
* Dictionaries
* Dictionary Creation and Modification
* Dictionary Methods
* Sets
* Set Operations
* Union and Intersection
* `if`, `elif`, and `else`
* User Input
* Performance Categorization

---

## 1. List

### List Creation

Created an `age_list` containing five integer values and a `name_list` containing five names.

```python
age_list = [24, 25, 26, 27, 28]

name_list = ["yash", "krish", "nani", "bunny", "deepu"]
```

### List Operations

The following operations were performed:

* `append()` – Add an element to the end of a list.
* `insert()` – Add an element at a specific index.
* `remove()` – Remove a specific element.
* `pop()` – Remove the last element.
* `extend()` – Add multiple elements.
* `sort()` – Arrange elements in descending order.
* `max()` – Find the maximum value.
* `min()` – Find the minimum value.
* `sum()` – Calculate the total of numeric values.

### List Access

Examples of accessing list elements:

```python
print(name_list[0])      # First element
print(name_list[-1])     # Last element
print(name_list[2:5])    # Elements from index 2 to 4
print(name_list[::-1])   # Reverse order
```

---

## 2. Dictionary

A dictionary named `student_marks` was created to store student names and their marks.

```python
student_marks = {
    yash: 85,
    krish: 76,
    nani: 92,
    bunny: 68,
    deepu: 74
}
```

### Dictionary Operations

The following operations were performed:

* Access a student's mark.
* Add a new student.
* Update an existing student's mark.
* Display keys.
* Display values.
* Display key-value pairs.

```python
print(student_marks.keys())
print(student_marks.values())
print(student_marks.items())
```

---

## 3. Sets

A set was created using vowel values:

```python
my_set = {'a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'}

print(my_set)
```

### Observation

The output contains only unique values because **sets do not allow duplicate elements**.

The duplicate `a` and `i` values are automatically removed.

Sets are also **unordered**, so the output order may vary.

### Set Indexing

Attempting:

```python
my_set[4] = 's'
```

produces an error because sets do not support indexing or item assignment.

### Union and Intersection

Two sets were created:

```python
set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}
```

Union:

```python
set1 | set2
```

Intersection:

```python
set1 & set2
```

The **union** contains all unique elements from both sets, while the **intersection** contains elements common to both sets.

---

## 4. Conditional Statements

A performance category program was created using:

* `if`
* `elif`
* `else`

The user enters a score between **0 and 10**.

### Performance Criteria

| Score          | Category      |
| -------------- | ------------- |
| Greater than 7 | Above Average |
| 4 to 7         | Average       |
| Less than 4    | Below Average |

### Example

```python
score = float(input("Enter your score (0 to 10): "))

if score < 0 or score > 10:
    print("Invalid score. Please enter a score between 0 and 10.")

elif score > 7:
    print("Above Average: Excellent performance!")

elif score >= 4:
    print("Average: Good effort! Keep practicing.")

else:
    print("Below Average: Consistent practice will lead to better results.")
```

### Sample Output

```text
Enter your score (0 to 10): 7
Average: Good effort! Keep practicing.
```

---

## 🎯 Learning Outcomes

After completing this assignment, I learned:

* How to create and modify Python lists.
* How to access list elements using indexes and slicing.
* How to use common list methods.
* How to create and modify dictionaries.
* How to use dictionary methods such as `keys()`, `values()`, and `items()`.
* How sets handle duplicate values.
* How to perform union and intersection operations.
* Why sets do not support indexing.
* How to use `if`, `elif`, and `else`.
* How to accept and validate user input.
* How to build a simple performance classification program.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook / Google Colab**
* **GitHub**

## 📂 Repository Structure

```text
Python-Assignment-2/
│
├── Python_Assignment_2.ipynb
└── README.md
```

## 👩‍💻 Author

**Y Ramya Krishna**

BTech Graduate | Aspiring Data Analyst
