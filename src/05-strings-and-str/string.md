## Strings

Sequence of UTF-8 characters that can form a word or a phrase, including letters, numbers, symbols, or any other type of special character.

Think of your memory as a cabinet, a variable as a drawer, and a string as a piece of paper.

When you create a "string" variable, you use the entire drawer. But when you create a "&str" variable, you use a piece of paper to write down the information and then put it inside the drawer.

## String

```rust
// new()
let create_string: String = String::new();
println!("{}", create_string);

// from()
let create_string: String = String::from("Create text!");
println!("{}", create_string);

// to_string()
let create_string: String = "Create text!".to_string();
println!("{}", create_string);

// mut
let mut create_string: String = String::from("Create text!");
println!("{}", create_string);
create_string = "Create new text!".to_string();
println!("{}", create_string);
```

## String concatenation

```rust
// format!
let create_string_01: String = String::from("1");
let create_string_02: String = String::from("2");
let create_string: String = format!("{}{}", create_string_01, create_string_02);
println!("{}", create_string);

//
let create_string_01: String = String::from("1");
let create_string_02: String = String::from("2");
println!("{}{}", create_string_01, create_string_02);

// push
let mut create_string: String = String::new();
create_string.push_str("Create");
create_string.push_str(" String");
println!("{}", create_string);

// concatenation -> +
let create_string_01: String = String::from("1");
let create_string_02: String = String::from("2");
let create_string: String = create_string_01 + &create_string_02;
println!("{}", create_string);

// ERROR
println!("{}", create_string_01);
// Value of create_string_01 moved for create_string
// create_string_01 == null
// Velue of create_string_02 referenced in create_string = 01 + &02
// Consider cloning the value if the performance cost is acceptable: `.clone()`
// let create_string: String = create_string_01.clone() + &create_string_02;
```
