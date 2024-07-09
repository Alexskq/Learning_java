# Loop

## while
```java
while (condition) {

 // code

}
```
## for
```java
for (int i = 0; i < 5; i++) {

  // code that will run

}
```

## for-each 
```java
for (String inventoryItem : inventoryItems) {

  // do something with each inventoryItem

}
```
## Removing an element
```java
for (int i = 0; i < lst.size(); i++) {
  if (lst.get(i) == "value to remove"){
    // remove value from ArrayList
    lst.remove(lst.get(i));
    // Decrease loop control variable by 1
    i--;    
  }
}
```
