# Access, Encapsulation and Scope

## Scope 

Local variables can only be used within the scope that they were defined in.

## Encapsulation

Encapsulation is a technique used to keep implementation details hidden from other classes. Its aim is to create small bundles of logic.

## "This" keyword 

The public and private keywords are used to define what parts of code have access to other classes, methods, constructors, and instance variables.

- The this keyword can be used to designate the difference between instance variables and local variables.
- The this keyword can be used to call methods when writing classes.

 - Variable :
   
```java
public class Dog{
  public String name;

  public Dog(String inputName){
    name = inputName;
  }

  public void speakNewName(String name){
    System.out.println("Hello, my new name is" + this.name);
  }
    
  public static void main(String[] args){
    Dog a = new Dog("Fido");
    Dog b = new Dog("Odie");

    a.speakNewName("Winston");
    // "Fido", the instance variable of Dog a is printed. "Winston" is ignored

    b.speakNewName("Darla");
    // "Odie", the instance variable of Dog b is printed. "Darla" is ignored.
  }
}
```

- Method :

  ```java
    public class Computer{
    public int brightness;
    public int volume;
    
    public void setBrightness(int inputBrightness){
      this.brightness = inputBrightness;
    }
  
    public void setVolume(int inputVolume){
      this.volume = inputVolume;
    }
  
    public void resetSettings(){
      this.setBrightness(0);
      this.setVolume(0);
    }
  }
```



