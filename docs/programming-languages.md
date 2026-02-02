# CS50’s Computer Science for Business Professionals  
## Lecture: Programming Languages — Summary

---

## 1. What Does It Mean to Program a Computer?

- Programming is the act of **writing instructions** that tell a computer what to do.
- These instructions are written in **programming languages**, which are:
  - More readable for humans
  - Ultimately translated into something the computer understands
- Although there are **many programming languages**, most share the same **core concepts**.

> Once you understand the fundamentals, you can transfer that knowledge to almost any language.

---

## 2. Fundamental Programming Constructs

Most programming languages are built on a small set of core ideas:

### 2.1 Functions
- Represent **actions** or **procedures**
- Example (conceptual):  
  - `move()` → tells the computer to perform an action
- Functions are **verb-like**: they *do* something

---

### 2.2 Loops
- Used to **repeat actions**
- Avoid repetition and make programs more concise
- Examples:
  - Repeat something a fixed number of times
  - Repeat forever (infinite loop)

⚠️ Infinite loops can be:
- **Useful** (e.g., clocks, animations)
- **Problematic** (e.g., frozen programs, high CPU usage)

---

### 2.3 Variables
- Store **values** that can change over time
- Similar to variables in algebra (`x`, `y`)
- Often named descriptively:
  - `counter`, `score`, `steps`

Used to:
- Track progress
- Count iterations
- Store state

---

### 2.4 Conditions
- Allow programs to make **decisions**
- Built around the keyword **if**
- Example logic:
  - *If* you’re about to walk off the stage, *stop*

Conditions prevent errors and enable smarter behavior.

---

### 2.5 Boolean Expressions
- Expressions that evaluate to:
  - `true` or `false`
- Examples:
  - Is the object touching the edge?
  - Is the value greater than 10?

Named after **George Boole**.

---

## 3. Programming as Translation

Programming is fundamentally about:
- Translating **human intentions**
- Into **formal instructions**
- That computers can execute

Computers natively understand:
- **Binary (0s and 1s)**
- A small set of **CPU instructions**

Everything else is layered on top.

---

## 4. Visual Programming with Scratch

### 4.1 Why Scratch?
- Graphical, block-based programming language
- Removes syntax complexity
- Ideal for learning core concepts

Scratch demonstrates:
- Functions
- Loops
- Conditions
- Variables
- Events

---

### 4.2 Key Scratch Concepts

- **Sprites**: characters or objects that perform actions
- **Events**: e.g., *when green flag clicked*
- **Scripts area**: where logic is assembled
- **Puzzle pieces**: visual representation of code blocks

---

### 4.3 Example: Movement with Logic

A typical Scratch program might:
- Start when the green flag is clicked
- Move a sprite continuously (loop)
- Check if it’s touching the edge (condition)
- Turn around if necessary

This visually demonstrates:
- Control flow
- Loops + conditions working together
- Literal interpretation of instructions by the computer

---

### 4.4 Debugging and Iteration

- Computers do **exactly** what you tell them
- Bugs often come from:
  - Missing conditions
  - Incorrect logic
- Programming requires:
  - Testing
  - Incremental changes
  - Debugging

---

## 5. From Visual to Textual Languages

Scratch is a learning tool.
Most real-world programming uses **text-based languages**.

---

## 6. Low-Level vs High-Level Languages

### 6.1 C Language

- One of the earliest high-level languages
- Requires:
  - Explicit syntax
  - Curly braces
  - Semicolons
- Example task: printing “Hello, world”

#### Compilation Process:
1. **Source code** (written by humans)
2. **Compiler** (e.g., Clang, GCC)
3. **Machine code** (0s and 1s)

---

### 6.2 Python Language

- Higher-level and more human-readable
- Less syntax overhead
- Example:
  ```python
  print("hello, world")

#### Interpretation Process:

- Source code → Interpreter → Bytecode → Virtual Machine
- No explicit compilation step required by the programmer

## 7. Compilation vs Interpretation

Programming languages differ in how their code is translated into something a computer can execute.

### 7.1 Compiled Languages
- Example: **C**
- Code is translated **before execution**
- Process:
  1. Source code written by the programmer
  2. Compiler translates it into machine code
  3. The CPU executes the machine code directly

**Characteristics:**
- Faster execution
- More control over hardware
- Requires explicit compilation step
- Errors are caught before execution

---

### 7.2 Interpreted Languages
- Example: **Python**
- Code is translated **at runtime**
- Executed by an interpreter or virtual machine

**Characteristics:**
- Easier to write and read
- Faster development cycle
- Slightly slower execution
- Errors may appear while the program is running

---

### 7.3 Summary Table

| Aspect | Compiled Languages (C) | Interpreted Languages (Python) |
|-----|------------------------|-------------------------------|
| Translation Time | Before execution | During execution |
| Output | Machine code | Bytecode |
| Execution | Directly by CPU | Via interpreter |
| Performance | Generally faster | Generally slower |
| Ease of Use | More complex | More beginner-friendly |

---

## 8. Other Programming Languages

The lecture highlights that there are **many programming languages**, each designed with specific goals in mind.

### Examples Mentioned
- **C++** – Extension of C with object-oriented features
- **Java** – Widely used in enterprise systems
- **JavaScript** – Runs in browsers and servers
- **Ruby** – Emphasizes simplicity and readability
- **Lisp** – Functional programming paradigm

### Key Idea
- Languages vary in:
  - Syntax
  - Paradigm
  - Typical use cases
- However, they all rely on the **same core programming concepts**

---

## 9. Language Evolution and Transpilation

- Programming languages are constantly evolving
- New features are added over time
- Older systems may not support newer versions

### 9.1 Transpilation
- Process of converting code from:
  - One version of a language
  - Into another version of the *same* language
- Common in web development

**Example:**
- Modern JavaScript → Older JavaScript
- Ensures compatibility with older browsers

---

## 10. Key Takeaways

- Programming languages differ in **form**, not in **fundamentals**
- Core concepts appear everywhere:
  - Functions
  - Loops
  - Variables
  - Conditions
  - Boolean logic
- Computers follow instructions **literally**
- Debugging and iteration are essential parts of programming
- Learning one language well makes learning others much easier

---

## 11. What Comes Next

To build real-world software, additional knowledge is required:

- **Markup Languages** (e.g., HTML)
- **Web technologies**
- **Internet fundamentals**

These topics build directly on the programming concepts introduced in this lecture and enable the creation of complete applications.
