## While

For repetitions as long as a condition is true.

```rust
// while
fn main() {
      //
      let mut count = 0;

      while count <= 5 {
          println!("Count = {}", count);
          count += 1;
      }
  }

// while + continue
fn main() {
    //
    let mut count = 0;
    let max_value = 4;

    while count <= max_value {
        //
        count += 1;

        if count % 2 == 0 {
            println!("Count is even! Value = {}", count);
            continue;
        }
        println!("---");
    }
}
```
