# Kotlin

Welcome to my digital kotlin notebook where i will be storing my kotlin information in one place.
This notebook was created for study purposes and as a source to come back to whenever i forget anything.

---

## Main function

```kotlin
fun main() {
  println("Hello world!")
}
```
>The main function is the entry point of the program


## Printing

```kotlin
println("Hello world!") // adds a new line after printing
print("Hellow world!") // doesn't add a new line after printing
```

## Declaring variables

> Kotlin uses the CamelCase naming convention

In kotlin, we have 3 ways of declaring variables. var, val, and const?

### ***var:***

```kotlin
var name:String = "John"
```

This way of declaring variables is fine, but we don't need to always explicitly state the type of the variable, as kotlin has type inference. So we can just declare it at so:

```kotlin
var name = "John"
```

> Kotlin is a statically typed programming language, so you will get an error immediately if you try to assign the wrong type to your variable

### ***val:***

Declaring variables using val means that they cannot be changed later

```kotlin
var name:String = "John"
name = "Alex"
```

The code above is acceptable using var, but it will raise an error if you try to reassign a variable declared using val.

- third type of variable declaration:

We can refer to variables in our string using $ as follows

```kotlin
var name:String = "John"
println("Hello $name!")
```

# Kotlin Data Types

In Kotlin, data types are categorized into different groups:

## Numbers

Numbers include both integer and floating-point types.

### Integer Types

Integer types store whole numbers without decimals.

- **Byte**: Whole numbers from -128 to 127.
- **Short**: Whole numbers from -32768 to 32767.
- **Int**: Whole numbers from -2147483648 to 2147483647.
- **Long**: Whole numbers from -9223372036854775808 to 9223372036854775807.

### Floating-Point Types

Floating-point types represent numbers with a fractional part.

- **Float**: Decimal values with a precision of about six or seven decimal digits.
- **Double**: Decimal values with a precision of about 15 digits.

  others include characters, boolean, strings and arrays
  `Char` `Boolean ` `String` `Array`

## For loop



## While loop
