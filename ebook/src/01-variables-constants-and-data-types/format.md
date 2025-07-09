## Format

The format! macro in Rust is used to improve data output formatting by using curly braces "{}" as placeho
lders that will be filled with the information.

```rust
//
let name = "Marcos";
println!("I'm, {}!", name);

//
let name = "Alice";
let years = 30;
println!("Hi, I'm {}, {} years old", name, years);
```

> ⚠️
>
>**For more information, see the [Rust `std::fmt` documentation](https://doc.rust-lang.org/std/fmt/).**
