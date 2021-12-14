# KOTLIN Development Basics

The basics for Kotlin development

## Table of Content

1. Project Setup
2. Kotlin Basics
3. Advanced Features

### Project Setup

#### Requirements

- An IDE like IntelliJ IDEA (Recommended) or Eclipse
- Basic programming fundamentals

#### Setting it up

- Click on `New Project`
- Press on the `Kotlin` tab
- Choose the JVM libraries you want to build kotlin based on.

### Syntaxes

- `fun` keyword to declare a function
- Uses `println` to print or debug a statement
- Kotlin automatically recognises `main` as the executable function

```kotlin
fun main(){
    println("Hello Kotlin")
}
```

#### Variable and Datatype declaration

```kotlin
// Mutable variable, these variables can be reassigned
var name: String = "David"

// Immutable variable, assigned once only variable | Local Read-Only variable
val name2: String = "David"

// Type referencing, implicit type cast
var name = "David"

// Kotlin default data types are non-nullable
// To make it nullable, we need a null safe operator
val name3: String? = null
```
