# Methods - [CheatSheet](https://www.codecademy.com/learn/learn-java/modules/learn-java-object-oriented-java-u/cheatsheet "Cheatsheet")

### Syntax 

- To declare -> `public class ClassName{
                      public void Method()
                  }`

- A class is a blueprint to create instances. It defines the state and behavior of these instances.
- Every class has a special method called constructor which is invoked when a new object is created. Constructors initialize the state of newly created instances.
- Instance fields define the characteristics of an object. We can declare them within a class but outside of any method or constructor.
- We use the dot operator (.) to access the instance fields.
- A program can have multiple classes, instances, and instance fields as per our program’s requirements.


   - Example :
```java
public class Dog {
  // instance fields
    String breed;
    boolean hasOwner;
    int age;

public Dog(String dogBreed, boolean dogOwned, int dogYears) {
  // constructor method
    System.out.println(“Constructor invoked!”);
    breed = dogBreed;
    hasOwner = dogOwned;
    age = dogYears;
    }

public static void main(String[] args) {
    System.out.println(“Main method started”);
    Dog fido = new Dog(“poodle”, false, 4);
    Dog nunzio = new Dog(“shiba inu”, true, 12);
    boolean isFidoOlder = fido.age > nunzio.age;
    int totalDogYears = nunzio.age + fido.age;
    System.out.println(“Two dogs created: a “ + fido.breed + “ and a “ + nunzio.breed);
    System.out.println(“The statement that fido is an older dog is: “ + isFidoOlder);
    System.out.println(“The total age of the dogs is: “ + totalDogYears);
    System.out.println(“Main method finished”);
    }
}
```

### Review 

- Defining a method : Method declarations will declare a method’s return type, name, and parameters
- Calling a method : Methods are invoked with a . and ()
- Parameters : Inputs to the method and their types are declared in parentheses in the method signature
- Changing Instance Fields : Methods can be used to change the value of an instance field
- Scope : Variables only exist within the domain that they are created in
- Return : The type of the variables that will be output are declared in the method declaration

