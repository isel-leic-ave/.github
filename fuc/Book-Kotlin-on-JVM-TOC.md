1. **Introduction to the JVM**
   1. Virtual Machines
      1. Abstraction and Execution
      2. Managed Runtime Environment
      3. Java Ecosystem
      4. Java to Nowadays
   2. JVM Foundations
   3. Class Loader, CLASSPATH and Interoperability
   4. Modules
   5. Central Repository and Dependency Management
   6. Exercises

2. **Type Basics**
   1. JVM Type Fundamentals
      1. Primitive Types
      2. Reference Types
      3. Members
      4. Nested Types
   2. Kotlin to Java type system
      1. Kotlin Class Members
   3. Conversions and Casting
      1. Primitive Numeric Conversions
      2. Reference Type Casting
      3. Boxing and Unboxing
   4. Abstract and Base Types
   5. Anonymous classes
   6. Kotlin Object declarations
   7. Kotlin Function types
      1. Lambdas Translation in former Kotlin 1.x
   8. Exercises

3. **Reflection**
   1. Kotlin Reflection
   2. A Simple Logger Using Kotlin Reflection
   3. Java Reflection
   4. Checking Type Compatibility
   5. NaiveMapper: automatic object to object mapper
      1. NaiveMapper Motivation
      2. NaiveMapper Implementation
   6. Annotations
   7. Reflection of generic types
   8. Reflection Overhead and the Enhancement of NaiveMapper
      1. Reflection Overhead
      2. Enhancing the NaiveMapper
   9. Exercises

4. **Performance testing and Microbenchmarking**
   1. Performance Measurement Pitfalls
   2. JMH
   3. Exercises

5. **Bytecode and the Just-in-time Compiler**
   1. Evaluation Stack
   2. Constant Pool and Descriptors
   3. Bytecode for Comparison and Control Flow
   4. Managing Instances and Members
      1. Creating Objects
      2. Accessing Fields
      3. Invoking Methods
   5. Method Dispatch Internals
   6. Exceptions
      1. Throwable, Exception, and Error
      2. Checked and Unchecked Exceptions
      3. Throwing an Exception
      4. Catching Exceptions
      5. Stack Unwinding
      6. Finally Blocks
      7. Stack Traces as Runtime Artifacts
      8. Uncaught Exceptions
   7. Exercises

6. **Metaprogramming**
   1. Introduction
   2. Class-File API
   3. Dynamic Mapper
   4. Build-time Mapper
      1. Build-time Mapper API
      2. Gradle Plugin Basics
      3. Gradle `MapperPlugin`
   5. Exercises

7. **Sequences, Generators and Suspending functions**
   1. Sequence Alternatives
      1. Operation names
      2. Composability: *method chaining* versus *nested functions*
      3. *Eager* versus *lazy* evaluation
      4. Extensibility
      5. Access approach: *pull* versus *push*
   2. Generators and yield pattern
   3. Suspend functions
   4. Deconstructing yield and generators
      1. Translating a Suspend Function into a State Machine
      2. `sequence` builder
   5. Exercises

8. **Garbage Collection and Cleanup Actions**
   1. Memory Foundations: Stack versus Heap
   2. Manual Memory Management
   3. Automatically Identifying Alive Objects
   4. Garbage Collection Techniques
   5. Types Requiring Special Cleanup
      1. Using closeable types
      2. Finalization and Cleaners
   6. Exercises