# Java (For JS Developers)

1. [Java Fundamentals](https://github.com/akshaitr/java-concepts/blob/main/README.md#java-fundamentals)

# Java Fundamentals

This is the single most important concept that JavaScript hides from you completely, and it governs everything in Java.

In JavaScript, you never think about this:
```javascript
let a = 5;       // where does this live? You don't care.
let b = [1,2,3]; // where does this live? You don't care.
```

JS manages all memory for you behind the scenes. In Java, there are two distinct types of data, and they behave completely differently:

**Primitive types** — stored directly in memory, small, fast. These are the building blocks:
```java
int age = 30;           // integer (no decimals)
double salary = 85000.50; // decimal number
boolean isActive = true;  // true or false
char grade = 'A';        // single character
```
