# Data Types

## u: unsigned integers

Whole numbers that can only be positive.

```rust
// u8 = 0 - 255
let number_u8: u8 = 255;
println!("{}", number_u8);
```

## i: signed integers

Whole numbers that can be either positive or negative.

```rust
// i8 = -128 - 127
let number_i8: i8 =  127;
println!("{}", number_i8);
```

## f: floating-point numbers

Numbers that have a decimal point.

```rust
// f32 = approx. -3.4e+38 a +3.4e+38
let number_f32: f32 =  179.76;
println!("{}", number_f32);
```

## char: character

Used to represent a single character and requires the use of single quotes (e.g., 'a').

```rust
let character: char = 'a';
println!("{}", character);
```

## bool: boolean

Represents only two types of values: true or false.

```rust
let checked: bool = true;
println!("The data was checked? {}", checked);
```
> ⚠️
>
> Rust offers additional data types: usize and isize. Refer to the documentation for details.
> These types automatically adjust to the system's architecture (32-bit or 64-bit).


## Tuples

Store multiple data items of different types in a fixed-size structure.

```rust
  let data_types: (u8, char, f32, i64) = (2, 'a', 5.4, 28);
  println!("{:#?}", data_types);
```

## Array

A list of data items that are all of the same type and have a fixed size.

```rust
  let list: [u8; 3] = [1, 5, 9];
  println!("{:#?}", list);
```
