# Conditionals & Control flow

- ### if-then
      - code block runs if condition is true

- ### if-then-else:
  -  one block runs if conditions is true
  - another block runs if condition is false

- ### if-then-else chained:
  - same as if-then but an arbitrary number of conditions

```java
  if (condition) {
    // consequent path
} else if {
    // alternative path
} else {
}
```

- ### Switch

  - switch block runs if condition value matches case value

```java
      String course = "History";
      
      switch (course) {
        case "Algebra": 
          // Enroll in Algebra
          break; 
        case "Biology": 
          // Enroll in Biology
          break;
        case "History": 
          // Enroll in History
          break;
        case "Theatre":
          // Enroll in Theatre
          break;
        default:
          System.out.println("Course not found");
      }
```

- ### Condition - AND : &&
  
```
true && true
// true
false && true
// false
true && false
// false
false && false
// false
```

- ### Condition - OR : ||

```
true || true
// true
false || true
// true
true || false
// true
false || false
// false
```

- On some occasions, the compiler can determine the truth value of a logical expression by only evaluating the first boolean operand; this is known as short-circuited evaluation. Short-circuited evaluation only works with expressions that use && or ||.

In an expression that uses ||, the resulting value will be true as long as one of the operands has a true value. If the first operand of an expression is true, we don’t need to see what the value of the other operand is to know that the final value will also be true.

- ### Logical NOT : !

```
  !false
// true
!true
// false
```
