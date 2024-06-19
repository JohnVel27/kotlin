# Kotlin Strings Overview

Kotlin strings are used to store text, and they can be defined using double quotes (" ") for escaped strings or triple quotes (""" """) for raw strings.

## Types of Strings

1. <b>Escaped String:</b> Contains escape characters like \n, \t, etc.

2. <b>Raw String:</b> Can contain multiple lines of text without escape characters.

## Examples:

<pre>
  <code>
    fun main() {
    val escapedString: String = "I am an escaped String!\n"
    val rawString: String = """
        This is a raw string.
        It spans multiple lines
        without any escape sequences.
    """

    print(escapedString)
    println(rawString)
}
  </code>
</pre>

## String Variables

You don't need to specify the type explicitly; Kotlin infers it from the value.

<pre>
  <code>
    fun main() {
    val name: String = "Zara Ali"
    println(name)
}

  </code>
</pre>

## String Templates

String templates allow for embedding variables and expressions inside strings using the $ sign.

<pre>
  <code>
    fun main() {
    val name: String = "Zara Ali"
    println("Name - $name")
    println("Name length - ${name.length}")
}

  </code>
</pre>

# String Operations

1. <b>Accessing Characters:</b> Strings are treated as arrays of characters.

<pre>
  <code>
    fun main() {
    val name: String = "Zara Ali"
    println(name[3]) // Outputs: 'a'
    println(name[5]) // Outputs: 'A'
}

  </code>
</pre>

2. <b>String Length:</b> Using length property or count() function.

<pre>
  <code>
    fun main() {
      val name: String = "Zara Ali"
    println("Length: ${name.length}")
    println("Length: ${name.count()}")
}

  </code>
</pre>

3. <b>Last Index:</b> Using lastIndex property.

<pre>
  <code>
    fun main() {
      val name: String = "Zara Ali"
      println("Last index: ${name.lastIndex}")
}

  </code>
</pre>

4. <b>Changing Case:</b> Using toUpperCase() and toLowerCase() functions.

<pre>
  <code>
    fun main() {
    val name: String = "Zara Ali"
      println("Upper case: ${name.toUpperCase()}")
      println("Lower case: ${name.toLowerCase()}")
}

  </code>
</pre>

5. <b>Concatenation:</b> Using + operator or plus() function.

<pre>
  <code>
    fun main() {
    
    val firstName: String = "Zara"
    val lastName: String = "Ali"
      
      println("Full Name: $firstName $lastName")
      println("Full Name: ${firstName.plus(lastName)}")
}

  </code>
</pre>

6. <b>Trimming Characters:</b> Using drop() and dropLast() functions.

<pre>
  <code>
    fun main() {
      val name: String = "Zara Ali"
        println("Drop first 2 chars: ${name.drop(2)}")
        println("Drop last 2 chars: ${name.dropLast(2)}")
}

  </code>
</pre>

7. <b>Quotes Inside Strings:</b> Using single quotes inside double-quoted strings.

<pre>
  <code>
    fun main() {
      val str1: String = "That's it"
      val str2: String = "It's OK"
    println("str1: $str1")
    println("str2: $str2")
}

  </code>
</pre>

8. <b>Finding a String:</b> Using indexOf() function.

<pre>
  <code>
    fun main() {
    val str: String = "Meditation and Yoga are synonymous with India"
      println("Index of Yoga: ${str.indexOf("Yoga")}")
}

  </code>
</pre>

9. <b>Comparing Strings:</b> Using compareTo() function.

<pre>
  <code>
    fun main() {
      val str1: String = "Apple"
      val str2: String = "Apple"
    println(str1.compareTo(str2)) // Outputs: 0
}

  </code>
</pre>

10. <b>getOrNull() Function:</b> Returns a character at the given index or null if out of bounds.

<pre>
  <code>
    fun main() {
    val name: String = "Zara"
      println(name.getOrNull(0)) // Outputs: 'Z'
      println(name.getOrNull(2)) // Outputs: 'r'
      println(name.getOrNull(100)) // Outputs: null
}

  </code>
</pre>

11. <b>toString() Function:</b> Converts any object to its string representation.

<pre>
  <code>
    fun main() {
    val name: String = "Zara Ali"
    println(name.toString()) // Outputs: Zara Ali
}
  </code>
</pre>


