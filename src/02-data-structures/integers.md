## u: unsigned integers

Whole numbers that can only be positive.

```rust
// u8 = 0 - 255
let number_u8: u8 = 255;
println!("{}", number_u8);

// u16 = 0 - 65.535
let number_u16: u16 = 255;
println!("{}", number_u16);

// u32 = 0 - 4.294.967.295
let number_u32: u32 = 255;
println!("{}", number_u32);

// u64 = 0 - 18.446.744.073.709.551.615
let number_u64: u64 = 255;
println!("{}", number_u64);

// u128 = 0 - ...
let number_u128: u128 = 255;
println!("{}", number_u128);
```

## i: signed integers

Whole numbers that can be either positive or negative.

```rust
// i8 = -128 - 127
let number_i8: i8 =  127;
println!("{}", number_i8);

// i16 = -32.768 - 32.767 (-32_768 até 32_767)
let number_i16: i16 =  127;
println!("{}", number_i16);

// i32 = -2.147.483.648 - 2.147.483.647
let number_i32: i32 =  127;
println!("{}", number_i32);

// i64 = -9.223.372.036.854.775.808 - 9.223.372.036.854.775.807
let number_i64: i64 =  127;
println!("{}", number_i64);

// i128 =  ... and ...
let number_i128: i128 =  127;
println!("{}", number_i128);
```
