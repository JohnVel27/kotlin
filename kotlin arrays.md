# Kotlin Arrays Overview

Arrays in Kotlin are used to store multiple items of the same data type in a single variable. They offer a convenient way to handle collections of data without creating multiple variables.

## Creating Arrays

You can create an array in Kotlin using the arrayOf() function:

<pre>
  <code>
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange");
  </code>
</pre>

You can also specify the data type explicitly:

<pre>
  <code>
    val fruits = arrayOf<String>("Apple", "Mango", "Banana", "Orange")
  </code>
</pre>

To create an array of a given size filled with null elements, use arrayOfNulls():

<pre>
  <code>
    val emptyFruits = arrayOfNulls<String>(4)
  </code>
</pre>

# Primitive Type Arrays

Kotlin has built-in functions to create arrays of primitive data types:

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    println(fruits[0]) // Output: Apple
    println(fruits[3]) // Output: Orange
}

  </code>
</pre>

# Accessing and Modifying Array Elements

You can access array elements using the index number:

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    println(fruits[0]) // Output: Apple
    println(fruits[3]) // Output: Orange
}

  </code>
</pre>

You can also use get() and set() functions:

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    println(fruits.get(0)) // Output: Apple
    println(fruits.get(3)) // Output: Orange

    fruits.set(3, "Guava")
    println(fruits.get(3)) // Output: Guava
}

  </code>
</pre>

# Array Properties and Functions

1. <b>Array Length:</b> Use the size property or count() function to get the length of an array.

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    println("Size of fruits array: ${fruits.size}") // Output: 4
    println("Size of fruits array: ${fruits.count()}") // Output: 4
}

  </code>
</pre>

2. <b>Looping Through an Array:</b> Use a for loop to iterate over array elements.

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    for (fruit in fruits) {
        println(fruit)
    }
}

  </code>
</pre>

3. <b>Check if an Element Exists:</b> Use the in operator to check for the existence of an element.

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange")
    if ("Mango" in fruits) {
        println("Mango exists in fruits")
    } else {
        println("Mango does not exist in fruits")
    }
}

  </code>
</pre>

4. <b>Distinct Values from an Array:</b> Use the distinct() function to get unique values.

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange", "Apple")
    val distinctFruits = fruits.distinct()
    
    for (fruit in distinctFruits) {
        println(fruit)
    }
}

  </code>
</pre>

5. <b>Dropping Elements from an Array:</b> Use drop() and dropLast() functions to remove elements.

<pre>
  <code>
    fun main() {
    val fruits = arrayOf("Apple", "Mango", "Banana", "Orange", "Apple")
    val result = fruits.drop(2) // drops first two elements
    for (fruit in result) {
        println(fruit)
    }
}

  </code>
</pre>

6. Checking an Empty Array: Use isEmpty() function to check if an array is empty

<pre>
  <code>
    fun main() {
      val fruits = arrayOf<String>()
      println("Array is empty: ${fruits.isEmpty()}") // Output: Array is empty: true
}

  </code>
</pre>

