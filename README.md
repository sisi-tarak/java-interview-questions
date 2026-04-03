# Java Interview Questions & Answers

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level — Java Fundamentals

| No. | Questions |
| --- | --------- |
| 1 | [What is Java? What are its key features?](#1-what-is-java-what-are-its-key-features) |
| 2 | [What is the difference between JDK, JRE, and JVM?](#2-what-is-the-difference-between-jdk-jre-and-jvm) |
| 3 | [How does Java achieve platform independence?](#3-how-does-java-achieve-platform-independence) |
| 4 | [What are the primitive data types in Java?](#4-what-are-the-primitive-data-types-in-java) |
| 5 | [What is the difference between == and .equals() in Java?](#5-what-is-the-difference-between--and-equals-in-java) |
| 6 | [What is a wrapper class in Java?](#6-what-is-a-wrapper-class-in-java) |
| 7 | [What is autoboxing and unboxing?](#7-what-is-autoboxing-and-unboxing) |
| 8 | [What is the difference between String, StringBuilder, and StringBuffer?](#8-what-is-the-difference-between-string-stringbuilder-and-stringbuffer) |
| 9 | [Why is String immutable in Java?](#9-why-is-string-immutable-in-java) |
| 10 | [What is the String pool (String intern pool)?](#10-what-is-the-string-pool-string-intern-pool) |
| 11 | [What is the difference between stack memory and heap memory?](#11-what-is-the-difference-between-stack-memory-and-heap-memory) |
| 12 | [What are access modifiers in Java?](#12-what-are-access-modifiers-in-java) |
| 13 | [What is the final keyword in Java?](#13-what-is-the-final-keyword-in-java) |
| 14 | [What is the static keyword in Java?](#14-what-is-the-static-keyword-in-java) |
| 15 | [What is the difference between break, continue, and return?](#15-what-is-the-difference-between-break-continue-and-return) |

#### 🟢 Basic Level — OOP Concepts

| No. | Questions |
| --- | --------- |
| 16 | [What are the four pillars of OOP?](#16-what-are-the-four-pillars-of-oop) |
| 17 | [What is a class and an object in Java?](#17-what-is-a-class-and-an-object-in-java) |
| 18 | [What is encapsulation? How is it achieved?](#18-what-is-encapsulation-how-is-it-achieved) |
| 19 | [What is inheritance in Java?](#19-what-is-inheritance-in-java) |
| 20 | [What is polymorphism? Explain method overloading vs overriding](#20-what-is-polymorphism-explain-method-overloading-vs-overriding) |
| 21 | [What is abstraction? Difference between abstract class and interface?](#21-what-is-abstraction-difference-between-abstract-class-and-interface) |
| 22 | [What is a constructor in Java? Types of constructors?](#22-what-is-a-constructor-in-java-types-of-constructors) |
| 23 | [What is the this keyword in Java?](#23-what-is-the-this-keyword-in-java) |
| 24 | [What is the super keyword in Java?](#24-what-is-the-super-keyword-in-java) |
| 25 | [Can we override static methods in Java?](#25-can-we-override-static-methods-in-java) |

#### 🟡 Medium Level — Exception Handling

| No. | Questions |
| --- | --------- |
| 26 | [What is exception handling in Java?](#26-what-is-exception-handling-in-java) |
| 27 | [What is the difference between checked and unchecked exceptions?](#27-what-is-the-difference-between-checked-and-unchecked-exceptions) |
| 28 | [What is the difference between throw and throws?](#28-what-is-the-difference-between-throw-and-throws) |
| 29 | [What is the finally block? When does it not execute?](#29-what-is-the-finally-block-when-does-it-not-execute) |
| 30 | [What is try-with-resources in Java?](#30-what-is-try-with-resources-in-java) |
| 31 | [How do you create a custom exception?](#31-how-do-you-create-a-custom-exception) |
| 32 | [What is the difference between Error and Exception?](#32-what-is-the-difference-between-error-and-exception) |

#### 🟡 Medium Level — Collections Framework

| No. | Questions |
| --- | --------- |
| 33 | [What is the Java Collections Framework?](#33-what-is-the-java-collections-framework) |
| 34 | [What is the difference between ArrayList and LinkedList?](#34-what-is-the-difference-between-arraylist-and-linkedlist) |
| 35 | [What is the difference between HashMap, HashTable, and ConcurrentHashMap?](#35-what-is-the-difference-between-hashmap-hashtable-and-concurrenthashmap) |
| 36 | [How does HashMap work internally?](#36-how-does-hashmap-work-internally) |
| 37 | [What is the difference between HashSet and TreeSet?](#37-what-is-the-difference-between-hashset-and-treeset) |
| 38 | [What is the difference between Comparable and Comparator?](#38-what-is-the-difference-between-comparable-and-comparator) |
| 39 | [What is the difference between Iterator and ListIterator?](#39-what-is-the-difference-between-iterator-and-listiterator) |
| 40 | [What is a fail-fast vs fail-safe iterator?](#40-what-is-a-fail-fast-vs-fail-safe-iterator) |
| 41 | [When would you use LinkedHashMap vs HashMap?](#41-when-would-you-use-linkedhashmap-vs-hashmap) |
| 42 | [What is a PriorityQueue in Java?](#42-what-is-a-priorityqueue-in-java) |

#### 🟡 Medium Level — Java 8+ Features

| No. | Questions |
| --- | --------- |
| 43 | [What are the major features introduced in Java 8?](#43-what-are-the-major-features-introduced-in-java-8) |
| 44 | [What is a lambda expression in Java?](#44-what-is-a-lambda-expression-in-java) |
| 45 | [What is a functional interface? Name some built-in ones](#45-what-is-a-functional-interface-name-some-built-in-ones) |
| 46 | [What is the Stream API? How is it different from Collections?](#46-what-is-the-stream-api-how-is-it-different-from-collections) |
| 47 | [What is the difference between map() and flatMap() in streams?](#47-what-is-the-difference-between-map-and-flatmap-in-streams) |
| 48 | [What are intermediate and terminal operations in streams?](#48-what-are-intermediate-and-terminal-operations-in-streams) |
| 49 | [What is Optional in Java 8? Why is it used?](#49-what-is-optional-in-java-8-why-is-it-used) |
| 50 | [What are default and static methods in interfaces (Java 8)?](#50-what-are-default-and-static-methods-in-interfaces-java-8) |
| 51 | [What is the new Date/Time API in Java 8?](#51-what-is-the-new-datetime-api-in-java-8) |
| 52 | [What is a method reference in Java?](#52-what-is-a-method-reference-in-java) |

#### 🟡 Medium Level — Multithreading & Concurrency

| No. | Questions |
| --- | --------- |
| 53 | [What is multithreading in Java?](#53-what-is-multithreading-in-java) |
| 54 | [What are the ways to create a thread in Java?](#54-what-are-the-ways-to-create-a-thread-in-java) |
| 55 | [What is the thread lifecycle in Java?](#55-what-is-the-thread-lifecycle-in-java) |
| 56 | [What is the synchronized keyword?](#56-what-is-the-synchronized-keyword) |
| 57 | [What is a deadlock in Java? How do you prevent it?](#57-what-is-a-deadlock-in-java-how-do-you-prevent-it) |
| 58 | [What is the difference between wait(), notify(), and notifyAll()?](#58-what-is-the-difference-between-wait-notify-and-notifyall) |
| 59 | [What is the volatile keyword in Java?](#59-what-is-the-volatile-keyword-in-java) |
| 60 | [What is the ExecutorService in Java?](#60-what-is-the-executorservice-in-java) |
| 61 | [What is the difference between Callable and Runnable?](#61-what-is-the-difference-between-callable-and-runnable) |
| 62 | [What is the difference between synchronized and ReentrantLock?](#62-what-is-the-difference-between-synchronized-and-reentrantlock) |

#### 🟡 Medium Level — JVM Internals & Memory

| No. | Questions |
| --- | --------- |
| 63 | [What is garbage collection in Java?](#63-what-is-garbage-collection-in-java) |
| 64 | [What are the different types of garbage collectors in Java?](#64-what-are-the-different-types-of-garbage-collectors-in-java) |
| 65 | [What is the JVM memory model? Explain all memory areas](#65-what-is-the-jvm-memory-model-explain-all-memory-areas) |
| 66 | [What is a memory leak in Java? How do you detect it?](#66-what-is-a-memory-leak-in-java-how-do-you-detect-it) |
| 67 | [What is the difference between shallow copy and deep copy?](#67-what-is-the-difference-between-shallow-copy-and-deep-copy) |
| 68 | [What is serialization and deserialization in Java?](#68-what-is-serialization-and-deserialization-in-java) |
| 69 | [What is the transient keyword?](#69-what-is-the-transient-keyword) |

#### 🔴 Advanced Level — Design Patterns

| No. | Questions |
| --- | --------- |
| 70 | [What are design patterns? Name the most commonly asked ones](#70-what-are-design-patterns-name-the-most-commonly-asked-ones) |
| 71 | [What is the Singleton pattern? How do you implement it thread-safely?](#71-what-is-the-singleton-pattern-how-do-you-implement-it-thread-safely) |
| 72 | [What is the Factory pattern?](#72-what-is-the-factory-pattern) |
| 73 | [What is the Builder pattern?](#73-what-is-the-builder-pattern) |
| 74 | [What is the Observer pattern?](#74-what-is-the-observer-pattern) |
| 75 | [What is the Strategy pattern?](#75-what-is-the-strategy-pattern) |

#### 🔴 Advanced Level — Spring & Spring Boot

| No. | Questions |
| --- | --------- |
| 76 | [What is Spring Framework? What problem does it solve?](#76-what-is-spring-framework-what-problem-does-it-solve) |
| 77 | [What is dependency injection? What are its types?](#77-what-is-dependency-injection-what-are-its-types) |
| 78 | [What is Spring Boot? How is it different from Spring?](#78-what-is-spring-boot-how-is-it-different-from-spring) |
| 79 | [What are Spring Boot annotations you use most often?](#79-what-are-spring-boot-annotations-you-use-most-often) |
| 80 | [What is Spring MVC? How does a request flow through it?](#80-what-is-spring-mvc-how-does-a-request-flow-through-it) |
| 81 | [What is Spring Data JPA? How is it different from Hibernate?](#81-what-is-spring-data-jpa-how-is-it-different-from-hibernate) |
| 82 | [What is Spring Security? How do you secure a REST API?](#82-what-is-spring-security-how-do-you-secure-a-rest-api) |
| 83 | [What is application.properties vs application.yml in Spring Boot?](#83-what-is-applicationproperties-vs-applicationyml-in-spring-boot) |
| 84 | [What is the difference between @Component, @Service, @Repository, and @Controller?](#84-what-is-the-difference-between-component-service-repository-and-controller) |
| 85 | [What is Spring Boot Actuator?](#85-what-is-spring-boot-actuator) |

#### 🔴 Advanced Level — Java New Features (Java 9–21)

| No. | Questions |
| --- | --------- |
| 86 | [What are the major features introduced in Java 9 to Java 21?](#86-what-are-the-major-features-introduced-in-java-9-to-java-21) |
| 87 | [What are records in Java 16+?](#87-what-are-records-in-java-16) |
| 88 | [What are sealed classes in Java?](#88-what-are-sealed-classes-in-java) |
| 89 | [What are virtual threads in Java 21 (Project Loom)?](#89-what-are-virtual-threads-in-java-21-project-loom) |
| 90 | [What is pattern matching in Java?](#90-what-is-pattern-matching-in-java) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 91 | [What is the difference between an abstract class and an interface? When to use which?](#91-what-is-the-difference-between-an-abstract-class-and-an-interface-when-to-use-which) |
| 92 | [How does HashMap handle collisions internally?](#92-how-does-hashmap-handle-collisions-internally) |
| 93 | [How would you reverse a String in Java without using reverse()?](#93-how-would-you-reverse-a-string-in-java-without-using-reverse) |
| 94 | [How do you find duplicate elements in an array?](#94-how-do-you-find-duplicate-elements-in-an-array) |
| 95 | [How do you make a class immutable in Java?](#95-how-do-you-make-a-class-immutable-in-java) |
| 96 | [What is the difference between HashMap and TreeMap?](#96-what-is-the-difference-between-hashmap-and-treemap) |
| 97 | [What happens if you override equals() but not hashCode()?](#97-what-happens-if-you-override-equals-but-not-hashcode) |
| 98 | [What is a ConcurrentModificationException and how do you avoid it?](#98-what-is-a-concurrentmodificationexception-and-how-do-you-avoid-it) |
| 99 | [How do you sort a list of objects by a field in Java?](#99-how-do-you-sort-a-list-of-objects-by-a-field-in-java) |
| 100 | [What are the latest trends in Java development (2024–2025)?](#100-what-are-the-latest-trends-in-java-development-20242025) |

</details>

---

<br>

## 🟢 Basic Level — Java Fundamentals

<br>

### 1. What is Java? What are its key features?

Java is a **high-level, class-based, object-oriented programming language** designed by **James Gosling** at Sun Microsystems (now owned by Oracle). It follows the **"Write Once, Run Anywhere" (WORA)** principle — compiled Java code runs on any platform that has a JVM.

| Feature | Description |
| ------- | ----------- |
| **Platform independent** | Bytecode runs on any OS with a JVM |
| **Object-oriented** | Everything is modelled as objects and classes |
| **Simple** | Syntax similar to C/C++ but removes pointers and memory management |
| **Secure** | No direct memory access, bytecode verification, class loader |
| **Robust** | Strong type checking, exception handling, automatic garbage collection |
| **Multithreaded** | Built-in support for concurrent programming |
| **High performance** | JIT compiler optimises bytecode at runtime |
| **Distributed** | Built-in support for TCP/IP, RMI, EJB |

```java
// The classic Hello World
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. What is the difference between JDK, JRE, and JVM?

| Component | Full Name | Purpose | Contains |
| --------- | --------- | ------- | -------- |
| **JVM** | Java Virtual Machine | Executes Java bytecode | Interpreter, JIT compiler, GC |
| **JRE** | Java Runtime Environment | Runs Java applications | JVM + core libraries |
| **JDK** | Java Development Kit | Develops Java applications | JRE + compiler (javac) + debugger + tools |

```
JDK
├── JRE
│   ├── JVM
│   │   ├── Class Loader
│   │   ├── Bytecode Verifier
│   │   ├── Interpreter / JIT Compiler
│   │   └── Garbage Collector
│   └── Core Libraries (java.lang, java.util, java.io...)
├── javac (compiler)
├── javadoc
├── jar
└── jdb (debugger)
```

> **Rule:** To run Java → need JRE. To develop Java → need JDK (which includes JRE).

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. How does Java achieve platform independence?

Java achieves platform independence through a **two-step compilation process:**

```
Source code (.java)
        ↓ javac (Java Compiler)
Bytecode (.class)         ← platform-independent intermediate code
        ↓ JVM (platform-specific)
Machine code              ← platform-specific execution
```

1. `javac HelloWorld.java` → produces `HelloWorld.class` (bytecode)
2. The `.class` file is **not** native machine code — it is an intermediate, platform-neutral format
3. Any platform with a compatible JVM can execute this bytecode
4. The JVM is platform-dependent, but the bytecode is not

```java
// Compile once on Windows:
// javac Hello.java → Hello.class

// Run on Linux, Mac, Windows — same .class file works everywhere:
// java Hello
```

> **JIT Compiler:** The JVM's Just-In-Time compiler further optimises performance by compiling frequently executed bytecode into native machine code at runtime.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What are the primitive data types in Java?

Java has **8 primitive data types** — they are not objects, stored on the stack, and faster than wrapper classes.

| Type | Size | Default | Range | Example |
| ---- | ---- | ------- | ----- | ------- |
| `byte` | 1 byte | 0 | -128 to 127 | `byte b = 100;` |
| `short` | 2 bytes | 0 | -32,768 to 32,767 | `short s = 1000;` |
| `int` | 4 bytes | 0 | -2^31 to 2^31-1 | `int i = 100000;` |
| `long` | 8 bytes | 0L | -2^63 to 2^63-1 | `long l = 100L;` |
| `float` | 4 bytes | 0.0f | ~7 decimal digits | `float f = 3.14f;` |
| `double` | 8 bytes | 0.0d | ~15 decimal digits | `double d = 3.14;` |
| `char` | 2 bytes | '\u0000' | 0 to 65,535 | `char c = 'A';` |
| `boolean` | 1 bit | false | true / false | `boolean flag = true;` |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What is the difference between == and .equals() in Java?

| Operator | Compares | Used for |
| -------- | -------- | -------- |
| `==` | Reference (memory address) | Primitives and object references |
| `.equals()` | Content (value) | Objects — String, Integer, custom classes |

```java
String s1 = new String("Sisi");
String s2 = new String("Sisi");

System.out.println(s1 == s2);       // false — different objects in heap
System.out.println(s1.equals(s2));  // true  — same content

// String literals use the String pool
String s3 = "Sisi";
String s4 = "Sisi";
System.out.println(s3 == s4);      // true — same reference from pool
System.out.println(s3.equals(s4)); // true — same content

// Primitives — == compares values directly
int a = 5, b = 5;
System.out.println(a == b); // true — value comparison
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What is a wrapper class in Java?

Wrapper classes are **object representations of primitive types**. They allow primitives to be used where objects are required (e.g., in Collections, Generics).

| Primitive | Wrapper Class |
| --------- | ------------- |
| `int` | `Integer` |
| `double` | `Double` |
| `char` | `Character` |
| `boolean` | `Boolean` |
| `byte` | `Byte` |
| `short` | `Short` |
| `long` | `Long` |
| `float` | `Float` |

```java
// Wrapper classes provide utility methods
int max = Integer.MAX_VALUE;          // 2147483647
int parsed = Integer.parseInt("42");  // String to int
String str = Integer.toString(100);   // int to String
int binary = Integer.toBinaryString(10); // "1010"

// Use in Collections (generics require objects, not primitives)
List<Integer> numbers = new ArrayList<>();
numbers.add(42); // autoboxing: int → Integer
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What is autoboxing and unboxing?

**Autoboxing** is the automatic conversion of a primitive to its wrapper class by the Java compiler. **Unboxing** is the reverse — wrapper to primitive.

```java
// Autoboxing — primitive → wrapper (compiler handles this)
int primitive = 42;
Integer wrapped = primitive;          // int → Integer (autoboxing)
List<Integer> list = new ArrayList<>();
list.add(10);                         // int 10 → Integer (autoboxing)

// Unboxing — wrapper → primitive
Integer wrapped2 = Integer.valueOf(100);
int primitive2 = wrapped2;            // Integer → int (unboxing)

// ⚠️ Common trap — NullPointerException from unboxing null
Integer nullVal = null;
int x = nullVal; // NullPointerException at runtime!

// ⚠️ Performance trap — autoboxing in loops
Long sum = 0L;
for (long i = 0; i < 1_000_000; i++) {
    sum += i; // creates ~1 million Long objects — use long primitive instead!
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What is the difference between String, StringBuilder, and StringBuffer?

| Feature | `String` | `StringBuilder` | `StringBuffer` |
| ------- | -------- | --------------- | -------------- |
| Mutability | Immutable | Mutable | Mutable |
| Thread safety | ✅ Yes (immutable) | ❌ Not thread-safe | ✅ Thread-safe (synchronized) |
| Performance | Slowest (creates new objects) | ✅ Fastest | Slower than StringBuilder |
| Use when | String won't change | Single thread, many modifications | Multi-thread string modifications |

```java
// String — creates new object for every modification
String s = "Hello";
s += " World"; // creates a new String object — old one is garbage collected

// StringBuilder — mutable, fast, single-threaded
StringBuilder sb = new StringBuilder("Hello");
sb.append(" World");
sb.insert(5, ",");
sb.reverse();
sb.delete(0, 3);
System.out.println(sb.toString());

// StringBuffer — thread-safe version of StringBuilder
StringBuffer sbf = new StringBuffer("Hello");
sbf.append(" World"); // synchronized — thread-safe
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. Why is String immutable in Java?

String is immutable because the `String` class is declared `final` and its internal `char[]` array is `private final`. Once created, the content cannot be changed.

**Reasons Java designers made String immutable:**

```java
// 1. String Pool — immutability enables safe reuse
String s1 = "Sisi";
String s2 = "Sisi";
// Both point to same pool object — safe because neither can mutate it

// 2. Thread safety — no synchronisation needed
// Multiple threads can share String objects without issues

// 3. Security — class names, file paths, network connections use Strings
// If mutable, malicious code could change them after security checks

// 4. HashMap key safety — String hashCode is cached
String key = "username";
Map<String, String> map = new HashMap<>();
map.put(key, "Sisi");
// key.change() would break the HashMap if String were mutable

// 5. Hashcode caching — computed once, cached in the String object
String s = "Hello";
s.hashCode(); // computed and cached the first time
s.hashCode(); // returned from cache — faster
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What is the String pool (String intern pool)?

The **String pool** (also called String constant pool) is a special area in the **heap memory** where Java stores string literals. When you create a string literal, JVM checks the pool first — if it exists, it reuses the reference instead of creating a new object.

```java
// String literals → stored in String pool
String s1 = "Hello";    // created in pool
String s2 = "Hello";    // reuses same pool reference
System.out.println(s1 == s2); // true — same reference

// new String() → always creates in heap (outside pool)
String s3 = new String("Hello"); // new object in heap
System.out.println(s1 == s3);   // false — different references
System.out.println(s1.equals(s3)); // true — same content

// intern() — manually add to pool or get pool reference
String s4 = s3.intern(); // gets pool reference
System.out.println(s1 == s4); // true — both point to pool object

// ✅ Best practice: always use String literals (not new String())
// to take advantage of the pool and save memory
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 11. What is the difference between stack memory and heap memory?

| Feature | Stack | Heap |
| ------- | ----- | ---- |
| Stores | Method calls, local variables, references | Objects, instance variables, arrays |
| Size | Small, fixed | Large, dynamic |
| Access speed | Fast (LIFO) | Slower |
| Memory management | Automatic (frame popped on method return) | Garbage collector |
| Thread sharing | Each thread has its own stack | Shared across all threads |
| Errors | `StackOverflowError` | `OutOfMemoryError` |

```java
public class MemoryDemo {
    int instanceVar = 10;  // heap — part of object

    public void method() {
        int localVar = 20;              // stack — local variable
        String s = "Hello";            // stack — reference; "Hello" in pool (heap)
        Student student = new Student(); // stack — reference; Student object in heap
    } // localVar, s reference, student reference removed from stack when method ends
      // Student object stays in heap until GC collects it
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. What are access modifiers in Java?

Access modifiers control **visibility and accessibility** of classes, methods, and variables.

| Modifier | Class | Package | Subclass | World |
| -------- | ----- | ------- | -------- | ----- |
| `private` | ✅ | ❌ | ❌ | ❌ |
| `default` (no modifier) | ✅ | ✅ | ❌ | ❌ |
| `protected` | ✅ | ✅ | ✅ | ❌ |
| `public` | ✅ | ✅ | ✅ | ✅ |

```java
public class AccessDemo {
    private int secret = 1;        // only within this class
    int packageLevel = 2;          // within the same package
    protected int forSubclasses = 3; // within package + subclasses
    public int forEveryone = 4;    // accessible everywhere

    private void privateMethod() { /* only here */ }
    public void publicMethod()   { /* everywhere */ }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. What is the final keyword in Java?

The `final` keyword serves three distinct purposes depending on where it is applied:

```java
// 1. final variable — cannot be reassigned (constant)
final int MAX_SIZE = 100;
// MAX_SIZE = 200; // CompileError: cannot assign a value to final variable

// 2. final method — cannot be overridden by subclasses
class Parent {
    public final void display() {
        System.out.println("Cannot be overridden");
    }
}
class Child extends Parent {
    // public void display() { } // CompileError: cannot override final method
}

// 3. final class — cannot be extended (subclassed)
final class Utility {
    public static int add(int a, int b) { return a + b; }
}
// class ExtendedUtil extends Utility { } // CompileError

// Note: String, Integer, and other wrapper classes are final
// That's why they can't be extended and are safely immutable
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. What is the static keyword in Java?

The `static` keyword means a member **belongs to the class itself**, not to any particular instance. All instances of the class share the same static member.

```java
public class Counter {
    private static int count = 0;    // shared by all instances (class-level)
    private int id;                  // unique per instance (object-level)

    public Counter() {
        count++;
        this.id = count;
    }

    public static int getCount() {   // static method — called on class
        return count;
        // Cannot use 'this' or instance variables here
    }

    // Static block — runs once when class is first loaded
    static {
        System.out.println("Counter class loaded!");
        count = 0;
    }
}

// Usage
Counter c1 = new Counter(); // count = 1
Counter c2 = new Counter(); // count = 2
System.out.println(Counter.getCount()); // 2 — called on class, not instance
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. What is the difference between break, continue, and return?

| Statement | Effect | Where used |
| --------- | ------ | ---------- |
| `break` | Exits the loop or switch entirely | loops, switch |
| `continue` | Skips current iteration, goes to next | loops |
| `return` | Exits the current method, optionally returns value | methods |

```java
// break — exit loop early
for (int i = 0; i < 10; i++) {
    if (i == 5) break; // stops at 5
    System.out.print(i + " "); // 0 1 2 3 4
}

// continue — skip specific iterations
for (int i = 0; i < 10; i++) {
    if (i % 2 == 0) continue; // skip even numbers
    System.out.print(i + " "); // 1 3 5 7 9
}

// return — exit method and return value
public int add(int a, int b) {
    if (a < 0 || b < 0) return -1; // early return
    return a + b;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — OOP Concepts

<br>

### 16. What are the four pillars of OOP?

| Pillar | Definition | Java mechanism |
| ------ | ---------- | -------------- |
| **Encapsulation** | Binding data and methods together, hiding internals | `private` fields + `public` getters/setters |
| **Abstraction** | Hiding implementation details, showing only functionality | `abstract` classes, `interface` |
| **Inheritance** | Child class acquires properties of parent class | `extends`, `implements` |
| **Polymorphism** | One interface, many implementations | Method overloading (compile-time), method overriding (runtime) |

```java
// All four pillars in one example
abstract class Shape {                  // Abstraction
    private String color;              // Encapsulation

    public String getColor() { return color; }
    public void setColor(String c) { this.color = c; }

    public abstract double area();     // must be implemented by subclasses
}

class Circle extends Shape {           // Inheritance
    private double radius;
    public Circle(double r) { this.radius = r; }

    @Override
    public double area() {             // Polymorphism (runtime)
        return Math.PI * radius * radius;
    }
}

class Rectangle extends Shape {        // Inheritance
    private double w, h;
    public Rectangle(double w, double h) { this.w = w; this.h = h; }

    @Override
    public double area() { return w * h; } // Polymorphism
}

Shape s1 = new Circle(5);             // Polymorphism — Shape reference, Circle object
Shape s2 = new Rectangle(4, 6);
System.out.println(s1.area());        // 78.54 — Circle's area()
System.out.println(s2.area());        // 24.0  — Rectangle's area()
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. What is a class and an object in Java?

A **class** is a blueprint or template that defines the state (fields) and behaviour (methods) of objects. An **object** is a concrete instance of a class — it occupies memory in the heap.

```java
// Class — blueprint
public class Student {
    // State (fields)
    String name;
    int age;
    String college;

    // Constructor
    public Student(String name, int age, String college) {
        this.name = name;
        this.age = age;
        this.college = college;
    }

    // Behaviour (method)
    public void introduce() {
        System.out.println("Hi, I'm " + name + ", " + age + " years old from " + college);
    }
}

// Object — instance
Student sisi = new Student("Sisi", 20, "SVCE Tirupati");
Student yamini = new Student("Yamini", 21, "SVCE Tirupati");

sisi.introduce();   // Hi, I'm Sisi, 20 years old from SVCE Tirupati
yamini.introduce(); // Hi, I'm Yamini, 21 years old from SVCE Tirupati
// Both are separate objects with their own state, sharing the same class blueprint
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. What is encapsulation? How is it achieved?

Encapsulation is the principle of **bundling data (fields) and methods together in one unit (class) and restricting direct external access** to the internal state.

```java
public class BankAccount {
    private double balance;   // private — hidden from outside
    private String owner;

    public BankAccount(String owner, double initialBalance) {
        this.owner = owner;
        this.balance = initialBalance;
    }

    // Controlled access through public methods
    public double getBalance() {
        return balance; // read access
    }

    public void deposit(double amount) {
        if (amount > 0) balance += amount; // validation before modification
    }

    public void withdraw(double amount) {
        if (amount > 0 && amount <= balance) {
            balance -= amount;
        } else {
            throw new IllegalArgumentException("Invalid withdrawal amount");
        }
    }
    // Cannot do: account.balance = -99999; — compile error!
}
```

**Benefits:** Data hiding, validation control, loose coupling, easier to maintain and test.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. What is inheritance in Java?

Inheritance allows a **child class (subclass) to acquire the properties and methods of a parent class (superclass)** using the `extends` keyword — promoting code reusability.

```java
// Parent class
class Vehicle {
    String brand;
    int speed;

    public Vehicle(String brand, int speed) {
        this.brand = brand;
        this.speed = speed;
    }

    public void move() {
        System.out.println(brand + " is moving at " + speed + " km/h");
    }
}

// Child class inherits from Vehicle
class Car extends Vehicle {
    int doors;

    public Car(String brand, int speed, int doors) {
        super(brand, speed); // call parent constructor
        this.doors = doors;
    }

    @Override
    public void move() {
        super.move();         // call parent method
        System.out.println("It has " + doors + " doors.");
    }

    public void honk() { System.out.println("Beep beep!"); } // new method
}

Car car = new Car("Toyota", 120, 4);
car.move();  // uses overridden method
car.honk();  // unique to Car
```

> **Java supports single inheritance** for classes (one parent only). Multiple inheritance is achieved via interfaces.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. What is polymorphism? Explain method overloading vs overriding

Polymorphism means **"one interface, many implementations"** — the same method name behaves differently based on context.

| Type | When resolved | Mechanism | Keyword |
| ---- | ------------- | --------- | ------- |
| **Compile-time (static)** | At compile time | Method overloading | — |
| **Runtime (dynamic)** | At runtime | Method overriding | `@Override` |

```java
// Compile-time polymorphism — overloading (same name, different params)
class Calculator {
    public int add(int a, int b) { return a + b; }
    public double add(double a, double b) { return a + b; }
    public int add(int a, int b, int c) { return a + b + c; }
    // Compiler picks correct method based on argument types at compile time
}

// Runtime polymorphism — overriding (same name, same params, different class)
class Animal {
    public void sound() { System.out.println("Some sound"); }
}
class Dog extends Animal {
    @Override
    public void sound() { System.out.println("Woof!"); }
}
class Cat extends Animal {
    @Override
    public void sound() { System.out.println("Meow!"); }
}

Animal a1 = new Dog(); // Animal reference, Dog object
Animal a2 = new Cat();
a1.sound(); // "Woof!" — JVM decides at runtime based on actual object type
a2.sound(); // "Meow!"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 21. What is abstraction? Difference between abstract class and interface?

Abstraction hides **implementation complexity** and exposes only essential features through abstract classes or interfaces.

| Feature | Abstract Class | Interface |
| ------- | -------------- | --------- |
| Instantiation | ❌ Cannot instantiate | ❌ Cannot instantiate |
| Methods | Abstract + concrete methods | Abstract (default, static from Java 8) |
| Variables | Instance variables allowed | Only `public static final` constants |
| Constructors | ✅ Has constructors | ❌ No constructors |
| Inheritance | `extends` (single) | `implements` (multiple) |
| Access modifiers | Any modifier | `public` by default |
| Use when | Sharing code + is-a relationship | Defining a contract / capability |

```java
// Abstract class — partial implementation
abstract class Payment {
    String currency = "INR"; // instance variable
    public abstract void pay(double amount); // must implement
    public void printReceipt() { System.out.println("Receipt generated"); } // concrete
}

// Interface — pure contract
interface Refundable {
    void refund(double amount); // implicitly public abstract
    default void notify() { System.out.println("Refund notification sent"); } // Java 8
}

// Class extends one abstract class, implements multiple interfaces
class UPIPayment extends Payment implements Refundable {
    @Override
    public void pay(double amount) { System.out.println("Paid ₹" + amount + " via UPI"); }

    @Override
    public void refund(double amount) { System.out.println("Refunded ₹" + amount + " via UPI"); }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. What is a constructor in Java? Types of constructors?

A constructor is a **special method** with the same name as the class that is called automatically when an object is created. It has no return type.

```java
public class Student {
    String name;
    int age;

    // 1. Default constructor — no arguments (provided by JVM if none defined)
    public Student() {
        this.name = "Unknown";
        this.age = 0;
    }

    // 2. Parameterized constructor — accepts arguments
    public Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    // 3. Copy constructor — creates copy of another object
    public Student(Student other) {
        this.name = other.name;
        this.age = other.age;
    }

    // Constructor chaining — one constructor calls another
    public Student(String name) {
        this(name, 18); // calls parameterized constructor
    }
}

Student s1 = new Student();              // default
Student s2 = new Student("Sisi", 20);   // parameterized
Student s3 = new Student(s2);           // copy — s3 is a copy of s2
Student s4 = new Student("Yamini");     // constructor chaining → age = 18
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 23. What is the this keyword in Java?

`this` is a **reference to the current object** — the instance on which the method or constructor is being called.

```java
public class Employee {
    String name;
    double salary;

    // 1. Resolve naming conflict between parameter and instance variable
    public Employee(String name, double salary) {
        this.name = name;     // this.name = instance field; name = parameter
        this.salary = salary;
    }

    // 2. Call another constructor in the same class (constructor chaining)
    public Employee(String name) {
        this(name, 30000.0); // calls two-arg constructor
    }

    // 3. Pass current object as argument
    public void register(Registry r) {
        r.add(this); // passes current Employee object
    }

    // 4. Return current object (method chaining / builder pattern)
    public Employee setName(String name) {
        this.name = name;
        return this; // enables chaining: emp.setName("Sisi").setSalary(50000)
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. What is the super keyword in Java?

`super` is a **reference to the parent class** — used to access parent class methods, fields, or constructors from a subclass.

```java
class Animal {
    String name = "Animal";

    public Animal(String name) { this.name = name; }

    public void speak() { System.out.println("Animal speaks"); }
}

class Dog extends Animal {
    String name = "Dog"; // shadows parent's name field

    public Dog(String name) {
        super(name); // 1. Call parent constructor — MUST be first statement
    }

    public void display() {
        System.out.println(this.name);  // "Dog" — current class field
        System.out.println(super.name); // "Animal" — parent class field
    }

    @Override
    public void speak() {
        super.speak();                  // 2. Call parent method
        System.out.println("Dog barks");
    }
}

Dog dog = new Dog("Rex");
dog.display(); // Dog, Animal
dog.speak();   // Animal speaks → Dog barks
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. Can we override static methods in Java?

**No.** Static methods belong to the class, not to any object. You can **hide** (not override) a static method in a subclass.

```java
class Parent {
    public static void staticMethod() {
        System.out.println("Parent static method");
    }
    public void instanceMethod() {
        System.out.println("Parent instance method");
    }
}

class Child extends Parent {
    // This is METHOD HIDING — not overriding
    public static void staticMethod() {
        System.out.println("Child static method");
    }
    @Override
    public void instanceMethod() {
        System.out.println("Child instance method");
    }
}

Parent obj = new Child();
obj.staticMethod();   // "Parent static method" — resolved at compile time (hiding)
obj.instanceMethod(); // "Child instance method" — resolved at runtime (overriding)

// That's the key difference:
// Overriding = runtime polymorphism (JVM decides based on actual object)
// Hiding = compile-time decision (based on reference type)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Exception Handling

<br>

### 26. What is exception handling in Java?

Exception handling is a mechanism to **handle runtime errors gracefully** — preventing the program from crashing and allowing clean recovery or meaningful error messages.

```java
// Exception hierarchy:
// Throwable
// ├── Error (serious — don't catch: OutOfMemoryError, StackOverflowError)
// └── Exception
//     ├── Checked (must handle: IOException, SQLException, ClassNotFoundException)
//     └── RuntimeException / Unchecked (NullPointerException, ArrayIndexOutOfBoundsException)

try {
    int[] arr = new int[5];
    arr[10] = 1;                      // throws ArrayIndexOutOfBoundsException
    int result = 10 / 0;              // throws ArithmeticException

} catch (ArrayIndexOutOfBoundsException e) {
    System.out.println("Array error: " + e.getMessage());

} catch (ArithmeticException e) {
    System.out.println("Math error: " + e.getMessage());

} catch (Exception e) {              // catch-all (least specific last)
    System.out.println("General error: " + e.getMessage());

} finally {
    System.out.println("Always runs — close resources here");
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. What is the difference between checked and unchecked exceptions?

| Feature | Checked Exceptions | Unchecked (Runtime) Exceptions |
| ------- | ------------------ | ------------------------------ |
| When detected | Compile time | Runtime |
| Must handle? | ✅ Yes — must catch or declare throws | ❌ No — optional to handle |
| Extends | `Exception` (not RuntimeException) | `RuntimeException` |
| Examples | `IOException`, `SQLException`, `ClassNotFoundException` | `NullPointerException`, `ArrayIndexOutOfBoundsException`, `IllegalArgumentException` |
| Caused by | External factors (file missing, DB down) | Programming bugs |

```java
// Checked — must handle (compile error if you don't)
public void readFile(String path) throws IOException {
    FileReader fr = new FileReader(path); // throws IOException
}

// Unchecked — optional to handle (programming mistake)
String s = null;
s.length(); // NullPointerException at runtime — you should have null-checked!

// Best practice: catch specific exceptions, not just Exception
try {
    connectToDatabase();
} catch (SQLException e) {
    logger.error("DB error: " + e.getMessage());
    throw new ServiceException("Database unavailable", e); // wrap and rethrow
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. What is the difference between throw and throws?

| Feature | `throw` | `throws` |
| ------- | ------- | -------- |
| Purpose | Actually throws an exception | Declares that method may throw exception |
| Location | Inside method body | In method signature |
| Followed by | Exception instance | Exception class name(s) |
| Used with | Checked + unchecked | Mainly checked exceptions |

```java
// throws — method signature declaration
public void withdraw(double amount) throws InsufficientFundsException {
    if (amount > balance) {
        throw new InsufficientFundsException("Balance: " + balance); // throw — actual throw
    }
    balance -= amount;
}

// Multiple exceptions in throws
public void processFile(String path) throws IOException, ParseException {
    // method that can throw either exception
}

// ⚠️ You can declare unchecked exceptions too (rarely done)
public void divide(int a, int b) throws ArithmeticException {
    if (b == 0) throw new ArithmeticException("Division by zero");
    return a / b;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 29. What is the finally block? When does it not execute?

The `finally` block **always executes** after try/catch — regardless of whether an exception occurred. It's used for cleanup (closing files, DB connections, etc.).

```java
public Connection getConnection() {
    Connection conn = null;
    try {
        conn = DriverManager.getConnection(DB_URL, USER, PASS);
        return conn;
    } catch (SQLException e) {
        System.err.println("Connection failed: " + e.getMessage());
        return null;
    } finally {
        System.out.println("Finally always runs!");
        // Note: don't close conn here if you're returning it
        // Use try-with-resources instead (Q30)
    }
}

// ❌ Cases where finally does NOT execute:
// 1. System.exit() is called in try or catch
// 2. JVM crash
// 3. Thread is killed externally

try {
    System.exit(0);  // JVM exits immediately — finally won't run
} finally {
    System.out.println("This will NOT print");
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. What is try-with-resources in Java?

Introduced in Java 7, try-with-resources **automatically closes** resources (that implement `AutoCloseable`) after the try block ends — eliminating the need for a finally block to close resources.

```java
// ❌ Old way — verbose, error-prone
FileReader fr = null;
BufferedReader br = null;
try {
    fr = new FileReader("file.txt");
    br = new BufferedReader(fr);
    String line = br.readLine();
} catch (IOException e) {
    e.printStackTrace();
} finally {
    try { if (br != null) br.close(); } catch (IOException e) { }
    try { if (fr != null) fr.close(); } catch (IOException e) { }
}

// ✅ New way — clean, automatic closing (Java 7+)
try (FileReader fr = new FileReader("file.txt");
     BufferedReader br = new BufferedReader(fr)) {

    String line = br.readLine();
    System.out.println(line);

} catch (IOException e) {
    e.printStackTrace();
}
// fr and br are automatically closed in reverse order when try block ends

// Custom AutoCloseable resource
class DatabaseConnection implements AutoCloseable {
    public DatabaseConnection() { System.out.println("Connected"); }
    @Override
    public void close() { System.out.println("Connection closed"); }
}

try (DatabaseConnection db = new DatabaseConnection()) {
    // use db
} // automatically calls db.close()
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 31. How do you create a custom exception?

```java
// Custom Checked Exception — extends Exception
public class InsufficientFundsException extends Exception {
    private double amount;

    public InsufficientFundsException(String message, double amount) {
        super(message); // pass message to parent Exception
        this.amount = amount;
    }

    public double getAmount() { return amount; }
}

// Custom Unchecked Exception — extends RuntimeException
public class InvalidAgeException extends RuntimeException {
    public InvalidAgeException(String message) {
        super(message);
    }
    public InvalidAgeException(String message, Throwable cause) {
        super(message, cause); // preserve original exception (exception chaining)
    }
}

// Using custom exceptions
public class BankAccount {
    private double balance = 1000.0;

    public void withdraw(double amount) throws InsufficientFundsException {
        if (amount > balance) {
            throw new InsufficientFundsException(
                "Need ₹" + amount + " but only ₹" + balance + " available",
                amount
            );
        }
        balance -= amount;
    }
}

// Catching
try {
    account.withdraw(5000);
} catch (InsufficientFundsException e) {
    System.out.println(e.getMessage());
    System.out.println("Short by: ₹" + (e.getAmount() - 1000));
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. What is the difference between Error and Exception?

| Feature | Error | Exception |
| ------- | ----- | --------- |
| Represents | Serious system-level problems | Recoverable application-level problems |
| Should you catch? | ❌ Generally no | ✅ Yes |
| Examples | `OutOfMemoryError`, `StackOverflowError`, `VirtualMachineError` | `IOException`, `NullPointerException` |
| Caused by | JVM or environment | Application logic or external factors |
| Recovery possible? | Usually no | Often yes |

```java
// Error examples — these indicate a broken JVM/system state
// StackOverflowError — infinite recursion
public void infiniteRecursion() {
    infiniteRecursion(); // StackOverflowError
}

// OutOfMemoryError — not enough heap space
int[] huge = new int[Integer.MAX_VALUE]; // OutOfMemoryError

// ❌ Don't do this — catching Error is almost always wrong
try {
    infiniteRecursion();
} catch (StackOverflowError e) { // technically works but useless
    System.out.println("Stack overflow");
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Collections Framework

<br>

### 33. What is the Java Collections Framework?

The Java Collections Framework (JCF) is a **unified architecture** of classes and interfaces for storing and manipulating groups of data efficiently.

```
Collection (interface)
├── List (ordered, allows duplicates)
│   ├── ArrayList      ← resizable array, fast random access
│   ├── LinkedList     ← doubly-linked list, fast insert/delete
│   └── Vector         ← synchronized ArrayList (legacy)
├── Set (no duplicates)
│   ├── HashSet        ← unordered, O(1) operations
│   ├── LinkedHashSet  ← insertion-ordered HashSet
│   └── TreeSet        ← sorted, O(log n) operations
└── Queue / Deque
    ├── PriorityQueue  ← elements ordered by priority
    ├── ArrayDeque     ← double-ended queue
    └── LinkedList     ← implements both List and Deque

Map (key-value pairs — not extends Collection)
├── HashMap            ← unordered, O(1), allows one null key
├── LinkedHashMap      ← insertion-ordered HashMap
├── TreeMap            ← sorted by keys, O(log n)
├── HashTable          ← synchronized, legacy
└── ConcurrentHashMap  ← thread-safe, high performance
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. What is the difference between ArrayList and LinkedList?

| Feature | ArrayList | LinkedList |
| ------- | --------- | ---------- |
| Internal structure | Dynamic array | Doubly linked list |
| Random access `get(i)` | O(1) fast | O(n) slow |
| Insert/delete at middle | O(n) slow (shifting) | O(1) fast (pointer change) |
| Insert/delete at end | O(1) amortized | O(1) |
| Memory | Less (only data) | More (data + two pointers per node) |
| Cache performance | Better (contiguous memory) | Poor (scattered memory) |
| Use when | Frequent reads, rare insertions | Frequent insertions/deletions |

```java
// ArrayList — best for reads
List<String> arrayList = new ArrayList<>();
arrayList.add("Sisi");       // O(1)
arrayList.get(0);            // O(1) — direct index access
arrayList.add(0, "First");   // O(n) — shifts all elements

// LinkedList — best for frequent insertions/deletions
List<String> linkedList = new LinkedList<>();
linkedList.add("Sisi");
linkedList.addFirst("First"); // O(1) — LinkedList also implements Deque

// Practical tip: use ArrayList by default — it's faster for most use cases
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. What is the difference between HashMap, HashTable, and ConcurrentHashMap?

| Feature | HashMap | HashTable | ConcurrentHashMap |
| ------- | ------- | --------- | ----------------- |
| Thread safety | ❌ Not thread-safe | ✅ Synchronized (locks whole table) | ✅ Segment/bucket-level locking |
| Null keys | ✅ One null key | ❌ No null | ❌ No null key/value |
| Performance | Fastest | Slowest | Fast for concurrent access |
| Introduced | Java 1.2 | Java 1.0 (legacy) | Java 1.5 |
| Use in | Single-threaded | Avoid (legacy) | Multi-threaded environments |

```java
// HashMap — single-threaded use
Map<String, Integer> hashMap = new HashMap<>();
hashMap.put(null, 1);     // allowed
hashMap.put("key", null); // allowed

// ConcurrentHashMap — multi-threaded use (preferred over HashTable)
Map<String, Integer> concurrentMap = new ConcurrentHashMap<>();
// Locks only the bucket being modified — other threads can still access other buckets
// Much better performance than HashTable in high-concurrency scenarios

// Thread-safe single-threaded wrapper — if you need synchronization
Map<String, Integer> syncMap = Collections.synchronizedMap(new HashMap<>());
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 36. How does HashMap work internally?

HashMap uses an **array of linked lists (buckets)** internally. From Java 8, buckets with more than 8 entries convert to a **Red-Black Tree** for O(log n) performance.

```
HashMap internal structure (Java 8+):
Array of buckets:
[0] → null
[1] → Node{key="apple", value=1} → Node{key="kiwi", value=2} (collision — chaining)
[2] → TreeNode (if bucket has > 8 entries — converts to Red-Black Tree)
[3] → null
...
[n-1] → Node{key="mango", value=5}
```

```java
// How put(key, value) works:
// 1. Compute hash: hash = key.hashCode() ^ (hash >>> 16)
// 2. Find bucket index: index = hash & (capacity - 1)
// 3. If bucket empty → insert Node
// 4. If bucket has nodes → check for same key (equals()) → update, or add new node (chaining)
// 5. If load factor exceeded (default 0.75) → resize (double capacity, rehash all)

// Why override both hashCode() and equals()?
Map<Point, String> map = new HashMap<>();
map.put(new Point(1, 2), "A");
map.get(new Point(1, 2)); // returns null! Unless hashCode() and equals() are overridden

class Point {
    int x, y;
    @Override
    public int hashCode() { return Objects.hash(x, y); } // same hash for same values
    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        Point p = (Point) o;
        return x == p.x && y == p.y;
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. What is the difference between HashSet and TreeSet?

| Feature | HashSet | TreeSet |
| ------- | ------- | ------- |
| Internal structure | HashMap backing | Red-Black Tree |
| Order | ❌ No order guaranteed | ✅ Sorted (natural or custom) |
| Performance | O(1) add/remove/contains | O(log n) add/remove/contains |
| Null element | ✅ One null allowed | ❌ No null (NullPointerException) |
| Use when | Fast lookup, no order needed | Sorted unique elements |

```java
// HashSet — fast, no order
Set<String> hashSet = new HashSet<>(Arrays.asList("banana", "apple", "cherry", "apple"));
System.out.println(hashSet); // [banana, cherry, apple] — order not guaranteed, apple deduplicated

// TreeSet — sorted automatically
Set<String> treeSet = new TreeSet<>(Arrays.asList("banana", "apple", "cherry"));
System.out.println(treeSet); // [apple, banana, cherry] — sorted alphabetically

// Custom sorting with TreeSet
Set<Employee> byAge = new TreeSet<>(Comparator.comparingInt(Employee::getAge));
byAge.add(new Employee("Sisi", 20));
byAge.add(new Employee("Yamini", 21));
// Sorted by age automatically
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 38. What is the difference between Comparable and Comparator?

| Feature | `Comparable` | `Comparator` |
| ------- | ------------ | ------------ |
| Package | `java.lang` | `java.util` |
| Method | `compareTo(Object o)` | `compare(Object o1, Object o2)` |
| Implemented by | The class being sorted | A separate comparator class / lambda |
| Modifies original class | ✅ Yes | ❌ No |
| Number of sort orders | One (natural ordering) | Many (multiple comparators) |
| Use when | Single natural order (e.g., by ID) | Multiple sort orders, or can't modify class |

```java
// Comparable — natural ordering (inside the class)
class Student implements Comparable<Student> {
    String name;
    int gpa;

    @Override
    public int compareTo(Student other) {
        return Integer.compare(this.gpa, other.gpa); // sort by GPA ascending
    }
}
List<Student> students = new ArrayList<>(/* ... */);
Collections.sort(students); // uses compareTo()

// Comparator — external ordering (lambda / separate class)
// Sort by name
Comparator<Student> byName = Comparator.comparing(s -> s.name);
// Sort by GPA descending
Comparator<Student> byGpaDesc = Comparator.comparingInt(Student::getGpa).reversed();
// Sort by multiple fields
Comparator<Student> complex = Comparator.comparingInt(Student::getGpa)
                                         .thenComparing(Student::getName);

students.sort(byGpaDesc);
students.sort(complex);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. What is the difference between Iterator and ListIterator?

| Feature | Iterator | ListIterator |
| ------- | -------- | ------------ |
| Direction | Forward only | Both forward and backward |
| Applicable to | Any Collection | Only List |
| Methods | `hasNext()`, `next()`, `remove()` | Above + `hasPrevious()`, `previous()`, `add()`, `set()` |
| Start position | Beginning | Any index |

```java
List<String> list = new ArrayList<>(Arrays.asList("A", "B", "C", "D"));

// Iterator — forward only
Iterator<String> it = list.iterator();
while (it.hasNext()) {
    String val = it.next();
    if (val.equals("B")) it.remove(); // safe removal during iteration
}

// ListIterator — forward and backward, add/set during iteration
ListIterator<String> lit = list.listIterator(list.size()); // start from end
while (lit.hasPrevious()) {
    System.out.print(lit.previous() + " "); // D C A — iterates backward (B removed above)
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 40. What is a fail-fast vs fail-safe iterator?

| Feature | Fail-Fast | Fail-Safe |
| ------- | --------- | --------- |
| Behavior | Throws `ConcurrentModificationException` if collection modified during iteration | Works on a copy — no exception |
| Works on | Original collection | Copy of collection |
| Memory | Less (no copy) | More (copy created) |
| Examples | `ArrayList`, `HashMap`, `HashSet` iterators | `CopyOnWriteArrayList`, `ConcurrentHashMap` iterators |

```java
// Fail-Fast — ArrayList
List<String> list = new ArrayList<>(Arrays.asList("A", "B", "C"));
Iterator<String> it = list.iterator();
list.add("D"); // modifies collection during iteration
it.next();     // throws ConcurrentModificationException!

// Use Iterator.remove() instead for safe removal:
Iterator<String> it2 = list.iterator();
while (it2.hasNext()) {
    if (it2.next().equals("B")) it2.remove(); // SAFE — doesn't throw
}

// Fail-Safe — CopyOnWriteArrayList
List<String> safeList = new CopyOnWriteArrayList<>(Arrays.asList("A", "B", "C"));
for (String s : safeList) {
    safeList.add("D"); // no exception — iterates over snapshot
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 41. When would you use LinkedHashMap vs HashMap?

```java
// HashMap — unordered, fastest
Map<String, Integer> wordCount = new HashMap<>();
// Use when: order doesn't matter, maximum performance needed

// LinkedHashMap — maintains insertion order
Map<String, Integer> orderedMap = new LinkedHashMap<>();
orderedMap.put("banana", 1);
orderedMap.put("apple", 2);
orderedMap.put("cherry", 3);
System.out.println(orderedMap); // {banana=1, apple=2, cherry=3} — insertion order

// LRU Cache using LinkedHashMap (access-ordered)
Map<Integer, String> lruCache = new LinkedHashMap<>(16, 0.75f, true) {
    @Override
    protected boolean removeEldestEntry(Map.Entry<Integer, String> eldest) {
        return size() > 5; // evict oldest accessed when size > 5
    }
};
// Use when: you need insertion-order OR want to build an LRU cache
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What is a PriorityQueue in Java?

A `PriorityQueue` is a **min-heap by default** — elements are dequeued in their natural order (smallest first), not insertion order.

```java
// Min-heap (default — smallest element polled first)
PriorityQueue<Integer> minHeap = new PriorityQueue<>();
minHeap.offer(30);
minHeap.offer(10);
minHeap.offer(20);
System.out.println(minHeap.poll()); // 10 — smallest
System.out.println(minHeap.poll()); // 20
System.out.println(minHeap.poll()); // 30

// Max-heap (custom comparator)
PriorityQueue<Integer> maxHeap = new PriorityQueue<>(Comparator.reverseOrder());
maxHeap.offer(30); maxHeap.offer(10); maxHeap.offer(20);
System.out.println(maxHeap.poll()); // 30 — largest

// Priority queue of objects
PriorityQueue<Task> taskQueue = new PriorityQueue<>(
    Comparator.comparingInt(Task::getPriority) // lower number = higher priority
);
taskQueue.offer(new Task("Deploy", 1));
taskQueue.offer(new Task("Test", 3));
taskQueue.offer(new Task("Build", 2));
// Polls in order: Deploy → Build → Test
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Java 8+ Features

<br>

### 43. What are the major features introduced in Java 8?

| Feature | Description |
| ------- | ----------- |
| **Lambda expressions** | Anonymous functions — concise functional code |
| **Stream API** | Functional-style bulk operations on collections |
| **Functional interfaces** | Interfaces with one abstract method — `Predicate`, `Function`, `Consumer`, `Supplier` |
| **Default methods** | Concrete methods in interfaces |
| **Method references** | Shorthand for lambdas calling existing methods |
| **Optional** | Wrapper to avoid `NullPointerException` |
| **New Date/Time API** | `LocalDate`, `LocalTime`, `LocalDateTime`, `ZonedDateTime` |
| **Nashorn JS Engine** | JavaScript engine inside JVM (removed in Java 15) |
| **Base64 encoding** | Built-in `Base64` class |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What is a lambda expression in Java?

A lambda expression is an **anonymous function** — a short block of code that can be passed around as a value. It implements a functional interface.

```java
// Syntax: (parameters) -> expression  OR  (parameters) -> { statements; }

// Before Java 8 — anonymous inner class
Runnable r1 = new Runnable() {
    @Override
    public void run() { System.out.println("Running!"); }
};

// Java 8 lambda — much cleaner
Runnable r2 = () -> System.out.println("Running!");

// With parameters
Comparator<Integer> comp = (a, b) -> a - b;

// With body block
Comparator<String> byLength = (s1, s2) -> {
    if (s1.length() != s2.length()) return s1.length() - s2.length();
    return s1.compareTo(s2);
};

// Lambda in Collections
List<String> names = Arrays.asList("Sisi", "Yamini", "Charitha", "Pavani");
names.sort((a, b) -> a.compareTo(b));
names.forEach(name -> System.out.println(name));
names.removeIf(name -> name.length() < 5);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 45. What is a functional interface? Name some built-in ones

A functional interface is an interface with **exactly one abstract method** — it can be implemented by a lambda expression. Annotate with `@FunctionalInterface` (optional but recommended).

| Interface | Method | Input | Output | Use case |
| --------- | ------ | ----- | ------ | -------- |
| `Predicate<T>` | `test(T t)` | T | boolean | Filtering, conditions |
| `Function<T,R>` | `apply(T t)` | T | R | Transformation/mapping |
| `Consumer<T>` | `accept(T t)` | T | void | Side effects (printing, saving) |
| `Supplier<T>` | `get()` | none | T | Providing/creating values |
| `BiFunction<T,U,R>` | `apply(T,U)` | T, U | R | Two inputs, one output |
| `UnaryOperator<T>` | `apply(T t)` | T | T | Transform same type |
| `BinaryOperator<T>` | `apply(T,T)` | T, T | T | Combine two values of same type |
| `Runnable` | `run()` | none | void | Thread/task with no args/return |

```java
// Predicate — test condition
Predicate<Integer> isEven = n -> n % 2 == 0;
System.out.println(isEven.test(4)); // true
List<Integer> evens = numbers.stream().filter(isEven).collect(Collectors.toList());

// Function — transform
Function<String, Integer> strLen = s -> s.length();
System.out.println(strLen.apply("Sisi")); // 4

// Consumer — consume with side effect
Consumer<String> printer = s -> System.out.println(">> " + s);
names.forEach(printer);

// Supplier — produce value
Supplier<String> greeting = () -> "Hello, World!";
System.out.println(greeting.get());
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. What is the Stream API? How is it different from Collections?

The Stream API provides a **functional-style pipeline for processing sequences of data** — filtering, mapping, reducing, etc.

| Feature | Collection | Stream |
| ------- | ---------- | ------ |
| Stores data? | ✅ Yes | ❌ No (pipeline only) |
| Reusable? | ✅ Yes | ❌ Once consumed, closed |
| Iteration | External (`for`, `iterator`) | Internal (API handles it) |
| Parallel? | Manual | ✅ `.parallelStream()` |
| Lazy evaluation? | ❌ No | ✅ Yes (intermediate ops are lazy) |

```java
List<Employee> employees = getEmployees();

// Without streams
List<String> result = new ArrayList<>();
for (Employee e : employees) {
    if (e.getSalary() > 50000 && e.getDept().equals("IT")) {
        result.add(e.getName().toUpperCase());
    }
}
Collections.sort(result);

// With streams — readable pipeline
List<String> result = employees.stream()
    .filter(e -> e.getSalary() > 50000)           // intermediate
    .filter(e -> e.getDept().equals("IT"))          // intermediate
    .map(e -> e.getName().toUpperCase())            // intermediate
    .sorted()                                       // intermediate
    .collect(Collectors.toList());                  // terminal

// Parallel stream for large datasets
long count = employees.parallelStream()
    .filter(e -> e.getSalary() > 100000)
    .count();
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is the difference between map() and flatMap() in streams?

| Method | Input | Output | Use when |
| ------ | ----- | ------ | -------- |
| `map()` | `T → R` | `Stream<R>` | One-to-one transformation |
| `flatMap()` | `T → Stream<R>` | `Stream<R>` (flattened) | One-to-many, or flattening nested streams |

```java
// map() — one-to-one
List<String> names = Arrays.asList("Sisi", "Yamini", "Pavani");
List<Integer> lengths = names.stream()
    .map(String::length)       // "Sisi" → 4
    .collect(Collectors.toList()); // [4, 6, 6]

// flatMap() — flatten nested structures
List<List<Integer>> nested = Arrays.asList(
    Arrays.asList(1, 2, 3),
    Arrays.asList(4, 5),
    Arrays.asList(6, 7, 8, 9)
);

// map() would give Stream<List<Integer>> — still nested
// flatMap() flattens to Stream<Integer>
List<Integer> flat = nested.stream()
    .flatMap(List::stream)     // each list → stream, all merged
    .collect(Collectors.toList()); // [1, 2, 3, 4, 5, 6, 7, 8, 9]

// Real-world: get all skills of all employees
List<String> allSkills = employees.stream()
    .flatMap(e -> e.getSkills().stream()) // each employee has List<String> skills
    .distinct()
    .sorted()
    .collect(Collectors.toList());
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. What are intermediate and terminal operations in streams?

| Type | Description | Returns | Examples |
| ---- | ----------- | ------- | -------- |
| **Intermediate** | Lazy — not executed until terminal op | `Stream<T>` | `filter()`, `map()`, `sorted()`, `distinct()`, `limit()`, `skip()`, `peek()` |
| **Terminal** | Triggers the pipeline, consumes stream | Result / void | `collect()`, `count()`, `forEach()`, `reduce()`, `findFirst()`, `anyMatch()`, `min()`, `max()` |

```java
List<Integer> numbers = Arrays.asList(5, 3, 8, 1, 9, 2, 7, 4, 6);

// Pipeline: intermediate ops are lazy — nothing runs until collect()
long result = numbers.stream()
    .filter(n -> n > 3)          // intermediate — lazy
    .map(n -> n * 2)             // intermediate — lazy
    .sorted()                    // intermediate — lazy
    .limit(4)                    // intermediate — lazy
    .count();                    // terminal — triggers ENTIRE pipeline

// reduce() — combine elements into a single value
int sum = numbers.stream().reduce(0, Integer::sum);
Optional<Integer> max = numbers.stream().reduce(Integer::max);

// collect() — most versatile terminal op
Map<Boolean, List<Integer>> partitioned = numbers.stream()
    .collect(Collectors.partitioningBy(n -> n % 2 == 0));
// {true=[8,2,4,6], false=[5,3,1,9,7]}

Map<Integer, List<Employee>> byDept = employees.stream()
    .collect(Collectors.groupingBy(Employee::getDeptId));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. What is Optional in Java 8? Why is it used?

`Optional<T>` is a **container object that may or may not contain a value** — it's a better alternative to returning `null`, forcing the caller to handle the absence of a value explicitly.

```java
// ❌ Old way — null checks everywhere, NullPointerException risk
String name = user.getAddress().getCity().toUpperCase(); // NPE if any is null

// ✅ Optional — explicit empty handling
Optional<String> cityOptional = Optional.ofNullable(user)
    .map(User::getAddress)
    .map(Address::getCity);

// Various ways to use Optional
Optional<String> opt = Optional.of("Sisi");         // guaranteed non-null
Optional<String> empty = Optional.empty();           // empty optional
Optional<String> nullable = Optional.ofNullable(maybeNull); // might be null

opt.isPresent();                   // true
opt.get();                         // "Sisi" (throws if empty!)
opt.orElse("default");             // "Sisi" (returns default if empty)
opt.orElseGet(() -> computeDefault()); // lazy default
opt.orElseThrow(() -> new NotFoundException("User not found"));
opt.ifPresent(name -> System.out.println(name));  // runs only if present
opt.map(String::toUpperCase);      // Optional<"SISI">
opt.filter(s -> s.startsWith("S")); // Optional<"Sisi"> or empty

// ❌ Anti-patterns
Optional<String> bad1 = Optional.of(null); // NullPointerException!
if (opt.isPresent()) opt.get();   // defeats the purpose — use ifPresent or orElse
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. What are default and static methods in interfaces (Java 8)?

Java 8 allowed interfaces to have **concrete method implementations** via `default` and `static` methods — without breaking existing implementations.

```java
interface Vehicle {
    void start(); // abstract — must implement

    // default method — concrete implementation, can be overridden
    default void fuelCheck() {
        System.out.println("Checking fuel level...");
    }

    // static method — called on interface directly, cannot be overridden
    static int maxSpeed() {
        return 200;
    }
}

class Car implements Vehicle {
    @Override
    public void start() { System.out.println("Car started"); }

    // Optional: override default method
    @Override
    public void fuelCheck() {
        System.out.println("Car fuel check: " + getFuelLevel() + "%");
    }
}

Vehicle.maxSpeed();  // 200 — static method on interface
Car car = new Car();
car.start();         // Car started
car.fuelCheck();     // Car fuel check: 85%

// Why default methods? To add new methods to interfaces without breaking all existing implementations
// Java's List, Collection, etc. added forEach(), removeIf(), stream() as default methods in Java 8
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 51. What is the new Date/Time API in Java 8?

Java 8 introduced the `java.time` package — replacing the old, flawed `java.util.Date` and `java.util.Calendar`.

```java
import java.time.*;
import java.time.format.DateTimeFormatter;

// LocalDate — date only (no time, no timezone)
LocalDate today = LocalDate.now();
LocalDate birthday = LocalDate.of(2004, Month.MARCH, 15);
LocalDate nextWeek = today.plusDays(7);
boolean isLeap = today.isLeapYear();

// LocalTime — time only
LocalTime now = LocalTime.now();
LocalTime meeting = LocalTime.of(14, 30, 0); // 2:30 PM
boolean isPast = meeting.isBefore(now);

// LocalDateTime — date + time (no timezone)
LocalDateTime dt = LocalDateTime.now();
LocalDateTime appointment = LocalDateTime.of(2025, 6, 15, 10, 30);

// ZonedDateTime — date + time + timezone
ZonedDateTime istNow = ZonedDateTime.now(ZoneId.of("Asia/Kolkata"));
ZonedDateTime utcNow = ZonedDateTime.now(ZoneId.of("UTC"));

// Duration and Period
Duration duration = Duration.between(meeting, LocalTime.now());
Period period = Period.between(birthday, today);
System.out.println("Age: " + period.getYears() + " years");

// Formatting
DateTimeFormatter formatter = DateTimeFormatter.ofPattern("dd-MM-yyyy HH:mm");
String formatted = dt.format(formatter);
LocalDateTime parsed = LocalDateTime.parse("15-03-2025 10:30", formatter);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. What is a method reference in Java?

Method references are **shorthand notation** for lambdas that simply call an existing method. There are four types:

| Type | Syntax | Lambda equivalent |
| ---- | ------ | ----------------- |
| Static method | `ClassName::staticMethod` | `x -> ClassName.staticMethod(x)` |
| Instance method (specific object) | `instance::method` | `x -> instance.method(x)` |
| Instance method (arbitrary object) | `ClassName::instanceMethod` | `x -> x.method()` |
| Constructor | `ClassName::new` | `x -> new ClassName(x)` |

```java
// Static method reference
List<String> names = Arrays.asList("sisi", "yamini", "pavani");
names.stream().map(String::toUpperCase).forEach(System.out::println);
//  ↑ instance method (arbitrary)      ↑ instance method (specific: System.out)

// Static method reference
List<Integer> numbers = Arrays.asList(-3, 1, -5, 2, -1);
numbers.stream().map(Math::abs).forEach(System.out::println);
// Equivalent to: n -> Math.abs(n)

// Constructor reference
List<String> nameList = Arrays.asList("Sisi", "Yamini");
List<Student> students = nameList.stream()
    .map(Student::new)               // calls Student(String name) constructor
    .collect(Collectors.toList());

// Specific instance method reference
String prefix = "Hello, ";
names.stream()
    .map(prefix::concat)             // calls prefix.concat(name) for each
    .forEach(System.out::println);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Multithreading & Concurrency

<br>

### 53. What is multithreading in Java?

Multithreading is the ability to execute **multiple threads concurrently** within a single program. Each thread is a lightweight sub-process that shares the same memory space (heap) but has its own stack.

**Benefits:** Better CPU utilisation, responsive UIs, parallel processing, better throughput.

```java
// A thread is the smallest unit of execution
// Java provides Thread class and Runnable interface

// Main thread always exists — your main() runs in it
public class Main {
    public static void main(String[] args) {
        System.out.println("Thread: " + Thread.currentThread().getName()); // main

        // Creating additional threads
        Thread t1 = new Thread(() -> System.out.println("Thread 1"));
        Thread t2 = new Thread(() -> System.out.println("Thread 2"));
        t1.start(); // starts thread — JVM schedules execution
        t2.start();
        // Output order is not guaranteed — JVM scheduler decides
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 54. What are the ways to create a thread in Java?

```java
// Method 1: Extend Thread class
class MyThread extends Thread {
    @Override
    public void run() {
        System.out.println("Thread running: " + getName());
    }
}
MyThread t1 = new MyThread();
t1.start(); // calls run() in new thread

// Method 2: Implement Runnable (preferred — doesn't "waste" inheritance)
class MyTask implements Runnable {
    @Override
    public void run() {
        System.out.println("Runnable running: " + Thread.currentThread().getName());
    }
}
Thread t2 = new Thread(new MyTask());
t2.start();

// Method 3: Lambda (most concise — since Runnable is @FunctionalInterface)
Thread t3 = new Thread(() -> System.out.println("Lambda thread!"));
t3.start();

// Method 4: Callable + FutureTask (returns a result)
Callable<Integer> callable = () -> 42;
FutureTask<Integer> future = new FutureTask<>(callable);
new Thread(future).start();
int result = future.get(); // blocks until result is ready

// Method 5: ExecutorService (recommended for production — thread pool)
ExecutorService executor = Executors.newFixedThreadPool(4);
executor.submit(() -> System.out.println("Executor thread"));
executor.shutdown();
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 55. What is the thread lifecycle in Java?

```
NEW → RUNNABLE → RUNNING → (BLOCKED/WAITING/TIMED_WAITING) → TERMINATED

NEW           : Thread created (new Thread()) but not started
RUNNABLE      : Thread ready to run, waiting for CPU (after start())
RUNNING       : Thread is executing (selected by CPU scheduler)
BLOCKED       : Waiting for a monitor lock (synchronized block)
WAITING       : Waiting indefinitely for notify() (wait(), join())
TIMED_WAITING : Waiting for specified time (sleep(), wait(ms), join(ms))
TERMINATED    : run() completed or exception thrown
```

```java
Thread t = new Thread(() -> {
    try {
        Thread.sleep(1000); // TIMED_WAITING
    } catch (InterruptedException e) {
        Thread.currentThread().interrupt();
    }
});

System.out.println(t.getState()); // NEW
t.start();
System.out.println(t.getState()); // RUNNABLE
Thread.sleep(100);
System.out.println(t.getState()); // TIMED_WAITING
t.join();                         // wait for t to finish
System.out.println(t.getState()); // TERMINATED
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 56. What is the synchronized keyword?

`synchronized` ensures only **one thread at a time** can execute a block of code or method — providing mutual exclusion and visibility guarantees.

```java
class Counter {
    private int count = 0;

    // Method-level synchronization — locks on 'this' object
    public synchronized void increment() {
        count++; // read-modify-write is NOT atomic without sync
    }

    // Block-level synchronization — more granular, better performance
    public void decrement() {
        synchronized (this) {  // only this block is locked
            count--;
        }
        System.out.println("Decremented"); // this runs without lock
    }

    // Static synchronization — locks on Class object
    public static synchronized void staticMethod() { /* ... */ }

    public int getCount() { return count; }
}

// Without synchronized — race condition:
Counter c = new Counter();
Thread t1 = new Thread(() -> { for(int i=0; i<1000; i++) c.increment(); });
Thread t2 = new Thread(() -> { for(int i=0; i<1000; i++) c.increment(); });
t1.start(); t2.start();
t1.join(); t2.join();
// Without sync: might print < 2000 (race condition lost updates)
// With sync: always prints 2000
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. What is a deadlock in Java? How do you prevent it?

A deadlock occurs when **two or more threads are blocked forever**, each waiting for a resource held by the other.

```java
// Classic deadlock — Thread 1 holds Lock A, wants Lock B
//                    Thread 2 holds Lock B, wants Lock A

Object lockA = new Object();
Object lockB = new Object();

Thread t1 = new Thread(() -> {
    synchronized (lockA) {
        System.out.println("T1 holds A, waiting for B...");
        try { Thread.sleep(100); } catch (Exception e) {}
        synchronized (lockB) { System.out.println("T1 got both locks"); }
    }
});

Thread t2 = new Thread(() -> {
    synchronized (lockB) { // T2 acquires B first
        System.out.println("T2 holds B, waiting for A...");
        synchronized (lockA) { System.out.println("T2 got both locks"); }
    }
});
// t1 holds A, waits for B. t2 holds B, waits for A. DEADLOCK.

// ✅ Prevention techniques:
// 1. Lock ordering — always acquire locks in the SAME ORDER
Thread t1Fixed = new Thread(() -> {
    synchronized (lockA) { synchronized (lockB) { /* ... */ } } // A then B
});
Thread t2Fixed = new Thread(() -> {
    synchronized (lockA) { synchronized (lockB) { /* ... */ } } // A then B (same order!)
});

// 2. tryLock with timeout (ReentrantLock)
ReentrantLock lock1 = new ReentrantLock();
if (lock1.tryLock(100, TimeUnit.MILLISECONDS)) {
    try { /* work */ } finally { lock1.unlock(); }
} else {
    System.out.println("Could not acquire lock — avoiding deadlock");
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 58. What is the difference between wait(), notify(), and notifyAll()?

These methods are defined in `Object` class and are used for **inter-thread communication**. They must be called from within a `synchronized` block.

| Method | Description |
| ------ | ----------- |
| `wait()` | Releases the lock and waits until notified |
| `notify()` | Wakes up ONE waiting thread (random) |
| `notifyAll()` | Wakes up ALL waiting threads |

```java
class SharedBuffer {
    private int data;
    private boolean hasData = false;

    public synchronized void produce(int value) throws InterruptedException {
        while (hasData) wait(); // wait if buffer full — releases lock
        data = value;
        hasData = true;
        System.out.println("Produced: " + value);
        notify(); // wake up the consumer
    }

    public synchronized int consume() throws InterruptedException {
        while (!hasData) wait(); // wait if buffer empty
        hasData = false;
        System.out.println("Consumed: " + data);
        notify(); // wake up the producer
        return data;
    }
}

// Producer-consumer pattern
SharedBuffer buffer = new SharedBuffer();
new Thread(() -> { for(int i=1; i<=5; i++) buffer.produce(i); }).start();
new Thread(() -> { for(int i=0; i<5; i++) buffer.consume(); }).start();
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. What is the volatile keyword in Java?

`volatile` ensures that a variable is **always read from and written to main memory** — not from a thread's local cache. It provides visibility guarantee but not atomicity.

```java
class StopThread {
    // Without volatile: background thread might never see stopRequested = true
    // because it's cached in the thread's local register
    private volatile boolean stopRequested = false; // volatile — always reads from main memory

    public void start() {
        Thread worker = new Thread(() -> {
            while (!stopRequested) { // always reads fresh value
                // doing work
            }
            System.out.println("Thread stopped");
        });
        worker.start();
    }

    public void stop() {
        stopRequested = true; // written to main memory immediately
    }
}

// volatile vs synchronized:
// volatile → visibility only (reads/writes are atomic for primitive types)
// synchronized → visibility + atomicity + mutual exclusion

// ⚠️ volatile doesn't fix race conditions:
private volatile int count = 0;
count++; // NOT atomic! (read → increment → write — three operations)
// Use AtomicInteger instead:
AtomicInteger atomicCount = new AtomicInteger(0);
atomicCount.incrementAndGet(); // atomic, thread-safe
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. What is the ExecutorService in Java?

`ExecutorService` is a **thread pool management framework** from `java.util.concurrent` — manages a pool of worker threads, reusing them instead of creating new threads for every task.

```java
import java.util.concurrent.*;

// Types of thread pools
ExecutorService fixed = Executors.newFixedThreadPool(4);        // 4 threads
ExecutorService single = Executors.newSingleThreadExecutor();   // 1 thread
ExecutorService cached = Executors.newCachedThreadPool();       // grows/shrinks dynamically
ScheduledExecutorService scheduled = Executors.newScheduledThreadPool(2);

// Submit tasks
ExecutorService executor = Executors.newFixedThreadPool(4);

// Runnable — fire and forget
executor.submit(() -> System.out.println("Task 1"));

// Callable — returns a result
Future<Integer> future = executor.submit(() -> {
    Thread.sleep(1000);
    return 42;
});
System.out.println("Result: " + future.get()); // blocks until done

// Multiple futures
List<Callable<Integer>> tasks = Arrays.asList(
    () -> 1, () -> 2, () -> 3
);
List<Future<Integer>> futures = executor.invokeAll(tasks);

// Scheduled task
scheduled.scheduleAtFixedRate(() -> System.out.println("Heartbeat"), 0, 5, TimeUnit.SECONDS);

// Graceful shutdown
executor.shutdown();                       // no new tasks, finish existing
executor.awaitTermination(30, TimeUnit.SECONDS); // wait up to 30 seconds
executor.shutdownNow();                   // attempt to stop all tasks
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 61. What is the difference between Callable and Runnable?

| Feature | `Runnable` | `Callable<V>` |
| ------- | ---------- | -------------- |
| Method | `run()` | `call()` |
| Return type | `void` | Generic type `V` |
| Throws checked exception | ❌ No | ✅ Yes |
| Used with | `Thread`, `ExecutorService` | `ExecutorService` only |
| Result | Cannot return | Returns `Future<V>` |

```java
// Runnable — no return, no checked exception
Runnable task = () -> System.out.println("Running...");
new Thread(task).start();
executor.submit(task);

// Callable — returns result, can throw checked exception
Callable<String> fetchData = () -> {
    String result = httpClient.get("https://api.example.com/data"); // may throw IOException
    return result;
};
Future<String> future = executor.submit(fetchData);
String data = future.get(); // blocks, returns result, throws if exception occurred
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 62. What is the difference between synchronized and ReentrantLock?

| Feature | `synchronized` | `ReentrantLock` |
| ------- | -------------- | --------------- |
| Fairness | No fairness guarantee | ✅ Optional fair mode |
| Try to acquire | ❌ Blocks indefinitely | ✅ `tryLock(timeout)` |
| Interruptible | ❌ No | ✅ `lockInterruptibly()` |
| Multiple conditions | ❌ One wait set | ✅ Multiple `Condition` objects |
| Explicit unlock needed | ❌ Auto on exit | ✅ Must call `unlock()` |
| Performance | Good | Slightly better for high contention |

```java
import java.util.concurrent.locks.ReentrantLock;
import java.util.concurrent.locks.Condition;

ReentrantLock lock = new ReentrantLock(true); // fair = true — longest-waiting thread goes next
Condition notEmpty = lock.newCondition();
Condition notFull = lock.newCondition();

// Always unlock in finally to avoid deadlock if exception occurs
lock.lock();
try {
    while (queue.isEmpty()) notEmpty.await(); // wait on specific condition
    queue.poll();
    notFull.signal();
} finally {
    lock.unlock(); // MUST release
}

// tryLock — non-blocking attempt
if (lock.tryLock(500, TimeUnit.MILLISECONDS)) {
    try { /* do work */ } finally { lock.unlock(); }
} else {
    System.out.println("Could not acquire lock, doing something else");
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — JVM Internals & Memory

<br>

### 63. What is garbage collection in Java?

Garbage Collection (GC) is Java's **automatic memory management** — the JVM automatically identifies and removes objects that are no longer reachable, freeing heap memory.

```
GC Process — Mark and Sweep:
1. MARK  — Starting from root references (stack, static fields), mark all reachable objects
2. SWEEP — Delete all unmarked (unreachable) objects, freeing their memory
3. COMPACT — Move surviving objects together to reduce fragmentation (optional)

Heap Generations:
Young Generation (small, collected frequently — "Minor GC")
├── Eden Space      ← new objects created here
├── Survivor S0     ← objects that survived one GC cycle
└── Survivor S1     ← objects that survived two GC cycles

Old Generation (large, collected rarely — "Major/Full GC")
└── long-lived objects that survived multiple Young GC cycles

Metaspace (Java 8+) — class metadata (replaced PermGen)
```

```java
// Making an object eligible for GC
String s = new String("Hello"); // object created in heap
s = null;                       // reference removed — object eligible for GC

// Suggesting GC (not guaranteed!)
System.gc();
Runtime.getRuntime().gc();

// finalize() — called before GC (deprecated in Java 9, removed in Java 18)
// Use try-with-resources or Cleaner instead
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. What are the different types of garbage collectors in Java?

| GC | Flag | Best for | Pauses |
| -- | ---- | -------- | ------ |
| **Serial GC** | `-XX:+UseSerialGC` | Single-threaded, small apps | Long stop-the-world |
| **Parallel GC** | `-XX:+UseParallelGC` | Throughput-focused, batch | Stop-the-world (parallel threads) |
| **CMS (Concurrent Mark Sweep)** | Deprecated Java 9 | Low latency | Short pauses |
| **G1 (Garbage First)** | `-XX:+UseG1GC` | Balanced, default Java 9+ | Short, predictable |
| **ZGC** | `-XX:+UseZGC` | Ultra-low latency (< 1ms pause) | Near-concurrent |
| **Shenandoah** | `-XX:+UseShenandoahGC` | Low pause, Red Hat contribution | Near-concurrent |

```bash
# Choose GC based on your needs
java -XX:+UseG1GC -Xmx4g MyApp          # balanced (default)
java -XX:+UseZGC -Xmx8g LatencySensitiveApp  # ultra-low pause
java -XX:+UseParallelGC -Xmx16g BatchProcessor # max throughput
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 65. What is the JVM memory model? Explain all memory areas

```
JVM Memory Areas:
┌──────────────────────────────────────────────────────────┐
│ Method Area / Metaspace (shared)                         │
│ Class metadata, static variables, constant pool          │
├──────────────────────────────────────────────────────────┤
│ Heap (shared — GC managed)                               │
│ ├── Young Generation (Eden + S0 + S1)                    │
│ └── Old Generation                                       │
├──────────────────────────────────────────────────────────┤
│ Stack (per thread)                                       │
│ Method frames, local variables, operand stack            │
├──────────────────────────────────────────────────────────┤
│ PC Register (per thread) — current instruction address   │
├──────────────────────────────────────────────────────────┤
│ Native Method Stack (per thread) — for native C/C++ code │
└──────────────────────────────────────────────────────────┘
```

```java
public class JVMMemoryDemo {
    static int staticVar = 10;           // Method Area (Metaspace)
    int instanceVar = 20;               // Heap (part of object)

    public void method() {
        int localVar = 30;              // Stack frame
        String s = "Hello";            // Stack frame (reference); String in pool (Heap)
        Object obj = new Object();     // Stack (reference); Object in Heap
    } // method frame popped from stack; obj eligible for GC

    // JVM args to tune memory:
    // -Xms512m  → initial heap size
    // -Xmx4g    → max heap size
    // -Xss512k  → thread stack size
    // -XX:MetaspaceSize=256m → metaspace size
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 66. What is a memory leak in Java? How do you detect it?

A memory leak in Java occurs when **objects are no longer needed but are still referenced** — preventing GC from collecting them, causing heap to grow over time until `OutOfMemoryError`.

```java
// Common memory leak causes:

// 1. Static collections that grow but never shrink
static List<byte[]> cache = new ArrayList<>();
public void addToCache(byte[] data) {
    cache.add(data); // keeps growing — never removed!
}

// 2. Unclosed resources (streams, connections)
public void readFile() throws IOException {
    FileInputStream fis = new FileInputStream("file.txt");
    // if exception before close() — fis never closed — leak!
}
// Fix: use try-with-resources

// 3. Listeners/callbacks not removed
button.addActionListener(myListener); // held by button forever
// Fix: button.removeActionListener(myListener) when done

// 4. ThreadLocal not removed in thread pools
ThreadLocal<byte[]> local = new ThreadLocal<>();
local.set(new byte[1024 * 1024]); // 1MB per thread
// Fix: local.remove() when done

// Detection tools:
// - JVisualVM / JConsole — heap monitoring
// - Eclipse Memory Analyzer (MAT)
// - Heap dump analysis: jmap -dump:live,format=b,file=heap.hprof <pid>
// - JVM flags: -XX:+HeapDumpOnOutOfMemoryError
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. What is the difference between shallow copy and deep copy?

| Feature | Shallow Copy | Deep Copy |
| ------- | ------------ | --------- |
| What is copied | Object + references to nested objects | Object + new copies of all nested objects |
| Nested objects | Shared (same reference) | Independent copies |
| Method | `clone()` (default), copy constructor | `clone()` (overridden), serialization, manual |
| Memory | Less | More |

```java
class Address {
    String city;
    Address(String city) { this.city = city; }
}

class Person implements Cloneable {
    String name;
    Address address; // nested object

    Person(String name, Address address) {
        this.name = name;
        this.address = address;
    }

    // Shallow copy — default clone()
    @Override
    public Person clone() throws CloneNotSupportedException {
        return (Person) super.clone(); // copies name and address REFERENCE
    }

    // Deep copy — create new Address too
    public Person deepCopy() {
        return new Person(this.name, new Address(this.address.city));
    }
}

Person p1 = new Person("Sisi", new Address("Tirupati"));
Person p2 = p1.clone();     // shallow copy
Person p3 = p1.deepCopy();  // deep copy

p2.address.city = "Hyderabad";
System.out.println(p1.address.city); // "Hyderabad"! — p1 and p2 share same address

p3.address.city = "Chennai";
System.out.println(p1.address.city); // "Hyderabad" — p3 has independent address
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. What is serialization and deserialization in Java?

**Serialization** converts a Java object into a **byte stream** (for storage or network transmission). **Deserialization** converts the byte stream back into an object.

```java
import java.io.*;

// Class must implement Serializable
public class Employee implements Serializable {
    private static final long serialVersionUID = 1L; // version control
    String name;
    int age;
    transient String password; // transient — NOT serialized

    public Employee(String name, int age, String password) {
        this.name = name;
        this.age = age;
        this.password = password;
    }
}

// Serialization — object → file
Employee emp = new Employee("Sisi", 20, "secret123");
try (ObjectOutputStream oos = new ObjectOutputStream(new FileOutputStream("emp.ser"))) {
    oos.writeObject(emp);
    System.out.println("Serialized successfully");
}

// Deserialization — file → object
try (ObjectInputStream ois = new ObjectInputStream(new FileInputStream("emp.ser"))) {
    Employee restored = (Employee) ois.readObject();
    System.out.println("Name: " + restored.name);       // "Sisi"
    System.out.println("Age: " + restored.age);         // 20
    System.out.println("Password: " + restored.password); // null — transient!
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. What is the transient keyword?

The `transient` keyword marks a field that **should NOT be included in serialization** — its value will be `null` (for objects) or default (for primitives) when deserialized.

```java
public class UserSession implements Serializable {
    private static final long serialVersionUID = 1L;

    String username;                  // serialized
    String email;                     // serialized
    transient String password;        // NOT serialized — security concern
    transient Connection dbConn;      // NOT serialized — can't serialize DB connections
    transient int cacheSize;          // NOT serialized — computed at runtime
    static String appVersion = "1.0"; // NOT serialized — static fields never serialized

    // After deserialization: password = null, dbConn = null, cacheSize = 0
    // Implement readObject() to reinitialize transient fields after deserialization
    private void readObject(ObjectInputStream ois) throws IOException, ClassNotFoundException {
        ois.defaultReadObject();
        dbConn = Database.getConnection(); // reinitialize
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Design Patterns

<br>

### 70. What are design patterns? Name the most commonly asked ones

Design patterns are **proven, reusable solutions to commonly occurring problems** in software design.

| Category | Patterns | Purpose |
| -------- | -------- | ------- |
| **Creational** | Singleton, Factory, Abstract Factory, Builder, Prototype | Object creation |
| **Structural** | Adapter, Decorator, Proxy, Facade, Bridge | Object composition |
| **Behavioural** | Observer, Strategy, Command, Iterator, Template Method, Chain of Responsibility | Object communication |

**Most asked in MNC interviews:** Singleton, Factory, Builder, Observer, Strategy, Decorator

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. What is the Singleton pattern? How do you implement it thread-safely?

Singleton ensures **only one instance** of a class exists throughout the application.

```java
// Thread-safe Singleton — Double-Checked Locking (most common interview answer)
public class DatabaseManager {
    private static volatile DatabaseManager instance; // volatile — visibility
    private Connection connection;

    private DatabaseManager() {
        // private constructor — prevents external instantiation
        connection = DriverManager.getConnection(DB_URL);
    }

    public static DatabaseManager getInstance() {
        if (instance == null) {                    // first check (no lock)
            synchronized (DatabaseManager.class) {
                if (instance == null) {            // second check (with lock)
                    instance = new DatabaseManager();
                }
            }
        }
        return instance;
    }
}

// Simplest thread-safe Singleton — Enum (Joshua Bloch's recommendation)
public enum AppConfig {
    INSTANCE;

    private String apiKey = "abc123";
    public String getApiKey() { return apiKey; }
}

// Usage
AppConfig config = AppConfig.INSTANCE;
DatabaseManager db1 = DatabaseManager.getInstance();
DatabaseManager db2 = DatabaseManager.getInstance();
System.out.println(db1 == db2); // true — same instance
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. What is the Factory pattern?

The Factory pattern provides a **method for creating objects without specifying the exact class** to be created — the factory decides which subclass to instantiate.

```java
// Product interface
interface Notification {
    void send(String message);
}

// Concrete products
class EmailNotification implements Notification {
    @Override
    public void send(String message) { System.out.println("Email: " + message); }
}
class SMSNotification implements Notification {
    @Override
    public void send(String message) { System.out.println("SMS: " + message); }
}
class PushNotification implements Notification {
    @Override
    public void send(String message) { System.out.println("Push: " + message); }
}

// Factory — creates objects based on type
class NotificationFactory {
    public static Notification create(String type) {
        return switch (type.toUpperCase()) {
            case "EMAIL" -> new EmailNotification();
            case "SMS"   -> new SMSNotification();
            case "PUSH"  -> new PushNotification();
            default -> throw new IllegalArgumentException("Unknown type: " + type);
        };
    }
}

// Client code — doesn't know which class is created
Notification n = NotificationFactory.create("EMAIL");
n.send("Your order is shipped!"); // Email: Your order is shipped!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 73. What is the Builder pattern?

The Builder pattern constructs **complex objects step by step**, separating the construction process from the object's representation. Ideal when an object has many optional parameters.

```java
// Builder pattern — avoids telescoping constructors
public class Employee {
    private final String name;      // required
    private final String email;     // required
    private final String phone;     // optional
    private final String department; // optional
    private final double salary;    // optional

    private Employee(Builder builder) {
        this.name = builder.name;
        this.email = builder.email;
        this.phone = builder.phone;
        this.department = builder.department;
        this.salary = builder.salary;
    }

    public static class Builder {
        private String name;
        private String email;
        private String phone;
        private String department;
        private double salary;

        public Builder(String name, String email) { // required fields in constructor
            this.name = name;
            this.email = email;
        }
        public Builder phone(String phone) { this.phone = phone; return this; }
        public Builder department(String dept) { this.department = dept; return this; }
        public Builder salary(double salary) { this.salary = salary; return this; }
        public Employee build() { return new Employee(this); }
    }
}

// Clean usage — method chaining
Employee emp = new Employee.Builder("Sisi", "sisi@webortex.com")
    .phone("+91-9876543210")
    .department("Engineering")
    .salary(50000)
    .build();

// Lombok's @Builder does this automatically!
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. What is the Observer pattern?

The Observer pattern defines a **one-to-many dependency** — when one object (subject) changes state, all its dependents (observers) are notified and updated automatically.

```java
import java.util.*;

// Observer interface
interface Observer {
    void update(String event, Object data);
}

// Subject (Observable)
class EventBus {
    private Map<String, List<Observer>> listeners = new HashMap<>();

    public void subscribe(String event, Observer observer) {
        listeners.computeIfAbsent(event, k -> new ArrayList<>()).add(observer);
    }

    public void publish(String event, Object data) {
        List<Observer> eventListeners = listeners.getOrDefault(event, Collections.emptyList());
        eventListeners.forEach(obs -> obs.update(event, data));
    }
}

// Concrete observers
class EmailService implements Observer {
    @Override
    public void update(String event, Object data) {
        System.out.println("EmailService received " + event + ": " + data);
    }
}
class AuditLogger implements Observer {
    @Override
    public void update(String event, Object data) {
        System.out.println("AuditLog: " + event + " → " + data);
    }
}

// Usage
EventBus bus = new EventBus();
bus.subscribe("USER_REGISTERED", new EmailService());
bus.subscribe("USER_REGISTERED", new AuditLogger());

bus.publish("USER_REGISTERED", "sisi@webortex.com");
// EmailService received USER_REGISTERED: sisi@webortex.com
// AuditLog: USER_REGISTERED → sisi@webortex.com
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. What is the Strategy pattern?

Strategy defines a **family of algorithms, encapsulates each one, and makes them interchangeable** — the algorithm can vary independently from the client that uses it.

```java
// Strategy interface
interface SortStrategy {
    void sort(int[] arr);
}

// Concrete strategies
class BubbleSort implements SortStrategy {
    @Override
    public void sort(int[] arr) { System.out.println("Sorting with Bubble Sort"); }
}
class QuickSort implements SortStrategy {
    @Override
    public void sort(int[] arr) { System.out.println("Sorting with Quick Sort"); }
}

// Context — uses a strategy
class DataSorter {
    private SortStrategy strategy;

    public DataSorter(SortStrategy strategy) { this.strategy = strategy; }

    public void setStrategy(SortStrategy strategy) { this.strategy = strategy; }

    public void sort(int[] data) { strategy.sort(data); }
}

// Client can swap strategies at runtime
DataSorter sorter = new DataSorter(new BubbleSort());
sorter.sort(data);           // Sorting with Bubble Sort

sorter.setStrategy(new QuickSort());
sorter.sort(data);           // Sorting with Quick Sort

// Modern Java: use lambdas as strategies (functional approach)
DataSorter lambdaSorter = new DataSorter(arr -> Arrays.sort(arr));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Spring & Spring Boot

<br>

### 76. What is Spring Framework? What problem does it solve?

Spring is a **comprehensive Java application framework** that solves the problem of boilerplate code, tight coupling, and complexity in enterprise Java development.

**Problems it solves:**
- **Tight coupling** → Dependency Injection (loose coupling)
- **Boilerplate code** → Auto-configuration, annotations
- **Transaction management** → Declarative with `@Transactional`
- **Database access** → Spring Data JPA, JdbcTemplate
- **Security** → Spring Security
- **Testing** → Mockito, Spring Test

**Core modules:**
- `spring-core` — IoC container, DI
- `spring-context` — ApplicationContext, AOP
- `spring-web` / `spring-webmvc` — REST APIs
- `spring-data` — database access
- `spring-security` — authentication + authorization
- `spring-boot` — auto-configuration, embedded server

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. What is dependency injection? What are its types?

Dependency Injection (DI) is a design pattern where an object's **dependencies are provided externally** (by the Spring container) rather than the object creating them itself — achieving loose coupling.

```java
// ❌ Without DI — tight coupling
class UserService {
    private UserRepository repo = new UserRepository(); // hard-coded dependency
    private EmailService email = new EmailService();
}

// ✅ With DI — Spring injects dependencies

// Type 1: Constructor injection (RECOMMENDED — mandatory dependencies)
@Service
public class UserService {
    private final UserRepository userRepo;
    private final EmailService emailService;

    @Autowired // optional in newer Spring when only one constructor
    public UserService(UserRepository userRepo, EmailService emailService) {
        this.userRepo = userRepo;
        this.emailService = emailService;
    }
}

// Type 2: Setter injection (optional dependencies)
@Service
public class ReportService {
    private EmailService emailService;

    @Autowired
    public void setEmailService(EmailService emailService) {
        this.emailService = emailService;
    }
}

// Type 3: Field injection (convenient but NOT recommended — hard to test)
@Service
public class ProductService {
    @Autowired
    private ProductRepository productRepo; // Spring injects directly into field
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 78. What is Spring Boot? How is it different from Spring?

| Feature | Spring | Spring Boot |
| ------- | ------ | ----------- |
| Configuration | XML or Java config (verbose) | Auto-configuration (opinionated defaults) |
| Server | External (Tomcat, JBoss) | Embedded (Tomcat, Jetty, Undertow) |
| Startup | Complex setup | `@SpringBootApplication` + `main()` |
| Dependencies | Manual management | Starter POMs (`spring-boot-starter-web`) |
| Deployment | WAR file | JAR file (self-contained) |
| Properties | Many XML files | `application.properties` / `.yml` |

```java
// Minimal Spring Boot application
@SpringBootApplication // = @Configuration + @ComponentScan + @EnableAutoConfiguration
public class WebortexApp {
    public static void main(String[] args) {
        SpringApplication.run(WebortexApp.class, args); // starts embedded Tomcat
    }
}

// Spring Boot starter dependencies in pom.xml
// spring-boot-starter-web    → REST APIs (embedded Tomcat + Jackson + MVC)
// spring-boot-starter-data-jpa → JPA + Hibernate
// spring-boot-starter-security → Spring Security
// spring-boot-starter-test   → JUnit + Mockito
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. What are Spring Boot annotations you use most often?

```java
// Application level
@SpringBootApplication    // entry point + enable auto-config + component scan
@Configuration            // marks class as Spring config (bean definitions)
@EnableScheduling         // enables @Scheduled tasks
@EnableAsync              // enables @Async methods

// Component/Bean annotations
@Component                // generic Spring-managed component
@Service                  // business logic layer
@Repository               // data access layer (enables exception translation)
@Controller               // MVC controller (returns view names)
@RestController           // = @Controller + @ResponseBody (returns JSON/XML)

// REST API annotations
@RequestMapping("/api")   // maps URL prefix
@GetMapping("/users")     // HTTP GET
@PostMapping("/users")    // HTTP POST
@PutMapping("/users/{id}") // HTTP PUT
@PatchMapping("/users/{id}") // HTTP PATCH
@DeleteMapping("/users/{id}") // HTTP DELETE
@PathVariable             // extract from URL path: /users/{id}
@RequestParam             // extract from query string: /users?page=1
@RequestBody              // extract from request body (JSON → object)
@ResponseBody             // object → JSON response
@ResponseStatus(HttpStatus.CREATED) // set response status

// Dependency Injection
@Autowired                // inject dependency
@Qualifier("beanName")    // specify which bean to inject when multiple exist
@Primary                  // mark default bean when multiple exist
@Value("${app.name}")     // inject property value

// JPA / Database
@Entity                   // maps class to DB table
@Table(name = "users")    // specify table name
@Id                       // primary key field
@GeneratedValue           // auto-generate ID
@Column(nullable = false) // column constraints
@OneToMany, @ManyToOne, @ManyToMany, @OneToOne // relationships
@Transactional            // transaction management

// Testing
@SpringBootTest           // full context integration test
@WebMvcTest               // test only web layer (MVC)
@DataJpaTest              // test only JPA layer
@MockBean                 // mock Spring bean in test context
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. What is Spring MVC? How does a request flow through it?

Spring MVC is a **Model-View-Controller framework** built on top of the Servlet API for building web applications and REST APIs.

```
HTTP Request
     ↓
DispatcherServlet (Front Controller — receives all requests)
     ↓
HandlerMapping (finds which Controller handles this URL)
     ↓
Controller method executed → business logic → calls Service → Repository → DB
     ↓
Returns ResponseEntity / view name / @ResponseBody data
     ↓
ViewResolver (for MVC) OR HttpMessageConverter (for REST — converts to JSON)
     ↓
HTTP Response sent to client
```

```java
// REST Controller — simplest Spring MVC example
@RestController
@RequestMapping("/api/users")
public class UserController {

    @Autowired
    private UserService userService;

    @GetMapping
    public ResponseEntity<List<User>> getAllUsers() {
        return ResponseEntity.ok(userService.findAll());
    }

    @GetMapping("/{id}")
    public ResponseEntity<User> getUserById(@PathVariable Long id) {
        return userService.findById(id)
            .map(ResponseEntity::ok)
            .orElse(ResponseEntity.notFound().build());
    }

    @PostMapping
    public ResponseEntity<User> createUser(@Valid @RequestBody UserDTO dto) {
        User created = userService.create(dto);
        URI location = URI.create("/api/users/" + created.getId());
        return ResponseEntity.created(location).body(created);
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 81. What is Spring Data JPA? How is it different from Hibernate?

| Feature | Hibernate | Spring Data JPA |
| ------- | --------- | --------------- |
| What it is | JPA implementation (ORM) | Abstraction layer over JPA (including Hibernate) |
| Configuration | SessionFactory, HQL | Repository interfaces, JPQL |
| Boilerplate | More (session management) | Minimal — repository auto-implements CRUD |
| Queries | HQL / Criteria API | Method naming convention, `@Query` |
| Transactions | Manual or `@Transactional` | Same |

```java
// Spring Data JPA — just define the interface!
public interface UserRepository extends JpaRepository<User, Long> {
    // Spring Data generates implementation automatically

    // Derived queries — method name = query
    List<User> findByRole(String role);
    List<User> findByAgeGreaterThanAndIsActiveTrue(int age);
    Optional<User> findByEmail(String email);
    boolean existsByEmail(String email);
    long countByRole(String role);

    // Custom JPQL query
    @Query("SELECT u FROM User u WHERE u.createdAt >= :date AND u.role = :role")
    List<User> findRecentByRole(@Param("date") LocalDate date, @Param("role") String role);

    // Native SQL query
    @Query(value = "SELECT * FROM users WHERE salary > :amount", nativeQuery = true)
    List<User> findHighEarners(@Param("amount") double amount);
}

// Usage in service — zero SQL written!
@Service
public class UserService {
    @Autowired private UserRepository repo;

    public User create(User user) { return repo.save(user); }
    public Optional<User> findById(Long id) { return repo.findById(id); }
    public List<User> findAll() { return repo.findAll(); }
    public void delete(Long id) { repo.deleteById(id); }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 82. What is Spring Security? How do you secure a REST API?

Spring Security is a **powerful authentication and authorization framework** for Java applications.

```java
@Configuration
@EnableWebSecurity
public class SecurityConfig {

    @Bean
    public SecurityFilterChain filterChain(HttpSecurity http) throws Exception {
        http
            .csrf(csrf -> csrf.disable()) // disable CSRF for stateless REST APIs
            .sessionManagement(sm -> sm.sessionCreationPolicy(SessionCreationPolicy.STATELESS))
            .authorizeHttpRequests(auth -> auth
                .requestMatchers("/api/auth/**").permitAll()       // public endpoints
                .requestMatchers("/api/admin/**").hasRole("ADMIN") // admin only
                .requestMatchers(HttpMethod.GET, "/api/products/**").permitAll() // public reads
                .anyRequest().authenticated()                      // all else — must auth
            )
            .addFilterBefore(jwtAuthFilter, UsernamePasswordAuthenticationFilter.class);
        return http.build();
    }

    @Bean
    public PasswordEncoder passwordEncoder() {
        return new BCryptPasswordEncoder(12); // bcrypt cost factor 12
    }
}

// JWT Auth Filter
@Component
public class JwtAuthFilter extends OncePerRequestFilter {
    @Override
    protected void doFilterInternal(HttpServletRequest req, HttpServletResponse res, FilterChain chain)
            throws ServletException, IOException {
        String token = req.getHeader("Authorization");
        if (token != null && token.startsWith("Bearer ")) {
            String jwt = token.substring(7);
            String username = jwtService.extractUsername(jwt);
            UserDetails user = userDetailsService.loadUserByUsername(username);
            if (jwtService.isValid(jwt, user)) {
                UsernamePasswordAuthenticationToken authToken =
                    new UsernamePasswordAuthenticationToken(user, null, user.getAuthorities());
                SecurityContextHolder.getContext().setAuthentication(authToken);
            }
        }
        chain.doFilter(req, res);
    }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 83. What is application.properties vs application.yml in Spring Boot?

Both configure Spring Boot application settings — `.yml` supports hierarchical structure (cleaner for complex configs).

```properties
# application.properties — flat key-value
server.port=8080
spring.datasource.url=jdbc:mysql://localhost:3306/webortex
spring.datasource.username=root
spring.datasource.password=secret
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update
app.jwt.secret=mySecretKey
app.jwt.expiration=86400000
```

```yaml
# application.yml — hierarchical (same config, cleaner)
server:
  port: 8080

spring:
  datasource:
    url: jdbc:mysql://localhost:3306/webortex
    username: root
    password: secret
  jpa:
    show-sql: true
    hibernate:
      ddl-auto: update

app:
  jwt:
    secret: mySecretKey
    expiration: 86400000

---
# Multiple profiles in one file (yml only)
spring:
  config:
    activate:
      on-profile: production
  datasource:
    url: jdbc:mysql://prod-db:3306/webortex
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. What is the difference between @Component, @Service, @Repository, and @Controller?

All four are **specialisations of `@Component`** — they all tell Spring to create a bean. The difference is semantic (intended layer) and some have additional capabilities.

| Annotation | Layer | Extra behaviour |
| ---------- | ----- | --------------- |
| `@Component` | Generic | None — just a Spring bean |
| `@Service` | Business logic | Semantic clarity, no extra behaviour |
| `@Repository` | Data access | Translates persistence exceptions to Spring's `DataAccessException` |
| `@Controller` | Web/MVC | Works with `@RequestMapping`, `ViewResolver` |
| `@RestController` | REST API | = `@Controller` + `@ResponseBody` |

```java
@Component      // generic — when it doesn't fit other layers
class EmailFormatter { }

@Service        // business logic
class PaymentService { }

@Repository     // data access — SQLException → DataAccessException translation
class UserRepository { }

@Controller     // returns view names (MVC)
class HomeController { }

@RestController // returns JSON/XML (REST API)
class ApiController { }
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. What is Spring Boot Actuator?

Spring Boot Actuator provides **production-ready monitoring and management endpoints** for your Spring Boot application — without writing any code.

```xml
<!-- Add dependency -->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```

```yaml
# application.yml
management:
  endpoints:
    web:
      exposure:
        include: health,info,metrics,env,loggers,httptrace
  endpoint:
    health:
      show-details: always
```

| Endpoint | URL | Purpose |
| -------- | --- | ------- |
| `/actuator/health` | `GET` | App health status (UP/DOWN) |
| `/actuator/info` | `GET` | App info (version, description) |
| `/actuator/metrics` | `GET` | JVM metrics, HTTP requests, memory |
| `/actuator/env` | `GET` | Environment properties |
| `/actuator/loggers` | `GET/POST` | View/change log levels at runtime |
| `/actuator/beans` | `GET` | All Spring beans |
| `/actuator/mappings` | `GET` | All `@RequestMapping` routes |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Java New Features (Java 9–21)

<br>

### 86. What are the major features introduced in Java 9 to Java 21?

| Version | Key Features |
| ------- | ------------ |
| **Java 9** | Module System (JPMS), JShell (REPL), Collection factory methods (`List.of()`) |
| **Java 10** | Local variable type inference (`var`) |
| **Java 11** | `String` methods (`isBlank()`, `strip()`, `lines()`), `HttpClient` API, LTS |
| **Java 14** | Switch expressions (standard), `instanceof` pattern matching (preview) |
| **Java 15** | Text blocks (standard), Sealed classes (preview) |
| **Java 16** | Records (standard), `instanceof` pattern matching (standard) |
| **Java 17** | Sealed classes (standard), LTS |
| **Java 21** | Virtual threads (Project Loom), Record patterns, Sequenced collections, LTS |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 87. What are records in Java 16+?

Records are **immutable data carrier classes** — they automatically generate constructor, getters, `equals()`, `hashCode()`, and `toString()`.

```java
// Before records — verbose POJO
public class Point {
    private final int x;
    private final int y;
    public Point(int x, int y) { this.x = x; this.y = y; }
    public int x() { return x; }
    public int y() { return y; }
    @Override public boolean equals(Object o) { /* ... */ }
    @Override public int hashCode() { /* ... */ }
    @Override public String toString() { return "Point[x=" + x + ", y=" + y + "]"; }
}

// With records — just one line!
public record Point(int x, int y) { }

// Usage
Point p1 = new Point(3, 4);
System.out.println(p1.x());       // 3
System.out.println(p1.y());       // 4
System.out.println(p1);           // Point[x=3, y=4]
System.out.println(p1.equals(new Point(3, 4))); // true

// Records can have: custom methods, compact constructors, implement interfaces
public record Employee(String name, double salary) implements Comparable<Employee> {
    // Compact constructor — validation
    public Employee {
        if (salary < 0) throw new IllegalArgumentException("Negative salary");
        name = name.trim(); // normalise
    }
    // Custom method
    public double annualSalary() { return salary * 12; }
    @Override
    public int compareTo(Employee other) { return Double.compare(this.salary, other.salary); }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 88. What are sealed classes in Java?

Sealed classes **restrict which classes can extend or implement them** — providing controlled inheritance.

```java
// Sealed class — only these classes can extend Shape
public sealed class Shape permits Circle, Rectangle, Triangle { }

// Each permitted subclass must be: final, sealed, or non-sealed
public final class Circle extends Shape {
    double radius;
    public Circle(double radius) { this.radius = radius; }
    public double area() { return Math.PI * radius * radius; }
}

public final class Rectangle extends Shape {
    double width, height;
    // ...
}

public non-sealed class Triangle extends Shape {
    // non-sealed: any class can extend Triangle
}

// Sealed classes work perfectly with pattern matching switch (Java 21)
double getArea(Shape shape) {
    return switch (shape) {
        case Circle c    -> Math.PI * c.radius() * c.radius();
        case Rectangle r -> r.width() * r.height();
        case Triangle t  -> t.base() * t.height() / 2;
        // No default needed — compiler knows all permitted subclasses!
    };
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 89. What are virtual threads in Java 21 (Project Loom)?

Virtual threads are **lightweight threads managed by the JVM** (not the OS) — allowing millions of threads without the overhead of OS threads.

```java
// Platform thread (traditional) — maps 1:1 to OS thread
// Limited: OS typically supports ~10,000 threads, each uses ~1MB stack

// Virtual thread (Java 21) — mapped many:1 to OS threads by JVM
// Lightweight: can create millions, uses ~few KB each

// Creating virtual threads
Thread vt = Thread.ofVirtual().start(() -> System.out.println("Virtual thread!"));

// With ExecutorService
try (ExecutorService executor = Executors.newVirtualThreadPerTaskExecutor()) {
    // Creates a virtual thread for EACH task — 100,000 tasks = 100,000 virtual threads
    // JVM efficiently maps these to a few OS threads
    for (int i = 0; i < 100_000; i++) {
        executor.submit(() -> {
            Thread.sleep(Duration.ofSeconds(1)); // blocking — virtual thread "parks", OS thread freed
            return "done";
        });
    }
} // executor closed — waits for all tasks

// Spring Boot 3.2+ — enable virtual threads for all HTTP requests
// application.yml:
// spring.threads.virtual.enabled: true

// Why it matters:
// Traditional: 1000 concurrent requests → 1000 OS threads → heavy, limits scalability
// Virtual: 1000 concurrent requests → 1000 virtual threads → mapped to few OS threads → lightweight
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. What is pattern matching in Java?

Pattern matching simplifies **type checking and casting** — removing boilerplate `instanceof` checks and casts.

```java
// Before Java 16 — verbose instanceof + cast
Object obj = "Hello";
if (obj instanceof String) {
    String s = (String) obj; // redundant cast
    System.out.println(s.toUpperCase());
}

// Java 16+ — pattern matching for instanceof
if (obj instanceof String s) { // binding variable 's' — cast happens automatically
    System.out.println(s.toUpperCase());
}

// Java 21 — pattern matching in switch (record patterns)
sealed interface Shape permits Circle, Rectangle { }
record Circle(double radius) implements Shape { }
record Rectangle(double w, double h) implements Shape { }

// Pattern matching switch — no default needed for sealed types!
String describe(Shape shape) {
    return switch (shape) {
        case Circle c when c.radius() > 10 -> "Large circle with r=" + c.radius();
        case Circle c -> "Small circle with r=" + c.radius();
        case Rectangle r -> "Rectangle " + r.w() + "×" + r.h();
    };
}

// Deconstruction patterns (Java 21)
record Point(int x, int y) { }
Object o = new Point(3, 4);
if (o instanceof Point(int x, int y)) { // extracts x and y directly!
    System.out.println("Point at " + x + ", " + y);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 91. What is the difference between an abstract class and an interface? When to use which?

> Covered in Q21. Key decision guide:

```
Use Abstract Class when:
✅ Classes share common code (state + behaviour)
✅ You need constructors with initialization logic
✅ You want to use access modifiers (private/protected methods)
✅ Strong "is-a" relationship (Dog IS-A Animal)
✅ Want to provide default implementation that subclasses can override

Use Interface when:
✅ Defining a contract/capability (Flyable, Serializable, Comparable)
✅ Multiple inheritance of type is needed (class implements A, B, C)
✅ Unrelated classes should share a capability
✅ You expect the "contract" to evolve carefully (adding default methods)

// Example decision:
// ✅ Animal (abstract class) — shares state (name, age) + behaviour (eat, sleep)
// ✅ Flyable (interface) — Birds AND Planes can fly — unrelated classes, shared capability
// ✅ Comparable (interface) — any class can define its own comparison logic
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. How does HashMap handle collisions internally?

```java
// When two different keys produce the same bucket index, a COLLISION occurs
// Example: "abc".hashCode() and "xyz".hashCode() might map to same bucket

// Java HashMap collision resolution: SEPARATE CHAINING
// Each bucket holds a linked list (or tree) of entries

// Java 8 optimization:
// - Bucket has <= 8 entries → LinkedList (O(n) lookup per bucket)
// - Bucket has > 8 entries → Red-Black Tree (O(log n) lookup per bucket)
// - Tree converts back to list if entries drop to 6

// HashMap state: (default capacity=16, load factor=0.75)
// When entries > capacity * loadFactor (16 * 0.75 = 12):
// → RESIZE: double capacity (32), rehash all entries into new array

// Practical impact:
HashMap<String, Integer> map = new HashMap<>(1000, 0.5f);
// capacity=1000, loadFactor=0.5 → resizes when 500 entries
// More memory but fewer collisions → faster lookups

// Always override both hashCode() and equals() in keys:
// If only equals() → same logical key → different hash → stored in wrong bucket
// If only hashCode() → same hash → goes to same bucket, but equals() returns false → duplicates
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. How would you reverse a String in Java without using reverse()?

```java
// Method 1: CharArray loop
public static String reverseWithLoop(String s) {
    char[] chars = s.toCharArray();
    int left = 0, right = chars.length - 1;
    while (left < right) {
        char temp = chars[left];
        chars[left] = chars[right];
        chars[right] = temp;
        left++;
        right--;
    }
    return new String(chars);
}

// Method 2: Recursion
public static String reverseRecursive(String s) {
    if (s.length() <= 1) return s;
    return reverseRecursive(s.substring(1)) + s.charAt(0);
}

// Method 3: Stack
public static String reverseWithStack(String s) {
    Stack<Character> stack = new Stack<>();
    for (char c : s.toCharArray()) stack.push(c);
    StringBuilder sb = new StringBuilder();
    while (!stack.isEmpty()) sb.append(stack.pop());
    return sb.toString();
}

// Method 4: StringBuilder (without reverse()) — append in reverse index order
public static String reverseWithSB(String s) {
    StringBuilder sb = new StringBuilder();
    for (int i = s.length() - 1; i >= 0; i--) {
        sb.append(s.charAt(i));
    }
    return sb.toString();
}

System.out.println(reverseWithLoop("Sisi")); // "isiS"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. How do you find duplicate elements in an array?

```java
int[] arr = {1, 2, 3, 2, 4, 3, 5, 1};

// Method 1: HashSet — O(n) time, O(n) space
public static Set<Integer> findDuplicatesWithSet(int[] arr) {
    Set<Integer> seen = new HashSet<>();
    Set<Integer> duplicates = new HashSet<>();
    for (int num : arr) {
        if (!seen.add(num)) { // add() returns false if already present
            duplicates.add(num);
        }
    }
    return duplicates; // {1, 2, 3}
}

// Method 2: HashMap — count occurrences O(n) time, O(n) space
public static Map<Integer, Integer> countFrequency(int[] arr) {
    Map<Integer, Integer> freq = new HashMap<>();
    for (int num : arr) {
        freq.merge(num, 1, Integer::sum); // elegant way to count
    }
    freq.entrySet().removeIf(e -> e.getValue() == 1); // keep only duplicates
    return freq; // {1=2, 2=2, 3=2}
}

// Method 3: Streams — declarative
List<Integer> duplicates = Arrays.stream(arr)
    .boxed()
    .collect(Collectors.groupingBy(n -> n, Collectors.counting()))
    .entrySet().stream()
    .filter(e -> e.getValue() > 1)
    .map(Map.Entry::getKey)
    .collect(Collectors.toList());

System.out.println(duplicates); // [1, 2, 3]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. How do you make a class immutable in Java?

```java
// Rules for making a class immutable:
// 1. Declare class as final (prevent subclassing)
// 2. All fields private and final
// 3. No setter methods
// 4. Initialize all fields via constructor
// 5. For mutable fields (List, Date, array) — return defensive copies

public final class ImmutableEmployee {      // Rule 1: final class
    private final String name;             // Rule 2: private final
    private final int age;
    private final List<String> skills;     // mutable field — needs defensive copy
    private final Date joiningDate;        // java.util.Date is mutable!

    public ImmutableEmployee(String name, int age, List<String> skills, Date joiningDate) {
        this.name = name;
        this.age = age;
        this.skills = List.copyOf(skills);          // Rule 5: defensive copy in constructor
        this.joiningDate = new Date(joiningDate.getTime()); // defensive copy
    }

    // Rule 3: getters only, no setters
    public String getName() { return name; }
    public int getAge() { return age; }
    public List<String> getSkills() { return List.copyOf(skills); }  // Rule 5: defensive copy in getter
    public Date getJoiningDate() { return new Date(joiningDate.getTime()); } // defensive copy
}

// Why immutability?
// - Thread-safe (no synchronization needed)
// - Safe HashMap keys
// - Predictable behaviour, easier to test
// Examples of immutable classes in Java: String, Integer, LocalDate, BigDecimal
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. What is the difference between HashMap and TreeMap?

| Feature | HashMap | TreeMap |
| ------- | ------- | ------- |
| Order | No order | Sorted by key (natural or custom) |
| Performance | O(1) average | O(log n) |
| Null keys | ✅ One null | ❌ No null key |
| Implementation | Hash table | Red-Black Tree |
| Implements | `Map` | `Map`, `SortedMap`, `NavigableMap` |
| Use when | Fast lookup, no order | Sorted keys, range queries |

```java
// HashMap — fast, unordered
Map<String, Integer> hashMap = new HashMap<>();
hashMap.put("Banana", 2); hashMap.put("Apple", 1); hashMap.put("Cherry", 3);
System.out.println(hashMap); // {Apple=1, Banana=2, Cherry=3} — random order!

// TreeMap — sorted by key
Map<String, Integer> treeMap = new TreeMap<>(hashMap);
System.out.println(treeMap); // {Apple=1, Banana=2, Cherry=3} — sorted alphabetically

// TreeMap extra methods (NavigableMap)
treeMap.firstKey();                     // "Apple"
treeMap.lastKey();                      // "Cherry"
treeMap.headMap("Banana");             // {Apple=1} — keys before "Banana"
treeMap.tailMap("Banana");             // {Banana=2, Cherry=3} — keys from "Banana"
treeMap.subMap("Apple", "Cherry");     // {Apple=1, Banana=2} — range

// Custom key order
Map<String, Integer> byLength = new TreeMap<>(Comparator.comparingInt(String::length));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. What happens if you override equals() but not hashCode()?

```java
class Student {
    String name;
    int rollNo;

    Student(String name, int rollNo) { this.name = name; this.rollNo = rollNo; }

    @Override
    public boolean equals(Object o) { // only equals, no hashCode!
        if (this == o) return true;
        if (!(o instanceof Student)) return false;
        Student s = (Student) o;
        return rollNo == s.rollNo && Objects.equals(name, s.name);
    }
    // hashCode() NOT overridden — uses Object.hashCode() = based on memory address
}

Student s1 = new Student("Sisi", 101);
Student s2 = new Student("Sisi", 101);

System.out.println(s1.equals(s2));  // true — equals() works correctly

// But HashMap breaks!
Set<Student> set = new HashSet<>();
set.add(s1);
System.out.println(set.contains(s2)); // false! — s1 and s2 have DIFFERENT hashCodes
                                      // HashMap looks in wrong bucket → can't find s2

Map<Student, String> map = new HashMap<>();
map.put(s1, "Grade A");
map.get(s2); // null! — different hashCode → wrong bucket → not found

// Rule: If a.equals(b) is true → a.hashCode() MUST equal b.hashCode()
// Always override both together! Use Objects.hash() for convenience:
@Override
public int hashCode() { return Objects.hash(name, rollNo); }
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. What is a ConcurrentModificationException and how do you avoid it?

`ConcurrentModificationException` is thrown when a **fail-fast collection is modified during iteration** (except through the iterator's own `remove()` method).

```java
List<String> list = new ArrayList<>(Arrays.asList("A", "B", "C", "D"));

// ❌ Causes ConcurrentModificationException
for (String s : list) {
    if (s.equals("B")) list.remove(s); // structural modification during iteration!
}

// ✅ Fix 1: Use Iterator.remove()
Iterator<String> it = list.iterator();
while (it.hasNext()) {
    if (it.next().equals("B")) it.remove(); // safe — iterator tracks modification
}

// ✅ Fix 2: Collect to remove, then removeAll
List<String> toRemove = list.stream()
    .filter(s -> s.equals("B"))
    .collect(Collectors.toList());
list.removeAll(toRemove);

// ✅ Fix 3: removeIf (Java 8) — cleanest
list.removeIf(s -> s.equals("B"));

// ✅ Fix 4: CopyOnWriteArrayList (for multi-threaded scenarios)
List<String> safeList = new CopyOnWriteArrayList<>(list);
for (String s : safeList) {
    if (s.equals("B")) safeList.remove(s); // no exception — iterates over snapshot
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. How do you sort a list of objects by a field in Java?

```java
class Employee {
    String name;
    int age;
    double salary;
    String department;

    Employee(String name, int age, double salary, String department) {
        this.name = name; this.age = age;
        this.salary = salary; this.department = department;
    }
    // getters...
}

List<Employee> employees = Arrays.asList(
    new Employee("Sisi", 20, 50000, "Engineering"),
    new Employee("Yamini", 21, 45000, "HR"),
    new Employee("Pavani", 19, 55000, "Engineering")
);

// Method 1: Comparator.comparing() — sort by single field
employees.sort(Comparator.comparing(Employee::getName));          // by name A-Z
employees.sort(Comparator.comparingDouble(Employee::getSalary)); // by salary ascending
employees.sort(Comparator.comparingInt(Employee::getAge).reversed()); // by age descending

// Method 2: Multi-field sort (by dept, then by salary descending)
employees.sort(
    Comparator.comparing(Employee::getDepartment)
              .thenComparingDouble(Employee::getSalary).reversed()
);

// Method 3: Streams — returns new sorted list (doesn't modify original)
List<Employee> sorted = employees.stream()
    .sorted(Comparator.comparingDouble(Employee::getSalary).reversed())
    .collect(Collectors.toList());

// Method 4: Implement Comparable (natural ordering)
class Employee implements Comparable<Employee> {
    @Override
    public int compareTo(Employee other) {
        return Double.compare(this.salary, other.salary);
    }
}
Collections.sort(employees); // uses compareTo()
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. What are the latest trends in Java development (2024–2025)?

| Trend | Description |
| ----- | ----------- |
| **Java 21 LTS** | Most teams migrating to Java 21 — Virtual threads, Records, Sealed classes, Pattern matching |
| **Virtual threads** | Game-changer for I/O-heavy apps — millions of threads with no overhead |
| **Spring Boot 3.x** | Full Java 17+ baseline, native compilation, virtual thread support |
| **GraalVM Native Image** | Compile Java to native binary — instant startup, low memory |
| **Quarkus / Micronaut** | Cloud-native Java frameworks — faster than Spring Boot for microservices |
| **Jakarta EE 10** | Renamed from Java EE — modern enterprise APIs |
| **Reactive programming** | Project Reactor, WebFlux, RxJava — non-blocking I/O for high concurrency |
| **Kotlin on JVM** | Increasingly popular alongside Java — fully interoperable |
| **Records + Sealed classes** | Replacing Lombok for DTOs and modelling domain types |
| **Pattern matching switch** | Replacing complex if-else chains and visitor patterns |
| **AI integration** | LangChain4j — LLM integration for Java applications |
| **JVM observability** | OpenTelemetry, Micrometer, JFR (Java Flight Recorder) |

```java
// Modern Java 21 code — clean, concise, type-safe
public sealed interface Result<T> permits Result.Success, Result.Failure {
    record Success<T>(T value) implements Result<T> { }
    record Failure<T>(String error) implements Result<T> { }

    static <T> Result<T> of(Supplier<T> supplier) {
        try { return new Success<>(supplier.get()); }
        catch (Exception e) { return new Failure<>(e.getMessage()); }
    }
}

// Pattern matching switch (Java 21)
String describe(Result<?> result) {
    return switch (result) {
        case Result.Success<?> s -> "Got: " + s.value();
        case Result.Failure<?> f -> "Error: " + f.error();
    };
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

<div align="center">

## 🎉 You've covered all 100 Java Interview Questions!

---

**If this repo helped your interview prep, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/java-interview-questions?style=social)](https://github.com/sisi-tarak/java-interview-questions)

---

### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a mistake, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/java-interview-questions/pulls)** — all contributions are welcome! 🙌

---

### 📦 More Interview Repos

| Status | Repository |
| ------ | ---------- |
| ✅ Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
| ✅ Live | [mern-interview-questions](https://github.com/sisi-tarak/mern-interview-questions) |
| ✅ Live | [java-interview-questions](https://github.com/sisi-tarak/java-interview-questions) |
| 🔜 Coming | nodejs-interview-questions |
| 🔜 Coming | dsa-interview-questions |
| 🔜 Coming | python-interview-questions |

⭐ **Star this repo to get notified when new repos drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, Amazon, Flipkart, and other product companies. We cannot guarantee these exact questions will appear in your interview. The goal is to build conceptual clarity and real-world understanding, not memorization.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
