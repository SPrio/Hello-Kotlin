# Kotlin Bootcamp for Programmers
A course to getting started with kotlin.
## Hello Kotlin
```kotlin
fun printHello() {
    println("Hello World")
}

printHello()
```
## Introduction

### Operators
```kotlin
1+1
res1: kotlin.Int = 2

53-3
res2: kotlin.Int = 50

50/10
res3: kotlin.Int = 5

1/2
res4: kotlin.Int = 0

12/0
java.lang.ArithmeticException: / by zero

1/2.0
res6: kotlin.Double = 0.5

1.0/2.0
res7: kotlin.Double = 0.5

5*60
res8: kotlin.Int = 300

6*50
res9: kotlin.Int = 300

1.0/2
res10: kotlin.Double = 0.5

fish * 2
error: unresolved reference: fish
fish * 2
^

#if is defined
error: expecting an element
#if is defined
^
error: expecting a condition in parentheses '(...)'
#if is defined
    ^

//if fish is defined by you, it will multiply it two times

var fish =2

fish.plus(other = 2)
res15: kotlin.Int = 4

1.toLong()
res16: kotlin.Long = 1

var num = 1
num.toLong()
res17: kotlin.Long = 1

var num: Number = 1
num.toLong()
res18: kotlin.Long = 1

var boxed: Number = 1
boxed.toLong() #boxing in kotlin
incomplete code

var boxed: Number = 1
boxed.toLong() //boxing in kotlin
res20: kotlin.Long = 1

//in kotlin variables are two types:
//unchangable
val aq = 1

aq=2
error: val cannot be reassigned
aq=2
^

//changable
var aq = 1

aq=4

aq
res25: kotlin.Int = 4

//we cant change the type of a variable if the type has been determined

aq = "aasa"
error: type mismatch: inferred type is String but Int was expected
aq = "aasa"
     ^

val b: Byte = 1

val i: Int = b
error: type mismatch: inferred type is Byte but Int was expected
val i: Int = b
             ^

val i: Int = b.toInt
error: unresolved reference: b
val i: Int = b.toInt
             ^

val b: Byte = 1

val b: Byte = 1

val i: Int = b
error: type mismatch: inferred type is Byte but Int was expected
val i: Int = b
             ^

val i: Int = b.toInt()

//Null Pointer Handling
var rocks : Int =null
error: null can not be a value of a non-null type Int
var rocks : Int =null
                 ^

// we can allow a variable to be null
var marbles : Int? = null

var g = null

g!!
kotlin.KotlinNullPointerException

g
res37: kotlin.Nothing? = null

var? ?: 0
error: expecting property name or receiver type
var? ?: 0
   ^
error: property getter or setter expected
var? ?: 0
     ^

var ?: 0
error: expecting property name or receiver type
var ?: 0
    ^
error: type expected
var ?: 0
       ^
?. elvis operator which can act on a method if returned null then ?: 0 value will be zero
```
### Strings

