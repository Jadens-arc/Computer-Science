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
largest number is 2,147,483,647
- must be a whole number
- can be positive or negative

``` java
int myInt = 8;
```

#### Byte
largest number is 127
- must be a whole number
- can be positive or negative

``` java
byte myByte = 8;
```

#### Short
largest number is 32,767
- must be a whole number
- can be positive or negative

``` java
short myShort = 8;
```

#### Long
largest number is 9,223,372,036,854,775,807
- must be a whole number
- can be positive or negative

``` java
long myLong = 8;
```

#### Float
argest number is approximately ±3.40282347E+38F  
(6-7 significant decimal digits)
- does not have to be whole

``` java
float myFloat = 9.41;
```

#### Double
largest number is approximately ±1.79769313486231570E+308  
(15 significant decimal digits)
- does not have to be whole

``` java
double myDub = 6;
```

#### Char
- can only be one character long
- can be take from String using ```myString.charAt(int index)```

``` java
char myChar = 'c';
```

#### Boolean
- must be ```true``` or ```false```

``` java
boolean myBool = false;
```

### Non-Primitives:
> Make sure you import util to get the most functionality
> ```java
>  import java.util.*;
>  ```

#### String
``` java
String myString = "Hell0 Internet!";
```

#### Array List
Downsides (when compared to an Array)

- Slower
- Require more proccessing power

Benefits (when compared to an Array)

- Able to add element
- Able to delete element
- Not a fixed length

``` java
ArrayList<String> strList = new ArrayList<String>();
ArrayList<Integer> intList = new ArrayList<Integer>();
```
 **Methods**

- add()
- remove()
- get()
- set()
- length()
- clear()

**add(declared datatype)**
Adds on to the **end** of an ArrayList
```java
strList.add("hi");
```

**get(int index)**
```java
// name.get(int index)
strList.get(0);
// returns the first item in an Arraylist
String firstItem = strList.get(0);
```

**set(int index, declared datatype value)**
```java
strList.set(0, "bye");
```

**length()**
```java
strList.length();
// returns length of list
length = strList.length();
```

**remove(int index)**
```java
// name.remove(int index)
strList.remove(0);
// removes first item in ArrayList
```

**Clear()**
```java
strList.clear();
// removes all items from list
```


#### Array
Downsides (when compared to an Array)

- Unable to remove elements
- Unable to add elements
- Fixed length

Benefits (when compared to an Array)

- Faster
- Less proccessing power

``` java
/*
Creating an array
dataType[] name = new dataType[size]
*/
String[] myStrList = new String[5]; 
```
**Setting Values in an Array**
```java
/*
name[item index] = data
*/
myStrList[0] = "hi";
```
**Printing an Array**
```java
System.out.println(Array.toString(myStrList));

output 
> ["hi", "", "", "", ""]
```
**Getting the Size of an Array**
```java
int length = myStrList.length;
```

## External Input



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
```java
> hello Jaden
> hi Dom
```



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQzNDQ5MzY2NCw3NTIzMjc3NTUsMzMxMT
A5NzI3LDE3NzU3OTA3MjAsLTY5Njk1ODIyNV19
-->