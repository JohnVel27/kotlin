# Kotlin Boolean Basics

In Kotlin, a Boolean is a data type that can only have two values: true or false. It's used for decision-making situations.

## Creating Boolean Variables

You can create a Boolean variable with or without specifying the type:

<pre>
  <code>
    fun main(){
      val isSummer:Boolean = true;
      val isWinter = false;

      println(isSummer);
      println(isWinter);
    }
  </code>
</pre>

## Nullable Boolean

Kotlin also has a nullable Boolean type Boolean?, which can hold true, false, or null.

# Kotlin Boolean Operators

Kotlin provides logical operators for Boolean variables:

&& (Logical AND): Returns true if both operands are true.
|| (Logical OR): Returns true if at least one operand is true.
! (Logical NOT): Reverses the Boolean value.

<pre>
  <code>
    fun main(){
      val x = true;
      val y:Boolean = false;

    println("x && y = ${x && y}");  //false
    println("x || y = ${x || y }"); //true
    println("!y = ${!y}"); //true 
    }
  </code>
</pre>

# Boolean Expressions

A Boolean expression returns true or false based on relational operators like >, <, >=, <=, ==, and !=.

## Examples:

<pre>
  <code>
    fun main() {
    val x = 40
    val y = 20

    println("x > y = ${x > y}")   // Outputs: true
    println("x < y = ${x < y}")   // Outputs: false
    println("x >= y = ${x >= y}") // Outputs: true
    println("x <= y = ${x <= y}") // Outputs: false
    println("x == y = ${x == y}") // Outputs: false
    println("x != y = ${x != y}") // Outputs: true
}

  </code>
</pre>

# Kotlin Boolean Functions

Kotlin provides and(), or(), not(), and xor() functions for Boolean operations. These functions do not short-circuit, meaning they always evaluate both operands.

## Examples:

<pre>
  <code>
    fun main() {
    val x = true
    val y = false
    val z = true

    println("x.and(y) = ${x.and(y)}") // Outputs: false
    println("x.or(y) = ${x.or(y)}")   // Outputs: true
    println("x.and(z) = ${x.and(z)}") // Outputs: true
}

  </code>
</pre>

Boolean to String Conversion

You can convert a Boolean value to its string representation using toString().

<pre>
  <code>
    fun main() {
    val x = true
    val z: String = x.toString()

    println("x.toString() = ${x.toString()}") // Outputs: true
    println("z = $z")                         // Outputs: true
}

  </code>
</pre>
