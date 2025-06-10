# Java-vs-C-Concurrent-Counter-Performance-Security-Analysis
A side-by-side analysis of Java and C++ implementations of a multithreaded counter. This project explores thread synchronization, memory management, and the performance/security trade-offs between high-level (Java) and low-level (C++) concurrency models.
# Java vs C++ Concurrent Programming: Performance and Security Comparison

## Overview

This project compares concurrent counter implementations in **Java** and **C++**, with a focus on **thread management**, **synchronization**, **memory safety**, and **performance/security trade-offs**.

###  Java Implementation
The Java version uses `Thread`, `synchronized` blocks, and `wait/notify` for thread coordination. Two threads increment and decrement a shared counter while using a lock object to control access.

###  Comparative Analysis
- **Java** offers a higher-level abstraction, easing development but introducing some overhead.
- **C++** gives finer control with lower-level thread primitives and manual memory management, offering better performance but higher risk of errors.
- Security trade-offs, memory management, and data race risks are also discussed.

## Files Included
- `Main.java` - Java implementation of the concurrent counter.
- `Java_Concurrency_Report.pdf` - Full write-up of Java vs C++ comparison (performance & security).
- `screenshot.png` - Output of the running Java code.

## How to Run (Java)
1. Open your IDE (like IntelliJ or Eclipse).
2. Create a Java project and add the `Main.java` file.
3. Run the file to see the counter increment/decrement in the console.

## Output Example
