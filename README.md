# FibonacciWithGetOpts
<b>Background</b></br>
The Fibonacci sequence is a set of integers that start with either a zero or a one. The sequence follows the rule that each number is equal to the sum of the preceding two numbers.
This Fibonacci sequence is a set of integers, where the script is called to set the first two seeds of the sequence to either 0 or 1. The sequence then follows the rule that each following integer is the sum of the preceding two integers. The Fibonacci sequence can be defined by the following equation:</br>
F<sub>n</sub> = F<sub>n-1</sub> + F<sub>n-2</sub>

<b>Details</b></br>
This script is called the required arguments of <i>-a</i> and <i>-b</i> to initalize the first two seeds in the sequence. However, the arguments must either be 0 or 1, and both cannot be 0 <i>(valid arguments are: {0,1}, {1,0}, {1,1})</i>. Optional arguments are <i>-r</i> to set amount of times the loop is executed, and <i>-s</i> to modify the sleep time. After the validity of the arguments are checked, the program either terminates or contines to the loop. The loop sleeps, updates the counter, calculates the next number in the Fibonacci sequence. The loop then prints the counter and the numbers associated to F<sub>n-1</sub> + F<sub>n-2</sub> = F<sub>n</sub>. Lastly, the loop overwrited F<sub>n-2</sub> to F<sub>n-1</sub>, F<sub>n-1</sub> to F<sub>n</sub>, and potentially the conditional variable to the loop.

<table>
  <tr>
    <th>Argument</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>-a</td>
    <td>Sets the first seed value of the fibonacci sequence. Must be either 0 or 1, and cannot be 0 if the second seed is also 0.</td>
  </tr>
  <tr>
    <td>-b</td>
    <td>Sets the second seed value of the fibonacci sequence. Must be either 0 or 1, and cannot be 0 if the first seed is also 0.</td>
  </tr>
  <tr>
    <td>-s</td>
    <td>Modifies the sleep time. Default value of 1.</td>
  </tr>
  <tr>
    <td>-r</td>
    <td>Sets a finite amount of times to execute the loop. By default, will run an infinitely</td>
  </tr>
</table>
