# Javascript
## for, while, do...while() Loop

1. Write a loop which prompts for a number greater than 100. If the visitor enters another number – ask him to input again.
The loop must ask for a number until either the visitor enters a number greater than 100 or cancels the input/enters an empty line.
Here we can assume that the visitor only inputs numbers. There’s no need to implement a special handling for a non-numeric input in this task.
```javascript

let x = prompt("please enter a number",'');
let inputValue = +x;

while ( (inputValue <= 100) && (inputValue != 0) ) {
    let y = prompt("please enter a number",'');
    let inputValue = +y;
}

```
