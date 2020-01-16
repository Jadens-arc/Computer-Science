# with Jaden

## Java Docs

**For Entire Program**
``` java 
/*
*@ AUTHOR:
*@ ASSIGNMENT: 
*@ DATE:
*@ VERSION:
*@ FEEDBACK:
*/
```

**For Method**
``` java
/*
Pre: any variables that need to be declared before the function can be ran 
Param: any parameters used and their data type[ex. String name] 
Post: any thing that will be printed to the screen 
Return: what will be returned when the method is ran 
*/
```

**End of Any Curly Bracket**
``` java 
// ends the [if-statement, for-loop, while-loop, method, class, try/catch, etc]
```

## Data Types

### Primitives:
#### Int
largest number is 2147483647
``` java
int myInt = 8;
```

#### Short
largest number is 
``` java
short myShort 
```

#### Long
``` java
```

#### Float
``` java
```

#### Double
``` java
```

#### Byte
``` java
```

#### Char
``` java
```

#### Boolean
``` java
```

### Non-Primitives:
#### String
``` java
```

#### Array List
``` java
```

#### Array
``` java
```

## Structure of a Program
Generally a Java program is made up of two main files

The first file(Main File) which contains all the classes and methods

And the second file(Driver) that calls these classes and methods

**Main File**
``` java 
class Main
{ 
  Private String greeting;
  Private String name;
  
  Public Main(String username, String userGreeting = "hello ")
  {
    greeting = userGreeting;
    name = username;
  }
  
  Public void sayHi()
  {
    System.out.println(greeting + name);
  }
}

```

**Driver**
```java 
class Driver
{
  Public static main(String[] args)
  {
    Main myGuy = new Main("Jaden");
    myGuy.sayHi();
    
    Main myGuy2 = new Main("Dom", "hi ");
    myGuy2.sayHi();
  }
}

```

**Output**
```
> hello Jaden
> hi Dom
```



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTMxMzYyMDUzOF19
-->