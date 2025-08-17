## &str

```rust
// &str
let create_str: &str = "Create text!";
println!("{}", create_str);

// without &str
let create_str = "Create new text!";
println!("{}", create_str);

// mut
let mut create_str = "Create text!";
println!("{}", create_str);

create_str = "Create new text!";
println!("{}", create_str);

// &str > string
let create_str = "Create text!";

// from and format!
let create_str_01: String = String::from(create_str);
let create_str_02: String = format!("{}", create_str);

// to
let create_str_03: String = create_str.to_string();
let create_str_04: String = create_str.to_owned();

//
println!("{}", create_str);
println!("{}", create_str_01);
println!("{}", create_str_02);
println!("{}", create_str_03);
println!("{}", create_str_04);
```
## Str Concatenation

```rust
let create_str_01 = "Create";
let create_str_02 = " text!";
println!("{}", create_str_01.to_string() + create_str_02); // or .to_owned()
```
