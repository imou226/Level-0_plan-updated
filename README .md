# C# .NET Level 0 — 3-Month Learning and Interview Plan

> **3-Month Learning Plan** | From Zero to OOP-Ready, with SQL and LeetCode interview preparation

---

## Goal

Learn C# from scratch, covering language fundamentals, OOP, Collections, and Generics before moving to LINQ. The plan combines guided sessions, w3resource exercises, mini projects, SQL practice, and beginner-friendly LeetCode interview questions.

## Learning Rules

- Watch the assigned videos before starting the exercises.
- Write and understand every solution. Copying solutions from the internet without understanding them is not accepted.
- Be ready to explain any submitted solution during a live session or meeting.
- Keep solutions in one console project or in clearly named `.cs` files.
- Add a comment above every exercise with the exercise number, source, and link.
- Submit a link to the repository containing all solutions.
- Recommended interview pace: **2 LeetCode questions and 3 SQL questions per week**.

---

## Timeline Overview

| Sprint | Duration | Main C# Focus | Interview Track |
|---|---:|---|---|
| Sprint 1 | Week 1–2 | Setup, Variables, Types, Operators, Conditions | SQL basics + simple logic questions |
| Sprint 2 | Week 3–4 | Loops + Arrays | SQL filtering + array questions |
| Sprint 3 | Week 5–6 | Strings + Functions + Math + Recursion | SQL aggregation + string questions |
| Sprint 4 | Week 7–8 | Exceptions + Files + Sorting + Regex + DateTime | SQL joins + searching/sorting questions |
| Sprint 5 | Week 9–10 | OOP Part 1 | SQL subqueries + hash-table questions |
| Sprint 6 | Week 11–12 | OOP Part 2 + Collections + Generics | SQL review + mixed mock interview |

---

## Sprint 1 — Setup and C# Basics

**Duration:** Week 1–2 | **Guided Sessions:** Setup and C# Fundamentals

**Goal:** Prepare the development environment and write C# programs using types, operators, console input/output, and conditions.

### Setup Checklist

- [ ] Install .NET 8 SDK
- [ ] Install Visual Studio 2022 Community, or VS Code with the C# Dev Kit extension
- [ ] Create a `Solution` and a Console `Project`
- [ ] Understand the difference between a solution and a project
- [ ] Run a first C# console application

### Topics to Master

- Variables and data types: `int`, `double`, `string`, `bool`, `char`
- Type casting and conversion
- Arithmetic, comparison, and logical operators
- `Console.WriteLine()` and `Console.ReadLine()`
- `if`, `else if`, `else`, and `switch`
- Ternary operator

### Required w3resource Exercises

| Topic | Exercises | Target |
|---|---|---:|
| Basic | [104 exercises](https://www.w3resource.com/csharp-exercises/basic/index.php) | First 50 |
| Data Types | [11 exercises](https://www.w3resource.com/csharp-exercises/data-types/index.php) | All 11 |
| Conditional Statements | [25 exercises](https://www.w3resource.com/csharp-exercises/conditional-statement/index.php) | All 25 |

### SQL Interview Preparation

- Database, table, row, column, primary key, and foreign key
- `CREATE DATABASE`, `CREATE TABLE`, `INSERT`, `SELECT`
- `WHERE`, comparison operators, `AND`, `OR`, `NOT`
- Interview questions:
  1. What is the difference between a primary key and a foreign key?
  2. What is the difference between `WHERE` and `HAVING`?
  3. Write a query that returns employees whose salary is greater than 5,000.
  4. Write a query that returns distinct department names.

### LeetCode Interview Questions

- [Fizz Buzz](https://leetcode.com/problems/fizz-buzz/)
- [Palindrome Number](https://leetcode.com/problems/palindrome-number/)
- [Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/)
- [Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/)

---

## Sprint 2 — Loops and Arrays

**Duration:** Week 3–4 | **Guided Session:** Loops and Arrays

**Goal:** Master iteration, nested loops, patterns, and one-dimensional and two-dimensional arrays.

### Topics to Master

- `for`, `while`, `do-while`, and `foreach`
- Loop control using `break` and `continue`
- Nested loops and drawing patterns
- One-dimensional arrays
- Two-dimensional arrays
- Built-in array methods: `Sort`, `Reverse`, `Max`, `Min`

### Required w3resource Exercises

| Topic | Exercises | Target |
|---|---|---:|
| Basic | [104 exercises](https://www.w3resource.com/csharp-exercises/basic/index.php) | Exercises 51–104 |
| For Loop | [83 exercises](https://www.w3resource.com/csharp-exercises/for-loop/index.php) | All 83 |
| Array | [41 exercises](https://www.w3resource.com/csharp-exercises/array/index.php) | All 41 |

### SQL Interview Preparation

- `ORDER BY`, `TOP`, `DISTINCT`, `LIKE`, `IN`, `BETWEEN`, `IS NULL`
- Interview questions:
  1. How do `NULL` and an empty string differ?
  2. Write a query to return the three highest salaries.
  3. Write a query to return names beginning with `A`.
  4. Write a query to return orders created between two dates.

### LeetCode Interview Questions

- [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/)
- [Two Sum](https://leetcode.com/problems/two-sum/)
- [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
- [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
- [Move Zeroes](https://leetcode.com/problems/move-zeroes/)

---

## Sprint 3 — Strings, Functions, Math, and Recursion

**Duration:** Week 5–6 | **Guided Sessions:** Strings and Functions

**Goal:** Process text, build reusable methods, use mathematical functions, and understand recursion.

### Live Sessions and Meetings

- [ ] Attend Live Session 1: Strings
- [ ] Attend Live Session 2: Functions
- [ ] Attend the stand-up meeting
- [ ] Attend the end-of-sprint meeting

> Attend both live sessions on their scheduled dates. The sessions provide the foundation for the practical exercises in this sprint.

### Topics to Master

- String methods: `ToUpper`, `ToLower`, `Trim`, `Replace`, `Substring`, `Split`, `Contains`, `StartsWith`, `EndsWith`, `IndexOf`
- String formatting and interpolation
- Methods: parameters, return types, and overloading
- Value parameters, `ref`, and `out`
- Optional and named parameters
- `Math`: `Pow`, `Sqrt`, `Abs`, `Round`, `Max`, `Min`
- Recursion: base case and recursive case

### Required w3resource Exercises

| Topic | Exercises | Required Target |
|---|---|---:|
| String | [68 exercises](https://www.w3resource.com/csharp-exercises/string/index.php) | Minimum 20; stretch goal all 68 |
| Function | [10 exercises](https://www.w3resource.com/csharp-exercises/function/index.php) | All 10 |
| Math | [24 exercises](https://www.w3resource.com/csharp-exercises/math/index.php) | All 24 |
| Recursion | [15 exercises](https://www.w3resource.com/csharp-exercises/recursion/index.php) | All 15 |

### Submission Requirements

- [ ] Solve a minimum of 20 string exercises
- [ ] Solve all 10 function exercises
- [ ] Solve all 24 math exercises
- [ ] Complete the assigned recursion exercises
- [ ] Organize solutions in one console project or clearly named `.cs` files
- [ ] Add an exercise number, source, and link comment to every solution
- [ ] Share the repository link containing all solutions

> **Time-management tip:** Start with the string exercises because this is the largest set. Continue with function exercises after the second live session.

### SQL Interview Preparation

- `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- `GROUP BY` and `HAVING`
- Interview questions:
  1. What is the difference between `COUNT(*)` and `COUNT(column)`?
  2. Write a query to calculate the average salary per department.
  3. Write a query to return departments with more than five employees.
  4. Write a query to return the highest salary in each department.

### LeetCode Interview Questions

- [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
- [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
- [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)
- [Reverse String](https://leetcode.com/problems/reverse-string/)
- [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)

---

## Sprint 4 — Exceptions, Files, Algorithms, Regex, and DateTime

**Duration:** Week 7–8 | **Guided Session:** Core Utilities and Algorithms

**Goal:** Handle errors and files, implement core algorithms, validate text, and work with dates and times.

### Topics to Master

- Exception handling: `try`, `catch`, `finally`, `throw`, custom exceptions
- File handling: `File`, `StreamReader`, `StreamWriter`, `using`
- Linear and binary search
- Bubble and selection sort
- Regular expressions and pattern matching
- `DateTime` formatting and arithmetic
- `struct`
- `Stack<T>`: `Push`, `Pop`, `Peek`
- Introductory Big-O notation: `O(1)`, `O(n)`, `O(log n)`, `O(n²)`

### Required w3resource Exercises

| Topic | Exercises | Target |
|---|---|---:|
| Exception Handling | [13 exercises](https://www.w3resource.com/csharp-exercises/exception-handling/index.php) | All 13 |
| File Handling | [15 exercises](https://www.w3resource.com/csharp-exercises/file-handling/index.php) | All 15 |
| Searching and Sorting | [11 exercises](https://www.w3resource.com/csharp-exercises/searching-and-sorting-algorithm/index.php) | All 11 |
| Regular Expression | [9 exercises](https://www.w3resource.com/csharp-exercises/regular-expression/index.php) | All 9 |
| Date Time | [57 exercises](https://www.w3resource.com/csharp-exercises/datetime/index.php) | All 57 |
| Structure | [10 exercises](https://www.w3resource.com/csharp-exercises/structure/index.php) | All 10 |
| Stack | [27 exercises](https://www.w3resource.com/csharp-exercises/stack/index.php) | All 27 |

### SQL Interview Preparation

- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, and self join
- Interview questions:
  1. What is the difference between `INNER JOIN` and `LEFT JOIN`?
  2. Write a query to display every employee with a department name.
  3. Write a query to find customers who have not placed an order.
  4. Write a self-join query that displays employees and their managers.

### LeetCode Interview Questions

- [Binary Search](https://leetcode.com/problems/binary-search/)
- [Search Insert Position](https://leetcode.com/problems/search-insert-position/)
- [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
- [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)
- [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/)

---

## Sprint 5 — OOP Part 1

**Duration:** Week 9–10 | **Guided Session:** Classes and Inheritance

**Goal:** Design classes and apply encapsulation, inheritance, overriding, and polymorphism.

### Topics to Master

- Classes and objects
- Fields, methods, and properties
- Default, parameterized, and copy constructors
- `this` keyword
- Encapsulation and access modifiers: `public`, `private`, `protected`, `internal`
- Getters, setters, validation, and auto-properties
- `static` keyword
- Inheritance and the `base` keyword
- Method overriding with `virtual` and `override`
- Compile-time and runtime polymorphism
- Composition versus inheritance

### Mini Project: Student Management System

- Create a `Person` base class and a `Student` derived class.
- Store each student's name, age, and GPA.
- Validate properties using encapsulation.
- Add a method to display student information and calculate a grade.
- Store multiple students and provide search and summary functions.

### SQL Interview Preparation

- Subqueries, correlated subqueries, `EXISTS`, and `NOT EXISTS`
- Interview questions:
  1. What is the difference between a join and a subquery?
  2. Write a query to return employees earning more than the company average.
  3. Write a query to return the second-highest salary.
  4. Write a query to find duplicate email addresses.

### LeetCode Interview Questions

- [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
- [Majority Element](https://leetcode.com/problems/majority-element/)
- [Single Number](https://leetcode.com/problems/single-number/)
- [Ransom Note](https://leetcode.com/problems/ransom-note/)
- [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/)

---

## Sprint 6 — OOP Part 2, Collections, and Generics

**Duration:** Week 11–12 | **Guided Session:** Abstraction and Collections

**Goal:** Complete OOP fundamentals and use generic collections to build a complete application.

### Topics to Master

- Abstract classes and methods
- Interfaces and multiple-interface implementation
- `sealed` classes and methods
- `List<T>`
- `Dictionary<TKey, TValue>`
- `Queue<T>` and FIFO
- `Stack<T>` and LIFO
- `HashSet<T>` and uniqueness
- Generic methods and classes
- Generic constraints such as `where T : IComparable<T>` and `where T : new()`
- `IEnumerable<T>` basics
- Introductory LINQ readiness: collections, lambdas, and predicates

### Mini Project: Library System

- Create an abstract `LibraryItem` class inherited by `Book` and `Magazine`.
- Create an `ISearchable` interface with a `Search()` method.
- Use `List<Book>` to store books.
- Use `Dictionary<string, Book>` to search by title.
- Use a queue for borrowing requests.
- Prevent duplicate identifiers with `HashSet<T>`.
- Add exception handling and file persistence.

### SQL Interview Preparation

- Normalization basics: 1NF, 2NF, 3NF
- Indexes, views, stored procedures, transactions, and ACID basics
- Mixed interview questions:
  1. What problem does normalization solve?
  2. What is an index, and what trade-off does an index introduce?
  3. What is a transaction?
  4. Explain the ACID properties.
  5. Write a query to rank salaries within each department.

### LeetCode Interview Questions

- [Group Anagrams](https://leetcode.com/problems/group-anagrams/)
- [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
- [Min Stack](https://leetcode.com/problems/min-stack/)
- [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/)
- [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

### Final Mock Interview

- [ ] Explain one C# fundamentals solution without running the code
- [ ] Solve one array or string problem in 30–40 minutes
- [ ] Explain the time and space complexity
- [ ] Answer five OOP questions
- [ ] Write three SQL queries, including one join and one aggregate query
- [ ] Demonstrate one mini project and explain design decisions

---

## Common C# Interview Questions

1. What is the difference between value types and reference types?
2. What is boxing and unboxing?
3. What is the difference between `const`, `readonly`, and `static`?
4. What is method overloading versus method overriding?
5. What is encapsulation, and why is it useful?
6. What is the difference between an abstract class and an interface?
7. What is the difference between `List<T>` and an array?
8. What is the difference between `Dictionary<TKey, TValue>` and `HashSet<T>`?
9. What is the purpose of generics?
10. What is the difference between `throw` and `throw ex`?
11. What is the purpose of the `using` statement?
12. What is polymorphism? Give a C# example.
13. What is the difference between composition and inheritance?
14. What are access modifiers in C#?
15. What is Big-O notation, and why is it important?

---

## Repository Structure

```text
Level-0-Plan/
├── README.md
├── Sprint-01-Basics/
├── Sprint-02-Loops-Arrays/
├── Sprint-03-Strings-Functions/
├── Sprint-04-Core-Utilities/
├── Sprint-05-OOP-Part-1/
├── Sprint-06-OOP-Part-2/
├── SQL-Practice/
├── LeetCode/
└── Projects/
    ├── Student-Management-System/
    └── Library-System/
```

## Submission Method

1. Push all solutions to the student's repository.
2. Keep folders and files clearly named.
3. Ensure each exercise includes its number and source link in a comment.
4. Update the progress tracker below.
5. Submit the repository link.

---

## Progress Tracker

### Sprint 1
- [ ] Environment setup completed
- [ ] Basic: ___/104
- [ ] Data Types: ___/11
- [ ] Conditional Statements: ___/25
- [ ] SQL questions: ___/4
- [ ] LeetCode: ___/4

### Sprint 2
- [ ] For Loop: ___/83
- [ ] Array: ___/41
- [ ] SQL questions: ___/4
- [ ] LeetCode: ___/5

### Sprint 3
- [ ] String: ___/68
- [ ] Function: ___/10
- [ ] Math: ___/24
- [ ] Recursion: ___/15
- [ ] SQL questions: ___/4
- [ ] LeetCode: ___/5

### Sprint 4
- [ ] Exception Handling: ___/13
- [ ] File Handling: ___/15
- [ ] Searching and Sorting: ___/11
- [ ] Regular Expression: ___/9
- [ ] Date Time: ___/57
- [ ] Structure: ___/10
- [ ] Stack: ___/27
- [ ] SQL questions: ___/4
- [ ] LeetCode: ___/5

### Sprint 5
- [ ] Student Management System completed
- [ ] SQL questions: ___/4
- [ ] LeetCode: ___/5

### Sprint 6
- [ ] Library System completed
- [ ] SQL questions: ___/5
- [ ] LeetCode: ___/5
- [ ] Final mock interview completed

---

## Milestones

| Week | Milestone |
|---:|---|
| 2 | Development environment and C# basics completed |
| 4 | Loops and arrays completed; first interview set solved |
| 6 | Strings, functions, math, and recursion completed |
| 8 | Core utilities, algorithms, regex, and DateTime completed |
| 10 | OOP Part 1 and Student Management System completed |
| 12 | OOP Part 2, collections, generics, SQL review, mock interview, and Library System completed |

---

*C# .NET Track — Level 0 | 3-Month Learning and Interview Plan*
