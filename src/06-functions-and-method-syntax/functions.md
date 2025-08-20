## Functions and Method Syntax

- functions

```rust
fn basic() {
    println!("Hello, world!");
}

fn main() {
    // basic
    basic();
}
```

- parameters

```rust
fn parameter(x: i8) {
    println!("x = {}", x);
}

fn main() {
    // parameter
    parameter(1);
}
```

```rust
fn parameter_00(x: i8, y: i8) {
    // 00
    println!("{} + {} = {}", x, y, x + y);
}

fn main() {
    // 00
    parameter_00(1, 2);
}
```
