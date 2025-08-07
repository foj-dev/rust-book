## scope

Enclosing a block of code within curly braces {}, limits its functionality to that specific scope, while still allowing access to previously defined data.

```rust
// scope
let scop_00: i8 = 2;
let scop_01: i8 = 2;

{
    let result: i8 = scop_00 + scop_01;
    println!("{:?}", result)
}

println!("{:?}", scop_00 + scop_01);
// println!("{:?}", result);
```
