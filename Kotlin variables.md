# Kotlin Variables

Variables are containers for storing data values.

To create a variable, use <b>var or val</b>, and assign a value to it with the equal sign (=):

## Syntax

<pre>
  <code>
    var variablename1 = value
    val variablename2 = value
  </code>
</pre>

# Mutable vs Immutable 

<b>Mutable (var)</b>: You can change the value after it’s been set.

<pre>
  <code>
    var age = 30;
    age = 32 // This is allowed
    println(age) // display 32
  </code>
</pre>

<b>Immutable (val):</b> Once set, you cannot change the value.

<pre>
  <code>
    val age = 30
    age = 22 // error because val cannot be reassigned
    println(age) // error
  </code>
</pre>

# Variable Type

Kotlin is smart and can often figure out the type of variable based on the value you assign to it. This is called type inference.

## Example: 

<pre>
  <code>
    fun main(){
      var name = "John Vel"; // Kotlin infers that this is a string
      val birthyear = 2000;  // kotlin infers that this is a Int

      println(name);   // Print John Vel
      println(birthyear);  // Print 2000
    }
  </code>
</pre>

# Specifying the Type

If you want, you can specify the type explicitly:

<pre>
  <code>
    fun main(){
      val name:String = "John Vel"
      var age:Int = 52;

      println(name);
      println(age);
    }
  </code>
</pre>

# Declaring Without Initial Value

You can declare a variable without assigning it a value right away, but you must specify the type. This is useful when you want to assign the value later.

<pre>
  <code>
    var name:String;
    name = "John Vel"
    println(name); //print John Vel
  </code>
</pre>

