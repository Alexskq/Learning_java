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
} else {
    // alternative path
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
