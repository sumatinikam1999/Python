# Python - Day 2

## Name Binding

Whenever we give `a = 5`:

- One block is created in memory which is holding `5`.
- Giving the name of the block as `a`.
- So that value `5` associated with name `a` is called **Name Binding** in programming.

## 3. Operators

Example:

`5 + 6`

- `+` -> Operator
- `5` and `6` -> Operands
- It is a special symbol which is used to perform an operation.

Python has various operators:

1. Arithmetic operators
2. Comparison or relational operators
3. Logical operators
4. Assignment operators
5. Bitwise operators
6. Identity operators
7. Membership operators

### 1. Arithmetic Operators

| Operators | Meanings |
|-----------|----------|
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `//` | Floor division |
| `%` | Modulus |
| `**` | Power |

- `/` -> Normal division -> Exact quotient
- `//` -> Floor division -> Least integer value of quotient
- `%` -> Modulus -> Returns the remainder

Example:

`5 / 2`

Every operator is having two things:

1. Priority
2. Associativity

| Operators | Priority | Associativity |
|-----------|----------|---------------|
| `**` | 1 | Right |
| `*`, `/`, `//`, `%` | 2 | Left |
| `+`, `-` | 3 | Left |

Example:

`5 + 6 - 4`

### 2. Relational or Comparison Operators

`a, b`

`a > b`

`a < b`

`a == b` -> Equality operator

| Operators | Meanings |
|-----------|----------|
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |
| `==` | Equal to |
| `!=` | Not equal to |

- Relational operators are always giving the Boolean answer (`True` or `False`).

Example:

`12 > 13 > 15`

It is evaluated as:

`(12 > 13) and (13 > 15)`

`False and False -> False`

| Operators | Priority | Associativity |
|-----------|----------|---------------|
| `**` | 1 | Right |
| `*`, `/`, `//`, `%` | 2 | Left |
| `+`, `-` | 3 | Left |
| `>`, `<`, `>=`, `<=`, `==`, `!=` | 4 | Left |

Example:

`2 ** 3 > 4 + 7 ** 2`

Step-by-step:

```text
8 > 4 + 49
8 > 53
False