# Java Basics – Day 1

## Introduction to Java
Java is a high-level, object-oriented, and platform-independent programming language.
It follows the principle **Write Once, Run Anywhere**.

---

## JDK (Java Development Kit)
- Used to develop Java applications
- Contains compiler (javac), JRE, and development tools

## JRE (Java Runtime Environment)
- Provides libraries and JVM
- Required to run Java programs

## JVM (Java Virtual Machine)
- Converts bytecode into machine code
- Manages memory and garbage collection

---

## Relationship Between JDK, JRE, JVM
JDK → JRE → JVM

---

## Data Types in Java
Java data types are classified into:
1. Primitive Data Types
2. Non-Primitive Data Types

---

## 1. Primitive Data Types

Primitive data types store **simple values** and occupy **fixed memory size**.

| Data Type | Size    | Range |
|----------|---------|-------|
| byte     | 1 byte  | -128 to 127 |
| short    | 2 bytes | -32,768 to 32,767 |
| int      | 4 bytes | -2³¹ to 2³¹-1 |
| long     | 8 bytes | -2⁶³ to 2⁶³-1 |
| float    | 4 bytes | ~6–7 decimal digits |
| double   | 8 bytes | ~15 decimal digits |
| char     | 2 bytes | 0 to 65,535 (Unicode) |
| boolean  | 1 bit   | true / false |

---

## 2. Non-Primitive Data Types

Non-primitive data types store **references to objects**.

### Examples:
- String
- Array
- Class
- Interface
- Object

### Characteristics:
- No fixed size
- Can store multiple values
- Created using `new` keyword (except String)

---

## Primitive vs Non-Primitive Data Types

| Primitive | Non-Primitive |
|----------|---------------|
| Stores actual value | Stores reference (address) |
| Fixed size | No fixed size |
| Faster | Comparatively slower |
| Cannot be null | Can be null |
| Examples: int, char | Examples: String, Array |

---

## Variables
Variables are used to store data values in a program.

### Rules:
- Must start with a letter, `_` or `$`
- Cannot use keywords
- Case-sensitive

---

## Example Program
```java
class DataTypesDemo {
    public static void main(String[] args) {
        int age = 20;
        double salary = 25000.75;
        char grade = 'A';
        boolean isStudent = true;

        String name = "java";
        int[] marks = {80, 85, 90};

        System.out.println(age);
        System.out.println(salary);
        System.out.println(grade);
        System.out.println(isStudent);
        System.out.println(name);
        System.out.println(marks.length);
    }
}
_Last updated on Day 1_
