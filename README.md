# 🐍 Python Basics – Beginner Notes

## 1. Print Statement

```python
print('hello world')
```

* `print` is a **function**
* `()` are used to call the function
* Python is an **interpreted language**, so no boilerplate code is required
* Java & C are **compiled languages**

---

## 2. Variables

```python
manesh = 12
print(manesh)
```

* Variable name is on the **left side**
* Value is on the **right side**

❌ Invalid

```python
1a = 12
```

✅ Valid

```python
a1 = 12
```

Rules:

* Cannot start with a number
* Can use numbers after letters

---

## 3. Data Types in Python

### 1️⃣ Numbers

* `int` → `1, 2, -1`
* `float` → `23.32`
* `complex` → `15j`

```python
b = 123
print(type(b))  # int
```

```python
a = 12 / 6
print(type(a))  # float
```

```python
d = 15j
print(type(d))  # complex
```

### 2️⃣ Boolean

```python
True, False
```

### 3️⃣ String

```python
words = 'apple'
```

---

## 4. Type Checking & Type Conversion

### 🔍 type()

Used to check the data type

```python
type(10)
```

### 🔄 Type Conversion

Convert one data type into another

Functions:

* `int()`
* `float()`
* `str()`
* `bool()`

Example:

```python
a = '12'
a = int(a)
```

```python
r = 23.4
r = int(r)  # 23
```

```python
s = 124
s = str(s)
```

---

## 5. Truthy & Falsy Values

### ✅ Truthy Values

* Non‑empty strings
* Non‑zero numbers
* Collections with values

### ❌ Falsy Values

* `False`
* `None`
* `0`, `0.0`
* `''`
* `[]`

---

## 6. Input Function

```python
name = input('Tell me your name: ')
age = int(input('What is your age: '))
```

📌 Note:

* `input()` always returns **string**

---

## 7. Escape Characters

| Character | Meaning     |
| --------- | ----------- |
| `\n`      | New line    |
| `\t`      | Tab (space) |
| `\b`      | Backspace   |

Example:

```python
print('My name is Akarsh\nMy brother age is 25')
```

### Raw String

```python
print(r'To end a line use \n')
```

* Escape characters are printed as text

---

## 8. Formatted String (f-string)

```python
medical = 'Vit C'
price = 10

print(f'To fresh your face use {medical} and price is {price}')
```

---

## 9. Arithmetic Operators

| Operator | Meaning          |
| -------- | ---------------- |
| `+`      | Addition         |
| `-`      | Subtraction      |
| `*`      | Multiplication   |
| `/`      | Division (float) |
| `//`     | Floor Division   |
| `%`      | Remainder        |
| `**`     | Power            |

Examples:

```python
print(35 / 7)   # float
print(35 // 7)  # int
print(5 ** 2)   # 25
print(12 % 7)   # 5
```

📌 `% 10` gives the **last digit**

---

## 10. Comparison Operators

| Operator | Meaning          |
| -------- | ---------------- |
| `==`     | Equal            |
| `!=`     | Not equal        |
| `>`      | Greater than     |
| `<`      | Less than        |
| `>=`     | Greater or equal |
| `<=`     | Less or equal    |

Example:

```python
a = 100
b = 200
print(b > a)
```

---

## 11. Logical Operators

* `and` → All conditions must be true
* `or` → Any one true
* `not` → Reverse the result

Example:

```python
print(12 < 13 and 34 > 23)
print(not 12 > 5)  # False
```

---

✅ **These notes are beginner‑friendly and Markdown ready (.md)**
