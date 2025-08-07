## logical

Relating to operations that combine or modify Boolean (true/false) values to produce a single Boolean result.

```rust
//
let t: bool = true;
let f: bool = false;

// &&
println!("{}", t && t); // true AND true = true
println!("{}", f && f); // false AND false = false
println!("{}", t && f); // true AND false = false
println!("{}", f && t); // false AND true = false

// ||
println!("{}", t || t); // true OR true = true
println!("{}", f || f); // false OR false = false
println!("{}", t || f); // true OR false = true
println!("{}", f || t); // false OR true = true

// !
println!("{}", !t); // true = false
println!("{}", !f); // false = true
```
