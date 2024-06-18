# Kotlin Data types

In Kotlin, variables can store different types of data. Here’s a basic overview of the main data types and how to use them.

## 1. Integer Types: Whole numbers (no decimals)

<ul>
  <li><b>Byte:</b> -128 to 127</li>
  <li><b>Short:</b> -32,768 to 32,767</li>
  <li><b>Int:</b> -2,147,483,648 to 2,147,483,647</li>
  <li><b>Long:</b> Very large numbers, up to ±9,223,372,036,854,775,807 (ends with 'L')</li>
</ul>

## 2. Floating Point Types: Numbers with decimals

<ul>
  <li><b>Float:</b> Smaller precision (6-7 decimal digits, ends with 'F')</li>
  <li><b>Double:</b> Higher precision (15 decimal digits)</li>
</ul>

## 3. Other Basic Types

<ul>
  <li><b>Char:</b> A single character, like 'A' or 'B'</li>
  <li>Boolean: <b>true</b> or <b>false</b></li>
  <li><b>String:</b> A sequence of characters, like "Hello"</li>
</ul>

# Examples

<pre>
  <code>
    val num = 5; //Int
    val mydouble = 5.22; //Double
    val name = "John Vel"; // String
    val myletter = 'C'; //Char
    val myboolean = true; // Boolean
  </code>
</pre>

## You can also specify the type explicitly:

<pre>
  <code>
    val mynum:Int = 5;
    val mydouble:Double = 5.22;
    val name:String = "John Vel";
    val myletter:Char = 'C';
    val myboolean:Boolean = true;
  </code>
</pre>

# Integer Types

## Byte: Small numbers

<pre>
  <code>
    val num:Byte = 100;
    println(num);
  </code>
</pre>

## Short: Larger than Byte

<pre>
  <code>
    val num:Short = 5000;
    println(num);
  </code>
</pre>

## Int: Default for whole numbers

<pre>
  <code>
    val num:Int = 100000
    println(num);
  </code>
</pre>

## Long: Very large numbers

<pre>
  <code>
    val num:Long = 10000000000L;
    println(num);
  </code>
</pre>

# Floating Point Types

## Float: Numbers with decimals, less precise

<pre>
  <code>
    val num:Float = 5.23F
    println(num);
  </code>
</pre>

## Double: Numbers with decimals, more precise

<pre>
  <code>
    val num:Double = 2.35;
    println(num);
  </code>
</pre>

# Common Types

## Boolean: true or false

<pre>
  <code>
    val myboolean:Boolean = true;
    println(myboolean);
  </code>
</pre>

## Char: A single character

<pre>
  <code>
    val mychar:Char = 'C';
    println(mychar);
  </code>
</pre>

## String: A sequence of characters

<pre>
  <code>
    val myname:String = "John Vel";
    println(myname);
  </code>
</pre>

# Type Conversion

Sometimes, you need to convert one type to another:

<pre>
  <code>
    val x:Int = 532;
    val y:Long = x.toLong();

    println(y);
  </code>
</pre>

To convert a numeric data type to another type, you must use one of the following functions: toByte(), toShort(), toInt(), toLong(), toFloat(), toDouble() or toChar():
