There are four main data types we use in robotics: String, int, double, and boolean.

## Strings
Earlier, you were introduced to the `String` type. Here are a few more things you can do with Strings.

String concatenation with the `+` sign:
```java
String hello = "Hello" + " world"; // results in "Hello world"
```

Inserting a new line with `\n`:
```java
String hello = "Hello\nworld"; // results in "Hello
//                                            world"
```

## Integers
Integer types are pretty intuitive. Integer variables are created with the keyword `int`.
```java
int four = 4;
```
You can perform basic arithmetic operations with integers:
```java
int five = 3 + 2;         // addition
int three = five - 2;     // subtraction
int nine = three * three; // multiplication
int one = 9 / nine;       // division
```

!!! warning
    When the result of a division between two ints is a fraction, the output will always round down.
    ```java
    int something = 9 / 2; // will result in 4
    ```

## Doubles
But what if you wanted to use more than just whole numbers? For that purpose, we have the `double` data type. You can use it the same way you use ints.
```java
double six = 6.0;
double threeHalves = six / 4;
double two = threeHalves + 0.5;
// etc
```

## Booleans
Boolean is the most basic type in Java. A boolean variable can either be `true` or `false`.
```java
boolean yes = true;
boolean no = false;
```
Even though they're super simple, we actually use booleans a lot. For example, when comparing the values of two things, a boolean is returned.

Here are a few comparison operators that we use:
```java
2 == 2; // equality
3 != 2; // inequality
2 < 3;  // less than
3 > 2;  // greater than
2 <= 2; // less than or equal
3 >= 3; // greater than or equal
```
These comparison operators can be used to compare ints, doubles, and booleans, but not Strings. We'll talk about why in the future.