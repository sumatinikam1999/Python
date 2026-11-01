
# Python Programming - Fundamentals

## 1. Programming

### What is a Language?

- Language is a mode of communication.

**Communication between two persons:**

```text
Person 1 ----------> Person 2
             |
          Language
      (Natural Language)
```

**Communication between a person and a computer:**

```text
Person ----------> Computer
             |
     Programming Language
```

- Programming language -> It is a special kind of instructions which is used to communicate with a computer.

### Problem: Language Difference

Example:

```text
Person 1          Person 2
English           Hindi
```

```text
       Person
          |
       English
          |
        Hindi
```

### How Does a Computer Understand?

- Computer -> Binary
- Computer is an electronic device.
- It understands signals (positive or negative), that is, 1 and 0.

```text
Computer -> Binary -> 1 and 0
```

### Programming Language Example

- Python is an example of a programming language.

```text
Person              Computer
Python              Binary
```

**Translator:**

```text
Python -> Binary -> Compiler -> Software
```

### Grammar and Syntax

- English -> Language
- Grammar -> Set of rules.
- Python -> Grammar -> Syntax rules.

---

## 2. Process of Learning a Language

### Example: English

1. Alphabet
2. Words
3. Sentences
4. Paragraphs

### Example: Programming Language

1. Character Sets
2. Tokens
3. Instructions
4. Program

---

## 3. Basic Programming Terminology

- Program
- Process
- Algorithms
- Procedure

### 3.1 Algorithm

**Definition:**

- Step-by-step instructions to solve any problem (finite number of steps).

**Problem Statement:**

Example: Make Coffee.

Steps:

1. Take a pan.
2. Add milk.
3. Add coffee powder.
4. Boil it.

### 3.2 Procedure

**Definition:**

- Procedure: Finite step-by-step instructions.

**Example:**

```text
Boy ---> Girl

1. Sense of humar
2. Dressing sense
3. etc
```

### 3.3 Program

- Set of instructions.
- Program is recided in hard disk.

---

## 4. Stored Program Concept

**Definition:**

- To execute any program, we need to save it.

### Program Execution Process

```text
Program stored in Hard Disk
             |
             v
To execute the program, we need to load it into Memory
             |
             v
Operating System has a program called Loader
             |
             v
Loader loads the program into Memory (RAM)
             |
             v
Program contains multiple Processes
             |
             v
Processes contain multiple Instructions
             |
             v
One Instruction contains multiple Micro Instructions
             |
             v
CPU will be able to execute one Micro Instruction
per Clock Cycle
```

### Important Points

- Program won't be loaded as a single program (has multiple processes).
- It gets divided into multiple processes and gets loaded into memory (RAM).
- When a program gets loaded in memory, we can say it as program under execution.

**Process:**

- Process -> Program under execution.

---

## 5. Python

Python:

1. Character Set
2. Tokens
3. Instruction
4. Program

---

## 6. Character Set

### What is a Character Set?

**Example: English**

- English -> A-Z
- `gr8` -> Not a valid English word.
- 26 characters.
- Example: `elephant`

**Example: Python**

- Python -> Alphabets -> 128 characters.
- If any Python code is going beyond this 128 characters, we called it as invalid Python code.

Examples:

```text
A-Z
a-z
0-9
. : "" '
```

---

## 7. Tokens

### What is a Token?

- Token is the smallest individual unit in program.
- Without token we cannot write any Python code.
- We are having a 6 types of token in Python:

### Types of Tokens

1. Keywords
2. Identifier
3. Operators
4. Separators
5. Data Types
6. Constants

---

### 1 Keywords

**Definition:**

- Predefined word / Reserved words.
- Whose meaning is automatically recognized by the compiler.

**Example:**

```text
What is your name?

if
```

- Python is having a 35 keywords.

---

### 2 Identifier

**Definition:**

- Name given in the programming language.

**Example:**

```python
a = 5
```

- `a` -> Variable name.

**Other Examples:**

- Data structure -> `1st_name`, `tuple_name` etc.
- `function_name`
- Class name
- etc.

**Important Points:**

- Identifier is used to identify a data.
- There are rules for writing the identifier:

### Rules for Writing an Identifier

1. Identifier contains alphabets (`a-z`, `A-Z`), numbers (`0-9`) and only one special symbol (`_`).

2. Identifier should starts with a alphabets or special symbol underscore, it should not starts with a number.

3. Identifier should not be a keywords.

4. Python is a case sensitive.

   **Example:**

   ```python
   if
   IF
   If
   iF
   ```

   - All meanings are different.

5. The length of the identifier is upto any number of characters but compiler will recognized upto a specific length.
