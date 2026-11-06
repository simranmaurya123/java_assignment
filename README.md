# Java Assignment Solutions

This repository contains comprehensive Java programming solutions across multiple modules covering core, advanced, multithreading, collections, and reflection concepts.

---

## 📁 Repository Structure

```text
java_assignment/
├── Module2/                             # Packages, Interfaces, Exception Handling & Lambdas
│   ├── question01_utilities/            # Packages & Imports
│   ├── question02_shapes/               # Packages & Interfaces
│   ├── question03_arraylist/            # java.util ArrayList
│   ├── question04_calculator/           # Functional Interface & Lambdas
│   ├── question05_string_sort/          # Lambda String Sorting
│   ├── question06_method_ref/           # Method References
│   ├── question07_exception_handling/   # try-catch vs try-catch-finally
│   ├── question08_custom_exception/     # Custom InvalidAgeException
│   ├── question09_logging_exception/    # File Logging via java.util.logging
│   └── question10_factorial_throw_throws/ # throw and throws Keywords
│
├── Module3/                             # Multithreading, Concurrency & File I/O
│   ├── Q1 - Q13/                        # Threads, Synchronization, ReentrantLock, Deadlocks
│   ├── Q14 - Q23/                       # Byte Streams, Character Streams, File Class, RandomAccessFile
│   └── Q24 - Q25/                       # java.lang.Math, java.util.Date/Calendar, Regex Validation
│
├── Module4/                             # Collections Framework & Stream API
│   └── Q1.java - Q46.java               # ArrayList, LinkedList, Set, Map, Queues, Iterators, Streams
│
└── Module5/                             # Custom Annotations & Reflection
    ├── Q17/                             # MinLength Validation
    ├── Q18/                             # Repeatable Annotations
    ├── Q21/                             # Custom Annotation MinLength Demo
    ├── Q22/                             # ClassInfo Annotation & Reflection
    ├── Q26/                             # JsonField Serialization Demo
    ├── Q28/                             # Reflection Annotation Parsing
    └── Q29/                             # ExecutionTime Performance Benchmark
```

---

## 📝 Modules Overview

### Module 2: Packages, Interfaces, Exception Handling & Lambdas
- **Packages & Imports**: Custom packages (`utilities.MathUtils`), package interfaces (`shapes.Shape` with `Circle` and `Rectangle`).
- **Lambdas & Functional Interfaces**: `Calculator` functional interface, lambda comparator for string sorting, static method references (`Main::calculateSquare`).
- **Exceptions**: `try-catch-finally` guarantees, custom `InvalidAgeException`, file error logging via `java.util.logging`, and `throw`/`throws` validation.

### Module 3: Multithreading, Locks, File I/O & Concurrency
- **Threads & Synchronization**: Thread lifecycle, producer-consumer pattern, odd-even printer, dining philosophers, ticket booking synchronization.
- **Lock Management**: `ReentrantLock` counter protection, deadlock simulation, and deadlock avoidance using `tryLock()`.
- **I/O Streams**: Byte streams (`FileInputStream`/`FileOutputStream`), Character streams (`FileReader`/`FileWriter`), `BufferedReader`, `File` operations, `RandomAccessFile`.
- **Utilities**: Regular expression validation (email pattern), `java.util.Date`, and `java.util.Calendar`.

### Module 4: Java Collections & Streams
- Comprehensive implementations covering `List`, `Set`, `Queue`, and `Map` interfaces.
- Generics, custom comparators, priority queues, and Java 8 Stream API data pipelines (filtering, mapping, reducing, collecting).

### Module 5: Annotations & Reflection
- Custom runtime annotations (`@ClassInfo`, `@MinLength`, `@JsonField`, `@ExecutionTime`).
- Reflection API for inspecting metadata, validating field constraints, measuring execution time, and parsing annotations dynamically.

---

## ⚙️ Compilation & Execution

Each folder/file is self-contained. To run any solution:

```bash
# Example for Module 2 questions
cd Module2/question01_utilities
javac utilities/*.java Main.java
java Main

# Example for Module 4 questions
cd Module4
javac Q1.java
java Q1

# Example for Module 5 questions
cd Module5/Q22
javac ClassInfoDemo.java
java ClassInfoDemo
```

---

## 👤 Author

- **Simran Maurya** ([@simranmaurya123](https://github.com/simranmaurya123))
