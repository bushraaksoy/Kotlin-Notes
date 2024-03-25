# Kotlin

Welcome to my digital kotlin notebook where i will be storing my kotlin information in one place.
This notebook was created for study purposes and as a source to come back to whenever i forget anything.

---

### Main function

```kotlin
fun main() {
  println("Hello world!")
}
```
>The main function is the entry point of the program


### Printing

```kotlin
println("Hello world!") // adds a new line after printing
print("Hellow world!") // doesn't add a new line after printing
```

### Declaring variables

> Kotlin uses the CamelCase naming convention

In kotlin, we have 3 ways of declaring variables. var, val, and const?

** var **

```kotlin
var name = "John"
```
This way of declaring variables is fine, but we know that kotlin was created to be type safe, so we can decale the variable with its type as so:

```kotlin
var name:String = "John"
```
> Kotlin is a statically typed programming language, so you will get an error immediately if you try to assign the wrong type to your variable

** val **

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

## Loops



### For loop



### While loop
