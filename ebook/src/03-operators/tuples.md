## Tuples

Store multiple data items of different types in a fixed-size structure.

```rust
// tuple
let tup: (u8, u8) = (1, 4);
println!("Tup 0 + Tup 1 = {:?}", tup.0 + tup.1);

// tuple let
let tup: (u8, u8);
tup = (3, 8);
println!("Tup 0 + Tup 1 = {:?}", tup.0 + tup.1);

// tuple + tuple
let tup: ((u8, u8),(u8, u8)) = ((2, 4),(6, 16));
println!("Tup.0.0 + Tup.0.1 = {:?}", tup.0.0 + tup.0.1);
println!("Tup.1.0 + Tup.1.1 = {:?}", tup.1.0 + tup.1.1);
println!("Tup.0.0 + Tup.1.0 = {:?}", tup.0.0 + tup.1.0);
println!("Tup.0.1 + tup.1.1 = {:?}", tup.0.1 + tup.1.1);

// tuple + let + let
let tup_01: (u8, u8) = (1, 4);
let tup_02: (u8, u8) = (14, 9);

let result = tup_01.0 + tup_01.1 + tup_02.0 + tup_02.1;
println!("Result = {:?}", result);
```
