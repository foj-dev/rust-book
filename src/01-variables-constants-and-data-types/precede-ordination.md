# Precede ordination

Some operators have priority over others:

`( ) > *, /,  % > + and -`

```rust
//
println!("5 + 3 * 2 = {}", 5 + 3 * 2);
```

```rust
//
println!("(5 + 3) * 2 = {}", (5 + 3) * 2);
```


<br>
Use the constant associated with the type:

```rust
println!("u8: Min = {} | Max = {}", std::u8::MIN, std::u8::MAX);
```
  
```rust
println!("Usize: Min = {} | Max = {}", std::usize::MIN, std::usize::MAX);
```
