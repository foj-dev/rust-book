## arithmetic operators

Used for basic mathematical calculations.

```rust
// sum: +
let sum = 1 + 1;
println!("Sum = {:?}", sum);

// subtraction: -
let sub = 2 - 2;
println!("Sub = {:?}", sub);

// multiplication: *
let mul = 3 * 3;
println!("Mul = {:?}", mul);

// division: /
let div = 4 / 4;
println!("Div = {:?}", div);

// remainder: %
let rem = 5 % 5;
println!("Rem = {:?}", rem);

// print
println!("10 + 10 = {:?}", 10 + 10);

// let
let calc: u8 = 2 + 5;
println!("2 + 5 = {:?}", calc);

// let + let
let num_01: u8 = 4;
let num_02: u8 = 5;
println!("num_01 + num_02 = {:?}", num_01 * num_02);

// let + let + let
let num_01: u16 = 9;
let num_02: u16 = 9;

let result: u16 = num_01 / num_02;
println!("Result = {:?}", result);
```
