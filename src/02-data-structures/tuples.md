## tuples

Store multiple data items of different types in a fixed-size structure.

```rust
let data_types = ("a", 1);
println!("{:?}", data_types);

//
let data_types = ("b", 2);
println!("{:#?}", data_types);

//
let data_types : (char, u8);
data_types = ('c', 3);
println!("{:?}", data_types);

//
let (name, num) : (&str, i8);
(name, num) = ("Alice", 4);
println!("{} and {}", name, num);

//
let (letter, yes) : (char, bool) = ('d', true);
let test =  (letter, yes);
println!("{:?}", test);

//
let person = ("Gregor", 64, 1.82);
let (x, y, z) = person;
println!("My name is {x}, i'm {y} years old and my height is {z}");
```

## tuples and mut

```rust
//
let mut person = ("Roberto", 90, 1.98);
println!("{:#?}", person);

person.0 = "Moana";
person.1 = 58;
person.2 = 1.62;
println!("{:#?}", person);

//
let mut person = ("Helena", 67, 2.10);
println!("{:?}", person);

person.0 = "Arle";
person.1 = 64;
person.2 = 1.71;
println!("{:?}", person);

//
let (name, weight, height) = person;
println!("Name: {} \nWeight: {} \nHeight: {}", name, weight, height);
```
