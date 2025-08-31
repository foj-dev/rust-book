# Scope

Enclosing a block of code within curly braces {}, limits its functionality to that specific scope, while
still allowing access to previously defined data.

```rust
let x = 1;
println!("{}", x);

{
  let x = 2;
  println!("{}", x);
}

println!("{}", x);
```
