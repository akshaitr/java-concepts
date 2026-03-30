# Java (For JS Developers)

1. [Java Fundamentals](https://github.com/akshaitr/java-concepts/blob/main/README.md#java-fundamentals)

# Java Fundamentals

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

**Reference types** — everything else. Objects, arrays, strings. The variable doesn't hold the data — it holds a pointer to where the data lives.

```java
String name = "Karthik";  // 'name' points to a String object
int[] scores = {90, 85, 70}; // 'scores' points to an array object
```

${\textsf{\color{khaki}Guess\ the\ output}}$

```java
int a = 10;
int b = a;      
b = 20;
System.out.println(a);
```

${\textsf{\color{khaki}Guess\ the\ output}}$

```java
int[] x = {1, 2, 3};
int[] y = x;
y[0] = 99;
System.out.println(x[0]); // 99! Because x and y point to the same data.
```

Think of primitives as values written directly on a sticky note. Think of reference types as a sticky note with an address written on it, pointing to a locker where the actual data lives. Two sticky notes can have the same address — which means they share the same locker.

📢 NOTES: 

> In JavaScript, null and undefined can appear anywhere. In Java, primitive types cannot be null. Only reference types can be null, which means NullPointerException — you'll meet this error often, and now you know exactly why it happens.

${\textsf{\color{khaki}Guess\ the\ output}}$

```java
String a = "hello";
String b = a;
int x = 10;
int y = x;

b = "world";
y = 20;

System.out.println(a);
System.out.println(x);
```
