## For

For iterating over collections or a defined number of times.

```rust
//
for element in collection {

}

// i
// 0 - 4
for i in 0..5 {
    println!("{}", i);
}

// 0 - 5
for i in 0..=5 {
    println!("{}", i);
}

// 4 - 0
for i in (0..5).rev() {
    println!("{}", i);
}

// 5 - 0
for i in (0..=5).rev() {
    println!("{}", i);
}

//
fn main() {
    //
    let name: &str = "Rust";
    for i in name.chars() {
        println!("{}", i);
    }
}

//
let arr = ["apple", "banana", "orange", "guava"];
for i in arr {
    println!("{:#?}", i)
}

//
let arr: [[i32; 3]; 3] = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
];

for i in arr {
    for j in i {
        print!("{}", j);
    }
    println!();
}
```
