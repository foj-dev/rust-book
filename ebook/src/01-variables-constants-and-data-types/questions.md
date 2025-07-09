# Questions - Variables Constants and Data Types

---
01 - How would you write a single-line comment in rust?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=fa5635f01f8529974ad29fcad714a6ff)

  <details>
  <summary>Answers</summary>
  
  ```rust
  fn main () {
      // single-line comment
  }
  ```
  </details>

02 - What is the syntax for a block comments in rust?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9eef6021ef3fd0cda684697b68fb29a3)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main () {
      /* block comments */
  }
  ```
  </details>

03 - Which macro would you use to print text on the same line, whihout adding a newline at the end?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=ffa6c6172b2088f36a0bb092c1d69afd)

  <details>
    <summary>Answers</summary>

  ```rust
  fn main() {
      //
      print!("Print: whihout adding a newline at the end!");
  }
  ```
  </details>

04 - Which macro would you use to print text and automatically add a newline at the end?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=bbf1b87290e47b4d63762d07be948e7e)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("Print: add newline at the end!");
  }
  ```
  </details>

05 - How do you insert an explicit newline within a string that is being printed with println!?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=c18cc1eb489ca7399c8d797f6af9e6a5)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("First\nSecond!");
  }
  ```
  </details>

06 - What would be printed by the following code?

  ```rust
  fn main () {
      //
      println!("First line\\nSecond line");
  }
  ```

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=f9933474d4f54c4c5c50167fcb9ffa06)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      println!("First line\\nSecond line");
  }
  ```
  </details>


07 - What will be the output of the following code?

  ```rust
  let name = "Ana";
  let age = 30;
  let text = format!("Hello, {}! You are {} years old.", name, age);
  println!("{}", text);
  ```

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=66b53067454a20b107933a77820f0c42)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      let name = "Ana";
      let age = 30;
      let text = format!("Hello, {}! You are {} years old.", name, age);
      println!("{}", text);
  }
  ```
  </details>


08 - How would you use the format! macro to create the string "The value is: 42" from the number 42?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=1ed69cf700df24418c0c55c5cde8c4f4)

 <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let number = 42;
      let formated = format!("The value is: {}", number);
      println!("{}", formated);
  }
  ```
 </details>


09 - How can you format the number 7 so that it is displayer as "0007" using format!?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=0df831110a2b60915f120a25b1399c06)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let number: u8 = 7;
      println!("{:04}", number);

      //
      let formated = format!("{:04}", number);
      println!("{}", formated);
  }
  ```
  </details>


10 - What is the utily of "{:?}" in the format! macro? Give an example of when you would use it.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=670868879cb54931c2ff8bf98de968a9)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      let number: u8 = 1;
      println!("{:?}", number);
  }
  ```
  </details>


11 - What does the specifier "{:#?}" do differently from "{:?}" when formatting a tuple or struct?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=b534638ecb6ea4cc4b269ae0802c1bfd)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      let arr = (1, 2, 3, 4);

      //
      println!("{:#?}\n", arr);
      println!("{:?}", arr);
  }
  ```
  </details>

12 - How do you declare a variable named score and assign in the value 100?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=487b3cbc4b51474715d196cf24a54899)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let score: u8 = 100;
      println!("Value: {}", score);
  }
  ```
  </details>

13 - Write a line of code that declares a variable city with the value "Paris" and then prints it to the screen.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=b8fcb114295f9dc6b824778683735d34)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let city: &str = "Paris";
      println!("City: {}!", city);
      println!("City: {:?}!", city);
  }
  ```
  </details>

14 - Which keyword is used to declare a variable that can have its value changed after initialization?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=1d26ec751414229f76fad50bf10b45e2)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      // mut
  }  
  ```
  </details>

15 - Declare a mutable variable named counter initialized with 0. Then, write the code to change the value of counter to 5 and print it.

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9d0dbd340798526b8af17861dac4c10f)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let mut counter: u8 = 0;
      println!("Counter = {:?}", counter);

      counter = 5;
      println!("Counter = {:?}", counter);
  }
  ```
  </details>

16 - How do you declare a constant named MAX_SPEED with the value 9000 of type i32?

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9818b68a6204c70c9b9ff767ae640ccb)

  <details>
    <summary>Answers</summary>
    
  ```rust
  const MAX_SPEED: i32 = 9000;

  fn main() {
      //
      println!("Max Speed: {:?}", MAX_SPEED);
  }
  ```
  </details>

17 - Is it possible to change the value of a constant after its declaration?

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=3e186423e1b02403a6489773539ab55d)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      // no
  }
  ```
  </details>

18 - What is "shadowing" in Rust? Explain with a code example and what the output would be.

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=aacfd95ca5035c54c55cc00cc5a35ef4)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let x: i8 = 0;
      {
        let x: f32 = 1.0;
        println!("{:?}", x);
      }
      println!("{:?}", x);
  }
  ```
  </details>

19 - What will be the output of the following code?

  ```rust
  let x = 5;
  
  let x = x + 1;
  {
    let x = x * 2;
    println!("The inner value of x is: {}", x);
  }
  
  println!("The outer value of x is: {}", x);
  ```
  
 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=29acc4265a22d22caa0e1e9c8ebec2a1)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      let x = 5;
      let x = x + 1;
      {
        let x = x * 2;
        println!("The inner value of x is: {}", x);
      }

      println!("The outer value of x is: {}", x);
  }
  ```
  </details>

20 - What will be the output of the following code? Explain why

  ```rust
  let a = 10;
  {
    let b = 20;
    println!("Inside the block: a = {}, b = {}", a, b);
  }
  
  // println!("Outside the block: a = {}, b = {}", a, b);
  println!("Outside the block: a = {}", a);
  ```

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=20123a0e1fb08faaaa95fbe669b38fd5)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      let a = 10;
      {
        let b = 20;
        println!("Inside the block: a = {}, b = {}", a, b);
      }

      // println!("Outside the block: a = {}, b = {}", a, b);
      println!("Outside the block: a = {}", a);
  }
  ```
  </details>

21 - What would happen if the commented line were uncommented and compiled?

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=b0fb33a31ace400c7958947b73f2bca4)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      // fail to compile and produce a compile-time error.
  }
  ```
  </details>

22 - What is the range of values that a u8 type can store?

 [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=cc7a5ff024c87dceaa7364920ed84d5c)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      println!("u8: Max = {} and Min = {}", std::u8::MAX, std::u8::MIN);
  }
  ```
  </details>

23 - What is the range of values that an i8 type can store?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=121241dc00402af3cba3f08f47996427)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      //
      println!("i8: Max = {} and Min = {}", std::i8::MAX, std::i8::MIN);
  }
  ```
  </details>

24 - How do you declare a variable maximum_age of type u16 with the value 150?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=960a6771cb88056c79bfcb5e29aa9fa8)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let maximum_age: u16 = 150;
      println!("maximum_age: {}", maximum_age);
  }
  ```
  </details>

25 - How can you print the minimum and maximum values for the u32 type using its associated constants?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=fa9ce766e67a11d4b2ec3f63d7e0383d)

  <details>
    <summary>Answers</summary>
    
  ```rust
  const MAXIMUM: u32 = u32::MAX;
  const MINIMUM: u32 = u32::MIN;

  fn main() {
      //
      println!("Max = {}", MAXIMUM);
      println!("MIN = {}", MINIMUM);
  }
  ```
  </details>

26 - Declare a variable named 'price' of type f32 with the value 19.99.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=e77d724638b13ea2ab70724acc9eb349)

  <details>
    <summary>Answers</summary>
    
  ```rust
   fn main() {
      //
      let price: f32 = 19.99;
      println!("Price = {}", price);
  }  
  ```
  </details>

27 - Which of the types f32 or f64 offers greater precision?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=c0b536eb9115bacade017e9235e1390e)

  <details>
    <summary>Answers</summary> 

    - **f32 (single-precision floating-point):** Uses 32 bits to represent a floating-point number. This allows for a certain level of precision, but it's less precise than f64;
    - **f64 (double-precision floating-point):** Uses 64 bits to represent a floating-point number. The extra bits allow for a significantly larger range of representable numbers and, more importantly for this question, a much higher degree of precision in those representations.

  </details>

28 - How do you declare a variable named 'initial' that stores the character 'P'?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=0aa9d42ef8dfde633e562d54d8488249)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let initial = 'P';
      println!("The initial is: {}", initial);
  }
  ```
  </details>

29 - Can a char type in Rust store only ASCII characters? Explain.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a2367bdb18135f5d79b06ecf3e0d75fa)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let cyrillic_char = 'Я';
      println!("Cyrillic character: {}", cyrillic_char);
  }
  ```
  </details>

30 - Declare a variable named 'rain' and assign the value true to it.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=cc276fc9404a4321d32bbbe299ea0d56)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let rain: bool = true;
      println!("Rain? {}", rain);
  }
  ```
  </details>

31 - What are the only two possible values for a variable of type bool?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=aed5d71ff42bf8d07364d18d6e26f644)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main () {
      // true and false
  }
  ```
  </details>

32 - How do you declare a tuple named 'product' that stores an item's name (string), its quantity (integer), and its price (floating-point)? For example: ("Pe
n", 10, 1.50).

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a5bf6056eb8f5be1f01aa1d61b065536)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let product = ("Pen", 10, 1.50);
      println!("Product = {:?}", product);
  }
  ```
  </details>

33 - Given the tuple 'let coordinates = (10, 20, 30);', how would you destructure this tuple into three separate variables x, y, and z?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=5fd94401acad8e2e5818b2d262e445b1)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let product: (&str, u8, f32) = ("Pen", 10, 1.50);
      println!("Product: {}, {} and {}", product.0, product.1, product.2);

      //
      let (name, quantity, price): (&str, u8, f32) = ("Pen", 10, 1.50);
      println!("Product: {}, {} and {}", name, quantity, price);

      //
      let (name, quantity, price) = product;
      println!("Product: {}, {} and {}", name, quantity, price);
  }
  ```
  </details>

34 - How would you access the second element of the tuple 'let rgb = (255, 0, 128):'?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8c5e493c268b625e837a7ff63689eb77)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let product: (&str, &str, &str) = ("Item 1", "Item 2", "Item 3");
      println!("Product: {}", product.1);

      //
      let (item_01, item_02, item_03) = product;
      println!("Product: {}", item_02);
  }
  ```
  </details>

35 - Declare an array named 'notes' that can store 5 numbers of type f32. Initialize it with some values.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=20591a94ade8f226ee643ebdb4d37d82)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let notes: [u8; 5] = [1, 2, 3, 4, 5];
      println!("{:?}", notes);

      //
      let notes: [u8; 5];
      notes = [1, 2, 3, 4, 5];
      println!("{:?}", notes);

      //
      let notes_slice: &[u8] = &notes;
      println!("{:?}", notes_slice);

      //
      let partial_notes_slice: &[u8] = &notes[0..3];
      println!("{:?}", partial_notes_slice);
  }
  ```
  </details>

36 - What is the main difference between an array and a tuple in terms of the data types they can store?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=97f67c372ff407555be540707a5df1bc)

  <details>
    <summary>Answers</summary>
    
  - Tuples ((T1, T2, ..., Tn)):
    - Heterogeneous: Each element can have a different type (T1, T2, etc.);
    - Fixed Size: The number of elements is known at compile time and cannot change.

    Example:

    ```rust
    let person_data: (&str, i32, f64) = ("Alice", 30, 60.5);
    let coordinates: (i32, i32) = (10, 20);
    ```

  - Arrays ([T; N]):
    - Homogeneous: All elements must have the identical type T;
    - Fixed Size: The number of elements N is known at compile time and cannot change.

    Example:

    ```rust
    let numbers: [i32; 3] = [1, 2, 3];
    let words: [&str; 2] = ["hello", "world"];
    ```
  </details>

37 - How would you access the first element of the array: let cores = ["red", "green", "blue"];?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=783ac15d71fa170ba5166fd884d9fdcb)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      let list: [&str; 3] = ["red", "green", "blue"];
      println!("List: {:?}", list);

      //
      let list: [&str; 3] = ["red", "green", "blue"];
      println!("List: {:?}", list[0]);
  }
  ```
  </details>

38 - What is the result of the expression 10 % 3?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=7d3fdc6c7c4879c3854fbaa87d9f910f)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("{}", 10 % 3);
  }
  ```
  </details>

39 - What is the result of the expression 5.0 / 2.0?

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=90ff979dab835a73d3d0af9376e0f359)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("{}", 5.0 / 2.0);
  }
  ```
  </details>

40 - What will be the result of the following expression in Rust, and why? println!("{}", 20 - 5 * 2);

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=3dc47883e25713d88cec14a9d35d0dde)

  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("{}", 20 - 5 * 2);
  }
  ```
  </details>

41 - What will be the result of the following expression in Rust, and why? println!("{}", (20 - 5) * 2);

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8c121f9ed99c9fae2097aaea52290c79)
  
  <details>
    <summary>Answers</summary>
    
  ```rust
  fn main() {
      //
      println!("{}", (20 - 5) * 2);
  }
  ```
  </details>
