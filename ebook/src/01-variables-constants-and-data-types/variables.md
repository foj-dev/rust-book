## Variables

Variables are named spaces in memory that can hold a value.

```rust
let name = "Roberto";
println!("What is your name: {}", name);

let num = 24;
println!("What number did you choose? {}", num);
```

## Mutability

Once a variable's value is set, you cannot change it later. However, using "mut" after "let" makes the cr
eated variable mutable.

```rust
//
let mut name = "Alice";
println!("What is your name: {}", name);

name = "Roberto";
println!("What is your name: {}\n", name);

//
let mut num = 24;
println!("Which number did you choose? {}", num);

num = 12;
println!("Which number did you choose? {}", num);
```

## Constant

The constant is a variable with a fixed, immutable value, explicit type, and can be declared in any scope.

```rust
const POINTS: i32 = 3;
println!("{}", POINTS);
```

## Shadowing

You can declare a new variable with the same name as an existing one.

```rust
let food = "bread";
println!("{}", food);

let food = "milk";
println!("{}", food);

let food = "pizza";
println!("{}", food);
```

## Scope

Enclosing a block of code within curly braces {}, limits its functionality to that specific scope, while
still allowing access to previously defined data.

```rust
let x = 1;
println!("{}", x);

{
  let x = 2;
  println!("{}", x);
}

println!("{}", x);
```

>💡
>
> Use the constant associated with the type:
> ```rust
> println!("u8: Min = {} | Max = {}", std::u8::MIN, std::u8::MAX);
> println!("Usize: Min = {} | Max = {}", std::usize::MIN, std::usize::MAX);
> ```
