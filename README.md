# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (actualAge){
  if (actualAge == 1){
    return {
      humanYears: actualAge,
      catYears: 15,
      dogYears: 15,
    }
  }

  if (actualAge == 2){
    return {
      humanYears: actualAge,
      catYears: 24,
      dogYears: 24,
    }
  }

  return {
    humanYears: actualAge,
    catYears: (actualAge - 2) * 4 + 24,
    dogYears: (actualAge - 2) * 5 + 24,
  }
}
```

| Input | Output  |
| ----- | ------  |
| 1     | { humanYears: 1, catYears: 15, dogYears: 15 }  | 
| 3     |3,28,29  | 
| 5     |5,36,39  | 
| 10    |10,56,64 | 
| 20    |20,96,114|  

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Takes the input actualAge and gives you an output of humanYears as well as converting to catYears and dogYears.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
