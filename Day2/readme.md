# Python Programming - Operators

## 1. Name Binding

Whenever we give `a = 5`:

```text
a = 5

 +-----+
 |  5  |  <- block in memory, name of the block = a
 +-----+
```

- One block is created in memory which is holding `5`.
- The name of the block is given as `a`.
- So the value `5` is associated with the name `a`. We call it **name binding** in programming.

---

## 2. Operators

### 2.1 What is an Operator?

**Example:**

```python
5 + 6
```

```text
5   +   6
|   |   |
|   |   operand
|   operator -> what type of operation you have to perform
operand
```

**Definition:**

- `+` -> operator.
- `5` and `6` -> operands.
- An operator is a special symbol which is used to perform operations.

### 2.2 Types of Operators

Python has various operators:

1. Arithmetic operators
2. Comparison or relational operators
3. Logical operators
4. Assignment operators
5. Bitwise operators
6. Identity operators
7. Membership operators

---

## 3. Arithmetic Operators

### 3.1 List of Arithmetic Operators

| Operator | Meaning |
|:--------:|---------|
| `+`  | addition |
| `-`  | subtraction |
| `*`  | multiplication |
| `/`  | division |
| `//` | floor division |
| `%`  | modulus |
| `**` | power |

### 3.2 Division, Floor Division and Modulus

- `/` --> normal division -> exact quotient.
- `//` --> floor division -> least integer value of the quotient.
- `%` --> modulus --> returns the remainder.

**Example:**

```python
5/2
```

### 3.3 Priority and Associativity

**Example:**

```python
4*5+6-4*2
```

Every operator has two things:

1. Priority
2. Associativity

| Operators | Priority | Associativity |
|-----------|:--------:|:-------------:|
| `**`                | 1 | right |
| `*`, `/`, `//`, `%` | 2 | left  |
| `+`, `-`            | 3 | left  |

---

## 4. Relational or Comparison Operators

### 4.1 What are Relational Operators?

```python
a, b
a > b
a < b
a == b   # -> chromaticity property
```

### 4.2 List of Relational Operators

| Operator | Meaning |
|:--------:|---------|
| `>`  | greater than |
| `<`  | less than |
| `>=` | greater than or equal to |
| `<=` | less than or equal to |
| `==` | equal to |
| `!=` | not equal to |

**Important Point:**

- Relational operators always give a **boolean** answer.

**Example (chained comparison):**

```text
12 > 13 > 15  ->  (12 > 13) and (13 < 15)

False and True -> False
```

### 4.3 Priority and Associativity

| Operators | Priority | Associativity |
|-----------|:--------:|:-------------:|
| `**`                             | 1 | right |
| `*`, `/`, `//`, `%`              | 2 | left  |
| `+`, `-`                         | 3 | left  |
| `>`, `<`, `>=`, `<=`, `==`, `!=` | 4 | left  |

**Example:**

```text
23*2 > 4+7*2
46 > 4+14
46 > 18   ->  True
```

---

## 5. Logical Operators

### 5.1 What are Logical Operators?

- Logical operators are used to combine two or more conditions or expressions.

```text
num > 10     num < 20
   c1           c2

num > 10 and num < 20
```

- We have three types of logical operators:

1. `and`
2. `or`
3. `not`

### 5.2 Logical AND (`and`)

**Definition:**

- Logical `and` is True when all the conditions are True, otherwise it will be False.

| exp1  | exp2  | exp1 and exp2 |
|-------|-------|---------------|
| True  | True  | **True**      |
| True  | False | False         |
| False | True  | False         |
| False | False | False         |

**Important Point:**

- Every non-zero value is considered as True. Only zero is considered as False.

### 5.3 Logical OR (`or`)

**Definition:**

- `or` is False when all the conditions are False, otherwise it will be True.

| exp1  | exp2  | exp1 or exp2 |
|-------|-------|--------------|
| True  | True  | True         |
| True  | False | True         |
| False | True  | True         |
| False | False | **False**    |

### 5.4 Logical NOT (`not`)

**Definition:**

- The `not` operator is used to invert the value.

```text
True  -> False
False -> True
```

---

## 6. Operator Priority and Associativity (Complete)

| Operators | Priority | Associativity |
|-----------|:--------:|:-------------:|
| `**`                             | 1 | right |
| `*`, `/`, `//`, `%`              | 2 | left  |
| `+`, `-`                         | 3 | left  |
| `>`, `<`, `>=`, `<=`, `==`, `!=` | 4 | left  |
| `and`                            | 5 | left  |
| `or`                             | 6 | left  |

---

## 7. Bitwise Operators

### 7.1 Number Systems

**Definition:**

- Base -> how many numbers are present in that number system (NS).

| # | Number System | Base | Digits / Symbols |
|---|---------------|:----:|------------------|
| 1 | Unary       | 1  | Only one number is present -> `0` |
| 2 | Binary      | 2  | `0`, `1` |
| 3 | Octal       | 8  | `0` to `7` |
| 4 | Decimal     | 10 | `0` to `9` |
| 5 | Hexadecimal | 16 | `0` to `9`, then `A` to `F` |

**Unary Example:**

```text
1 -> 0
2 -> 00
3 -> 000
```

**Hexadecimal Example:**

```text
A = 10, ... , F = 15
```

### 7.2 Prefixes

**Example:**

```text
26 ->
```

| Number System | Prefix |
|---------------|--------|
| Octal         | `0o` |
| Hexadecimal   | `0x` |
| Binary        | digits `0`, `1` (prefix `0b`) |
| Decimal       | any other (no prefix) |

### 7.3 Conversions

```text
decimal -> binary  -> D/2
decimal -> octal   -> D/8
decimal -> hex     -> D/16

any other -> decimal
```
