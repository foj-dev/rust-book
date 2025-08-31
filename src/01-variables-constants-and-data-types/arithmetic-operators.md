## Arithmetic Operators

Used for basic mathematical calculations.

- sum = +
- subtraction = -
- multiplication = *
- division = /
- remainder = %

```rust
fn main () {
    //
    println!("Sum: {}", 5 + 4);
    println!("Sub: {}", 5 - 2);
    println!("Mul: {}", 5 * 2);
    println!("Div: {}", 5.0 / 2.0);
    println!("Rem: {}", 5 % 2);
}
```

>💡
>
> Use the constant associated with the type:
> ```rust
> println!("u8: Min = {} | Max = {}", std::u8::MIN, std::u8::MAX);
> println!("Usize: Min = {} | Max = {}", std::usize::MIN, std::usize::MAX);
> ```

## Precede ordination

Some operators have priority over others

- ( )
- *, / and %
- + and -

```rust
println!("Result: {}", 5 + 3 * 2);
println!("Result: {}", (5 + 3) * 2);
```
