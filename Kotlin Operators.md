# Kotlin Operators: Simple Guide

Operators in Kotlin are symbols that perform operations on variables and values.

Basic Example

<pre>
  <code>
    fun main(){
      val x = 200 + 500;
      println(x);
    }
  </code>
</pre>

## Types of Operators

Kotlin operators are grouped into several categories:

1. Arithmetic Operators
2. Assignment Operators
3. Comparison Operators
4. Logical Operators

## 1. Arithmetic Operators

Used for basic mathematical operations.

<table>
  <tr>
    <th>Operators</th>
    <th>Name</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>+</td>
    <td>Addition</td>
    <td>Add two values</td>
    <td>x + y</td>
  </tr>
  <tr>
    <td>-</td>
    <td>Subtraction</td>
    <td>Subtracts one value from another</td>
    <td>x - y</td>
  </tr>
  <tr>
    <td>*</td>
    <td>Multiplication</td>
    <td>Multiplies two values</td>
    <td>x * y</td>
  </tr>
  <tr>
    <td>/</td>
    <td>Division</td>
    <td>Divides one value by another</td>
    <td>x / y</td>
  </tr>
   <tr>
    <td>%</td>
    <td>Modulus</td>
    <td>Remainder of division	</td>
    <td>x % y</td>
  </tr>
   <tr>
    <td>++</td>
    <td>Increment</td>
    <td>Increases value by 1</td>
    <td>x++ or ++x</td>
  </tr>
   <tr>
    <td>--</td>
    <td>Decrement</td>
    <td>Decreases value by 1</td>
    <td>x-- or --x</td>
  </tr>
</table>

<pre>
  <code>
var sum1 = 100 + 50       // 150
var sum2 = sum1 + 250     // 400
var sum3 = sum2 + sum2    // 800

  </code>
</pre>

## 2. Assignment Operators

Used to assign values to variables.

<table>
  <tr>
    <th>Operator</th>
    <th>Example</th>
    <th>Same As</th>
  </tr>
  <tr>
    <td>=</td>
    <td>x = 5</td>
    <td>x = 5</td>
  </tr>
   <tr>
    <td>+=</td>
    <td>x += 3</td>
    <td>x = x + 3</td>
  </tr>
  <tr>
    <td>-=</td>
    <td>x -= 3</td>
    <td>x = x - 3</td>
  </tr>
  <tr>
    <td>*=</td>
    <td>x*= 3</td>
    <td>x = x * 3</td>
  </tr>
  <tr>
    <td>/=</td>
    <td>x/= 3</td>
    <td>x = x / 3</td>
  </tr>
  <tr>
    <td>%=</td>
    <td>x %= 3</td>
    <td>x = x % 3</td>
  </tr>
</table>

### Example

<pre>
  <code>
var x = 10
x += 5   // x is now 15

  </code>
</pre>

# 3. Comparison Operators

Used to compare two values and return a Boolean (true or false).

<table>
  <tr>
    <th>Operators</th>
    <th>Name</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>==</td>
    <td>Equal to</td>
    <td>x == y</td>
  </tr>
  <td>!=</td>
    <td>Not equal to</td>
    <td>x != y</td>
  </tr>
  <tr>
    <td>&gt;</td>
    <td>Greater than</td>
    <td>x &gt; y</td>
  </tr>
  <tr>
    <td>&lt;</td>
    <td>Less than</td>
    <td>x &lt; y</td>
  </tr>
  <tr>
    <td>&gt;=</td>
    <td>Greater than or equal to</td>
    <td>x &gt;= y</td>
  </tr>
  <tr>
    <td>&lt;=</td>
    <td>Less than or equal to</td>
    <td>x &lt;= y</td>
  </tr>
</table>

# 4. Logical Operators

<table>
  <tr>
    <th>Operators</th>
    <th>Name</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
    <tr>
    <td>&amp;&amp;</td>
    <td>Logical and</td>
    <td>Returns true if both statements are true</td>
    <td>x &lt; 5 &amp;&amp; x &lt; 10</td>
  </tr>
  <tr>
    <td>||</td>
    <td>Logical or</td>
    <td>Returns true if either statement is true</td>
    <td>x &lt; 5 || x &lt; 4</td>
  </tr>
  <tr>
    <td>!</td>
    <td>Logical not</td>
    <td>Reverses the logical state of a statement</td>
    <td>!true</td>
  </tr>
</table>

This table summarizes the key Kotlin operators categorized by their types (arithmetic, assignment, comparison, logical). It should help you understand and review these operators effectively. Adjust the formatting as needed for your specific use case!


