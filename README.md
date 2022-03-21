# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

*Summary*
1) Function takes an array of numbers and first sets `sum = 0`. 
2) The function takes the 1st number in the array and adds it to the sum.
3) The function then iterates and takes the next number in the array and adds it to the previous sum.
4) Finally, the function takes the sum of all the numbers and divides it by the array's length and returns the quotient. 

```js
function (numbers){
  let sum = 0

  for (let number of numbers){
    sum += number
  }

  return +(sum / numbers.length)
}
```

Inputs and outputs should be valid JavaScript values!

|     Input     | Output |
| ------------- | ------ |
| [1, 2, 3, 4]  |  2.5   | 
| [3, 5, 7]     |    5   | 
| [0, 100]      |   50   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program gives you the mean of the array of numbers entered.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
