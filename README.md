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

#### If-Else statements

Standard if-else statements in a function

```kotlin
var name = "David"
val greeting: String? = null

fun main(){
	if(greeting != null){
		println(greeting)
	}
	else{
		println("byebye ")
	}

	println(name)
}
// answer: byebye David
```

if- else statements used in a variable to determine the expression

```kotlin
val name = "David"
var greeting: String? = null

fun main(){
	val hello = if(greeting != null) greeting else "hello"
	println(hello)
}

```

#### When() statements

It is used like a switch case statement in Kotlin basis

```kotlin
var name = "david"
var greeting = ""
fun main() {
	when(greeting){
		"" -> println("hello") // if condition matches the string
		else -> println("byebye") // default condition use else
	}
}
```

The when() statement similar to the if-else, could be used in a variable to determine its value

```kotlin
val name = "David"
var greeting: String? = null

fun main(){
	val hello = when(greeting){
		null -> "hello"
		else -> greeting
	}
	println(hello)
}
```
