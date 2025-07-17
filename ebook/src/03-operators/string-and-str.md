## String and &str

- **String:** use String when you need owned text data. It's ideal for situations where you're creating text (e.g., from user input), concatenating strings, or when you need the text to have a lifetime controlled by you;

- **&str:** use &str when you need to borrow immutable text data. It's perfect for working with string literals (fixed text in the code), for taking a "slice" of an existing String, or when a function only needs to read the text without modifying it or taking ownership.

```rust
// &str
let num_01: &str = "1";
let num_02: &str = "2";
println!("num_01 + num_02 = {:?}", num_01.to_owned() + num_02);

// string
let num_03: String = String::from("1");
let num_04: String = String::from("2");
println!("num_03 + num_04 = {:?}", num_03 + &num_04);

// String + &str
let part_01: &str = "10";
let part_02: String = String::from("20");
println!("part_01 + part_02 = {}", part_01.to_owned() + &part_02);

// String + &str + let
let part_01: String = String::from("Hello, ");
let part_02: &str = "World";

let result: String =  part_01 + part_02;
println!("Reseult = {}", result);
```
