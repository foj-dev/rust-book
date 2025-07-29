## Loop and break

For infinite repetitions, stopping only with break.

```rust
//
fn main() {
    loop {
        println!("Hello, world!");
        break;
    }
}

//
fn main () {
    //
    let mut count = 0;

    loop {
        prinlnt!("Cont: {}", count);
        count += 1;

        if count == 5 {
            break;
        }
    }

    println!("End of loop!");
}

// loop + breck + continue
fn main() {
    //
    let mut count = 0;
    let max_value = 4;

    loop {
        //
        count += 1;

        if count % 2 == 0 {
            println!("Count equal even! Value = {}", count);
            //continue;
        }
        if count > max_value {
            break;
        }

        println!("---")
    }
}

// + continue
fn main() {
    //
    let mut count = 0;
    let max_value = 4;

    loop {
        //
        count += 1;

        if count % 2 == 0 {
            println!("Count equal even! Value = {}", count);
            continue;
        }
        if count > max_value {
            break;
        }

        println!("---")
    }
}
```
