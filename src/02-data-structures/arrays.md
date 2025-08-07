## Array

A list of data items that are all of the same type and have a fixed size.

```rust
//
let list: [u8; 4] = [1, 2, 3 , 4];
println!("{:?}", list);

//
let list: [u8; 4] = [1, 2, 3 , 4];
println!("{:#?}", list);

//
let list = ['a', 'b', 'c' , 'd'];
println!("{:?}", list);

//
let list: [&str; 3];
list = ["ab", "cd", "de"];
println!("{:?}", list);

//
let [a, b, c]: [&str; 3] = ["xy", "yz", "zw"];
let list = [a, b, c];
println!("{:?}", list);

//
let list = ["12", "23", "34"];
let [a, b, c] = list;
println!("{:?} {:?} {:?}", a, b, c);
```

## Array and mut

```rust
//
let mut number: [i32; 5] = [10, 20, 30, 40, 50];
println!("{:?}", number);

number[0] = 100;
number[2] = 300;
println!("{:?}", number);

//
let mut names: [&str; 3] = ["Alice", "Bob", "Charlie"];
println!("{:?}", names);

names[0] = "Ane";
names[1] = "Bren";
println!("{:?}", names);

//
let mut scores: [u8; 4];
scores = [80, 40, 90, 73];

let [s1, s2, s3, s4] = scores;
println!("{}, {}, {} and {}", s1, s2, s3, s4);

scores[2] = 85;
println!("{:?}", scores);
println!("{}", s3);
```
