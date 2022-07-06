# Unary Operator

* The prefix increment operator adds one to a value. The value is changed before the statement is evaluted.
* The postfix increment operator adds one to a value. The value is changed after the statement is evaluted.

## Example
```
let weight = 90;
newWeight = ++weight;

console.log(weight); // 91
console.log(newWeight); //91
```
```
let weight = 90;
newWeight = weight++;

console.log(weight); // 91
console.log(newWeight); //90
```
# Logical assignment operator
## Example
* `x||=y` equivalent with `x||(x=y)`
* `x??=y` equivalent with `x??(x=y)`
# Exponentiation operator
## Example
`2**3=8`

# Comma operator
* A comma operator takes two expressions and evaluates them from left to right, and returns the value of the right expression.
* Use the comma operator (,) inside a for loop to update multiple variables once.
* Use two statements rather than the comma operator elsewhere to make the code more explicit and easier to understand.
## Example
```
let x=10;
let y=(x++,x+1);
console.log(x,y);// 11 12
```