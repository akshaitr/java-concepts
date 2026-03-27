# Java (For JS Developers)

1. [Java Fundamentals](https://github.com/akshaitr/java-concepts/blob/main/README.md#java-fundamentals)

# Java Fundamentals

Primitive data types

They have their own independant copies of the data.

- byte
- short
- int
- float
- double
- long
- boolean
- char

```java
int num = 10;
char initial = 't';
boolean isDelivered = true;
```

Reference data types

They point to a reference or address to where the actual data is stored

- String
- Array
- Class

```java
String state = "Columbia"
int[] marks = {45, 50, 44, 47};
```

When copied:

```java
int a = 10;
int b = a; // simply copies the value in a
b = 9; // doesn't change the value in a

int[] marks = {10, 20, 30, 40};
int[] score = marks; // score refer to the same array marks points to
score[0] = 15; // changes the values in marks
```


Now reassignment is another thing.

```java
score = {10, 15, 20, 25} // changes the pointer
```

reassignment changes the pointer, mutation changes the shared data.


Primitives can't be null

```
int x = 10;
x = null // wrong
```

reference types can be null
