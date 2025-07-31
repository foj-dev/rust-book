# Questions - Arithmetic Operators, Assignment Operators, String and &str, Tuples, Array, Scope, Precedence, Comparison and Logical

---
01 - Write a program that declares two integer variables, 'a' with the value 15 and 'b' with the value 7, and prints their sum.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=ba79725b1daeebae28b1f8eff37f3ef6)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let a: u8 = 15;
      let b: u8 = 7;

      //
      println!("{:?}", a + b);
  }
  ```
  </details>

02 - Create code that subtracts the value 3 from a variable called 'total' that initially equals 10, and displays the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=ce6ae9b7cf5ba78de17480e4ee126b7c)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let total = 10;
      let sub = total - 3;
      println!("{:?}", sub);

      //
      let mut total = 10;
      total -= 3;
      println!("{:?}", total);
  }
  ```
  </details>

03 - Develop a program that multiplies two variables, 'x' equals 6 and 'y' equals 8, and shows the product.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=70e75c196a74104dadd8c0b447c8b12e)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let x: u8 = 6;
      let y: u8 = 8;

      //
      let result: u8 = x * y;
      println!("{:?}", result);
  }
  ```
  </details>

04 - Implement code that divides the number 20 by 5 and prints the quotient.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=3310a0de603425918e6581d5b3721e2b)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut number: f32 = 20.;
      number /= 5.;

      //
      println!("{:?}", number);
  }
  ```
  </details>

05 - Write a program that calculates the remainder of the division of 23 by 4 and prints the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=d4c5c8dc43b052c33a57bd45d9d11a77)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut remainder: u8 = 23;
      remainder %= 4;

      //
      println!("{:?}", remainder);
  }
  ```
  </details>

06 - Declare two variables num1 (12) and num2 (5) and print the result of their sum directly within the println! macro.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=076ca45ba4bdd549e14c4559e5800ab3)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let num1: u8 = 12;
      let num2: u8 = 5;

      //
      println!("{:?}", num1 + num2);
  }
  ```
  </details>

07 - Create an immutable variable called 'value' that is the sum of 9 and 2, and print its value.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a9bc729353358ead87d8369738d196de)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let value: u8 = 9 + 2;
      println!("{:?}", value);
  }
  ```
  </details>

08 - Declare two variables 'first' (7) and 'second' (3) and print the result of their multiplication.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=633d7e426d95211f924fcd808a332ac3)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let first: u8 = 7;
      let second: u8 = 3;

      //
      println!("{:?}", first * second);
  }
  ```
  </details>

09 - Declare two variables 'dividend' (18) and 'divisor' (3) and store the result of the division in a variable called 'result', printing it.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=30f37a965c65eb08fc76b3751ccfd95e)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let dividend: u8 = 18;
      let divisor: u8 = 3;

      //
      let result: u8 = dividend / divisor;
      println!("{:?}", result);
  }
  ```
  </details>

10 - Declare two variables n1 (25) and n2 (7). Calculate and print the remainder of the division of n1 by n2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9880d7191e4c260e6a7cbd0f7c053b50)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let n1: u8 = 25;
      let n2: u8 = 7;

      //
      println!("{:?}", n1 % n2);
  }
  ```
  </details>

11 - Declare a mutable variable named counter with an initial value of 5. Increment it by 3 using the addition assignment operator and print the new value.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=7a8d2f1a19fccdcb70eeec71f7ab0fde)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut counter: u8 = 5;
      counter += 3;

      //
      println!("{:?}", counter);
  }
  ```
  </details>

12 - Create a mutable variable pontuacao initialized with 20. Decrement it by 5 using the subtraction assignment operator and display the final value.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=f4009497a1a81deb2ad17f177ea2b4d2)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut score: u8 = 20;
      score -= 5;

      //
      println!("{:?}", score);
  }
  ```
  </details>

13 - Declare a mutable variable fator with the value 2. Multiply it by 4 using the multiplication assignment operator and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=82ac11dee9d48d3431f72878863f0d61)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut value: u8 = 2;
      value *= 4;

      //
      println!("{:?}", value);
  }
  ```
  </details>

14 - Initialize a mutable variable size with 30. Divide it by 6 using the division assignment operator and show the resulting value.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=36e65843521161312365a71e69c8851f)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut size: u8 = 30;
      size /= 6;

      //
      println!("{:?}", size);
  }
  ```
  </details>

15 - Declare a mutable variable mod with the value 17. Calculate the remainder of the division by 5 using the remainder assignment operator and print the value.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=804489e2d5f2345e5760616564e55316)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      let mut mode: u8 = 17;
      mode %= 5;

      //
      println!("{:?}", mode);
  }
  ```
  </details>

16 - Declare two variables of type &str, part1 with "Hello, " and part2 with "Rust!". Concatenate them and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=19e51491cd2f3f2cbbf21143d21e9bcc)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let part1: &str = "Hello, ";
      let part2: &str = "Rust!";

      //
      println!("{:?}", part1.to_owned() + part2);
  }
  ```
  </details>

17 - Create two String variables, s1 with "Language" and s2 with "Rust.". Concatenate them and print the resulting string.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=43490545ac9f27c31901a3d3bbdede66)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let s1: String = String::from("Language ");
      let s2: String = String::from("Rust.");

      //
      println!("{:?}", s1 + &s2);
  }
  ```
  </details>

18 - Declare a variable of type &str called prefix with the value "Number: ". Create a variable of type String called number_str with the value "42". Concatenate them and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9d65adac0d80ea1a47b4a7ac17defe50)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let number: &str = "Number: ";
      let number_str: String = String::from("42");

      //
      println!("{:?}", number.to_owned() + &number_str);
  }
  ```
  </details>

18 - Create a String variable called initial_message with "Welcome ". Declare a &str variable called name with "User". Concatenate them and print the complete message.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=2295091d660ea2b9685cade8d09d6ccb)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let initial_message = "Welcome ";
      let name: &str = "User";

      //
      println!("{:?}", initial_message.to_owned() + name);
  }
  ```
  </details>

19 - Declare two variables greeting of type String with "Good " and period of type &str with "day!". Concatenate them and print the complete greeting.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=238b5e930de685cb06ca20e55c3576d3)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let greeting: String = String::from("Good ");
      let period: &str = "day!";

      //
      println!("{:#?}", greeting.to_owned() + &period);
  }
  ```
  </details>


XX - Create a program that sorts the following list in ascending order: Elements = [17, 43, 5, 54, 93];

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut elements: [u8; 5] = [17, 43, 5, 54, 93];
      elements.sort();

      println!("Ordenation: {:?}", elements);
  }
  ```
  </details>

XX - Write a program that creates an array with the following values: 1, 2, 3, 4, 5. Print the inverted array.

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut arr: [u8; 5] = [1, 2, 3, 4, 5];
      arr.reverse();

      println!("{:?}", arr);
  }
  ```
  </details>
  
XX - Write a program that finds the second largest number in a list. Arr: [17, 43, 5, 54, 93];

  <details>
  <summary>Answers</summary>
  
  ```rust
  fn main() {
      //
      let arr: [u8; 5] = [17, 43, 5, 54, 93];
      let mut arr_max: [u8; 5];
  
      arr_max = arr;
      arr_max.sort();
      arr_max.reverse();
  
      println!("{:?}", arr_max[1]);
  }
  ```  ```
  </details>  

20 - Create a tuple with three u8: (10, 20, 30). Access the first and second elements, add them and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=85d4b821bcfc7f29c3750cc50b189c57)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let tup: (u8, u8, u8) = (10, 20, 30);
      println!("{}, {}", tup.0, tup.1);
  }
  ```
  </details>

21 - Declare a tuple of two i32s. Initialize it with the values (5, -2). Print the multiplication of these two values.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=e0722f9856fd6420bdf854db51bda447)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let tup: (i32, i32) = (5, -2);
      println!("{:?}", tup.0 * tup.1);
  }
  ```
  </details>

22 - Create a nested tuple: ((1, 2), (3, 4)). Add the first element of the first tuple to the second element of the second tuple and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=843964881eecfdfb804108086bf46102)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let tup: ((u8, u8), (u8, u8)) = ((1, 2), (3, 4));
      println!("{:?}", tup.0 .0 + tup.1 .1);
  }
  ```
  </details>

23 - Declare two tuples, t1 with (2, 5) and t2 with (8, 1). Add all the elements of the two tuples and print the total.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8a22e77af9d0b7a18ac6012a7390804b)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let t1: (u8, u8) = (2, 5);
      let t2: (u8, u8) = (8, 1);

      //
      println!("{:?}", t1.0 + t1.1 + t2.0 + t2.1);
  }
  ```
  </details>

24 - Create a tuple with an f64 and an i32. Print each element separately.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=49be9b658f06dea9adab5077cb43985c)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut t1: (f32, i32) = (0.0, 0);
      t1.0 = -2.;
      t1.1 = 2;

      //
      println!("{:#?}", t1);
  }
  ```
  </details>

25 - Declare an array of 5 i32 with the values [1, 3, 5, 7, 9]. Print the sum of the first and last elements.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=e3342896a1b63feee95a878111a8daf9)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr: [i32; 5] = [1, 3, 5, 7, 9];
      println!("{}, {}", arr[0], arr[4]);
  }
  ```
  </details>

26 - Create an array of 3 u16. Initialize it with the values [10, 20, 30]. Print the product of all elements.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=02446a71b12a6262b64e2f2faabd4b94)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr: [i32; 3];
      arr = [10, 20, 30];

      //
      println!("{:?}", arr[0] * arr[1] * arr[2]);
  }
  ```
  </details>

27 - Declare a 2x2 multidimensional array with integers. Sum all elements and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=7b8c08f95d85e9bc254de6a437464b5b)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr: [[i8; 2]; 2];
      arr = [[2, 2], [4, 4]];

      //
      println!("{:?}", arr[0][0] * arr[0][1] * arr[1][0] * arr[1][1]);
  }
  ```
  </details>

28 - Create two arrays of two f32. Sum the corresponding elements of the two arrays and print the results of the sums.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=fd34ce0713943da9e41688fbef7424c8)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr1: [i8; 2] = [1, 2];
      let arr2: [i8; 2] = [1, 2];

      //
      println!("{:?}", arr1[0] * arr1[1] * arr2[0] * arr2[1]);
  }
  ```
  </details>

29 - Declare two arrays a1 with [4, 2] and a2 with [3, 6]. Calculate and print the sum of all elements from both arrays.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=1db2d55f7dc5fc32a20faed41d71452b)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let a1: [u8; 2] = [4, 2];
      let a2: [u8; 2] = [3, 6];

      //
      println!("{:?}, {:?}", a1[0] + a1[1], a2[0] + a2[1]);
  }
  ```
  </details>

30 - Declare a global variable with value 5. Inside a block {} declare another variable with the same name and value 10. Print the value of both variables (the global and the block variable) outside and inside the block.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=c933168e0df2e0c4546b1d3cf5ef1699)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let var: char = 'a';
      println!("{:?}", var);
      {
          let var: char = 'b';
          println!("{:?}", var);
      }
      println!("{:?}", var);
  }
  ```
  </details>

31 - Declare a variable x with value 1. Create an inner block where you declare a variable y with value 2. Inside the block, print the sum of x and y. Outside the block, try to print y (what will happen?).

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=d66b4b4a5e33c872d866cda67c0d0e59)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let x: u8 = 1;
      {
          let y: u8 = 2;
          println!("{:?}", x + y);
      }
      println!("{:?}", x);
      // println!("{:?}", y); cannot find value `y` in this scope
  }
  ```
  </details>

32 - Declare a variable level1 with value 10. Open a new block and declare a variable level2 with value 20. Inside this block, create another block and declare level3 with value 30. Print the sum of level1 and level3 inside the innermost block.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=95cf3f933752f8804abfc3e217d158d3)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let x: u8 = 1;
      {
          let y: u8 = 2;
          {
              //
              let z: u8 = 3;
              println!("{:?}", x + y + z);
          }
          println!("{:?}", y);
      }
      println!("{:?}", x);
  }
  ```
  </details>

33 - Declare a main variable with value 100. Create a block where you declare a variable with the same name and assign the value of main plus 50 to it. Print the value of the variable inside the block and outside the block.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=01c3267516f1340e4a042108ca1c94ea)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let num: u8 = 100;
      println!("{:?}", num);
      {
          let mut num: u8 = 100;
          println!("{:?}", num);
          {
              num += 50;
              println!("{:?}", num);
          }
          println!("{:?}", num);
      }
      println!("{:?}", num);
  }
  ```
  </details>

34 - Given the array values with [2, 3], write code that calculates and prints the result of values[0]+values[1]∗values[1].

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=4fc38c10f2e9f8af4b059f1d979c4f7b)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let var: [u8; 2] = [2, 3];
      println!("{:?}", var[0] + var[1] * var[1]);
  }
  ```
  </details>

35 - Using the same array values, write code that calculates and prints the result of (values[0]+values[1])∗values[1].

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=2ce6bcd5b4a70b7bd1efaf2da5fd145f)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let var: [u8; 2] = [2, 3];
      println!("{:?}", (var[0] + var[1]) * var[1]);
  }
  ```
  </details>

36 - Still with values, calculate and print values[0]∗values[1]/values[1]%values[1].

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=efeb476b82c5936b385067cc7ec87415)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let var: [u8; 2] = [2, 3];
      println!("{:?}", var[0] * var[1] / var[1] % var[1]);
  }
  ```
  </details>

37 - Calculate and print values[0]+values[1]−values[0]+values[0]∗values[0].

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=619694774b3dfb7d2417801e69a205cb)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let var: [u8; 2] = [2, 3];
      println!("{:?}", var[0] + var[1] - var[0] + var[0] * var[0]);
  }
  ```
  </details>

38 - Calculate and print ((values[0]+values[1])−(values[0]+values[0])∗values[0]).

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a731a6979c96bbc53019ed0fa1d4211b)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let var: [i8; 2] = [2, 3];
      println!("{:?}", (var[0] + var[1]) - (var[0] + var[0]) * var[0]);
  }
  ```
  </details>

39 - Declare two integer variables, num1 with value 10 and num2 with value 10. Write code that prints if num1 is equal to num2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=6987411834f9118f7707e0bc7d943035)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let num1: i8 = 10;
      let num2: i8 = 10;

      //
      println!("Num1 = Num2? {:?} ", num1 == num2);
  }
  ```
  </details>

40 - Declare two floating-point variables, f1 with 3.14 and f2 with 2.71. Write code that prints if f1 is different from f2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a530ea305ad2927dd433e555d4ffb182)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let f1: f32 = 3.14;
      let f2: f32 = 2.71;

      //
      println!("f1 != f2? {}", f1 != f2);
  }
  ```
  </details>

41 - Declare two integer variables, age1 with 25 and age2 with 30. Write code that prints if age1 is greater than age2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=a07816f8ff04db0f7df863401becda56)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let age1: u8 = 25;
      let age2: u8 = 30;

      //
      println!("Age-1 > Age-2? {}", age1 > age2);
  }
  ```
  </details>

42 - Declare two integer variables, point1 with 5 and point2 with 8. Write code that prints if point1 is less than point2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=7364e64dfa1a5b22f1db1e57328f12d5)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let point_1: u8 = 5;
      let point_2: u8 = 8;

      //
      println!("Point-1 < Point-2? {}", point_1 < point_2);
  }
  ```
  </details>

43 - Declare two integer variables, grade1 with 7 and grade2 with 7. Write code that prints if grade1 is greater than or equal to grade2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=c48944d03da1a64548da872e0dff14e9)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let grade_1: u8 = 7;
      let grade_2: u8 = 7;

      //
      println!("Grade-1 >= Grade-2? {}", grade_1 >= grade_2);
  }
  ```
  </details>

44 - Declare two integer variables, height1 with 170 and height2 with 165. Write code that prints if height1 is less than or equal to height2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=0520bbba63e5a59593f891d267f13360)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let height_1: f32 = 1.70;
      let height_2: f32 = 1.65;

      //
      println!("Height-1 <= Height-2? {}", height_1 <= height_2);
  }
  ```
  </details>

45 - Declare two boolean variables, true1 with true and true2 with true. Compare if they are equal and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9ebbbc8008bd6823590bbf1c736797ab)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let true_1: bool = true;
      let true_2: bool = true;

      //
      println!("True-1 == True-2? {}", true_1 == true_2);
  }
  ```
  </details>

46 - Declare an integer variable x with 5 and another y with 10. Check if x is not equal to y and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=e5f8a0a1835258198a69e7bd6c7f4158)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let x: u8 = 5;
      let y: u8 = 10;

      //
      println!("x != y? {}", x != y);
  }
  ```
  </details>

47 - Declare a variable temp1 with 22.5 and temp2 with 20.0. Check if temp1 is greater than temp2 and print.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=d6b51da7eba11107f6adbd7fb619c605)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let temp_1: f32 = 22.5;
      let temp_2: f32 = 20.;

      //
      println!("Temp1 > Temp2? {}", temp_1 > temp_2);
  }
  ```
  </details>

48 - Declare a variable count1 with 100 and count2 with 99. Check if count1 is less than count2 and print.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8e6d65a541d1156ea3dd5c4269b341df)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let count_1: u8 = 100;
      let count_2: u8 = 99;

      //
      println!("Count 1 < Count 2? {}", count_1 < count_2);
  }
  ```
  </details>

49 - Declare two boolean variables, cond1 as true and cond2 as true. Print the result of the logical AND (&&) operation between them.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=924c7f88d30b8c1acbe05c2d0d6f4d78)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let cond_1: bool = true;
      let cond_2: bool = true;

      //
      println!("Cond 1 && Cond 2: {}", cond_1 && cond_2);
  }
  ```
  </details>

50 - Declare flag1 as false and flag2 as false. Print the result of the logical AND operation between them.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=da4bcfbc81c52e6935eec8c759da69de)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let flag_1: bool = false;
      let flag_2: bool = false;

      //
      println!("Flag 1 && Flag 2: {}", flag_1 && flag_2);
  }
  ```
  </details>

51 - Declare active as true and allowed as false. Print the result of active && allowed.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=21a1c0c52c595a3399ed1c296e339e39)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let active: bool = true;
      let allowed: bool = false;

      //
      println!("Active && Allowed: {}", active && allowed);
  }
  ```
  </details>

52 - Declare has_permission as false and is_admin as true. Print the result of has_permission && is_admin.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=3e17966d1ed8415ace580de87215a10d)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let has_permission: bool = false;
      let is_admin: bool = true;

      //
      println!(
          " Has permission && Is admin: {}",
          has_permission && is_admin
      );
  }
  ```
  </details>

53 - Declare two boolean variables, option1 as true and option2 as true. Print the result of the logical OR (||) operation between them.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=9eff9a52575a2fd3e9151daaac2b8376)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let option_1: bool = true;
      let option_2: bool = true;

      //
      println!("Option 1 or Option 2: {}", option_1 || option_2);
  }
  ```
  </details>

54 - Declare error1 as false and error2 as false. Print the result of error1 || error2.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8af7eb80343f05502db36ec440b062c7)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let error_1: bool = false;
      let error_2: bool = false;

      //
      println!("Error 1 or Error 2: {}", error_1 || error_2);
  }
  ```
  </details>

55 - Declare connected as true and has_data as false. Print the result of connected || has_data.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=b5def9ce05b5f8a5930c93a572a882b6)

  <details>
  <summary>Answers</summary>

  ```rust
   fn main() {
      //
      let connected: bool = true;
      let has_data: bool = false;

      //
      println!("Connected Or Has data: {}", connected && has_data);
  }
  ```
  </details>

56 - Declare success as false and failure as true. Print the result of success || failure.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=8919aa4a8524f66baba5766ef9ab0764)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let success: bool = false;
      let failure: bool = true;

      //
      println!("Success OR Failure: {}", success || failure);
  }
  ```
  </details>

57 - Declare a boolean variable state as true. Print the result of the logical NOT (!) of state.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=f32b6d58be42cb535c0a3b281c64d39a)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let var: bool = true;
      println!("{:?}", !var);
  }
  ```
  </details>

58 - Declare a boolean variable invalid as false. Print the result of !invalid.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=34e20811739c8c8a827baf970810a7ab)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let invalid: bool = false;
      println!("{:?}", !invalid);
  }
  ```
  </details>

59 - Declare two u8 variables, val1 with 8 and val2 with 3. Calculate the sum, subtract 1 from the result, and print.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=f1744e9392a330122cb5c76c885d29e0)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let val_1: u8 = 8;
      let val_2: u8 = 3;

      //
      println!("{:?}", (val_1 + val_2) - 1);
  }
  ```
  </details>

60 - Create a tuple (u32, u32) with values (5, 10). Multiply the two elements and assign the result to a new variable, then print it.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=679eca9783df8cd9e363b431b44f26ad)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr_1: (u32, u32) = (5, 10);
      let arr_2 = arr_1.0 * arr_1.1;

      //
      println!("{:?}", arr_2);
  }
  ```
  </details>

61 - Declare an array [i32; 3] with values [2, 4, 6]. Divide each element by 2 (using division assignment if applicable) and print the resulting array.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=376d7b8b7c42cc5208fc6e923e7c7240)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let mut arr: [i32; 3] = [2, 4, 6];
      arr[0] /= 2;
      arr[1] /= 2;
      arr[2] /= 2;

      //
      println!("{:#?}", arr);
  }
  ```
  </details>

62 - Declare two variables n_a as 7 and n_b as 4. Calculate the remainder of the division of n_a by n_b and print if the remainder is equal to 3.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=bac43e837ffd593cee60160406896560)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let n_a: u8 = 7;
      let n_b: u8 = 4;

      //
      let rema: u8 = n_a % n_b;
      println!("Remainder: {:?} = 3? {:?}", rema, rema == 3);
  }
  ```
  </details>

63 - Create a String "Number: ". Concatenate with the result of the sum of two u8s (e.g., 5 + 7) converted to String. Print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=b884f435db8a5e41ca8d7990e2608510)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let num: String = String::from("Number: ");
      let sum: u8 = 5 + 7;

      //
      println!("{}{:?}", num, sum);
  }
  ```
  </details>

64 - Declare a tuple (f64, f64) with (2.5, 3.5). Sum the elements and print the result formatted to two decimal places.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=c5c8f9a3d00d3ae7d5ce8d56bd4ed91d)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let tup: (f64, f64) = (2.5, 3.5);
      let result: f64 = tup.0 + tup.1;

      //
      println!("{:.2}", result);
  }
  ```
  </details>

65 - Declare an array [u16; 2] with [100, 200]. Multiply the first element by 2 and the second by 3, then sum the results and print.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=69132860ad5bc19dca7f98bbf5680b72)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let arr: [u16; 2] = [100, 200];
      println!("{:?}", (arr[0] * 2) + (arr[1] * 3));
  }
  ```
  </details>

66 - Declare a mutable variable message with "&str" "Start". Append to it the String " -> End". Print the final value of message.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=5bc36877ec0c3c3d971220e0650843cd)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let message: &str = "Start";
      println!("{}", message.to_owned() + " -> End");
  }

  // string
  fn main() {
      //
      let mut message: String = String::from("Start");
      message += " -> End";

      //
      println!("{}", message);
  }
  ```
  </details>

<!--
Tuples!
-->

Create a tuple with the following values: Name, 80;

67 - Create a tuple (i8, i8, i8) with (1, 2, 3). Sum all three numbers and print the result.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=6b1cc95dbb15e089aceb517bb8388b84)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let tup: (i8, i8, i8) = (1, 2, 3);
      println!("{:?}", tup.0 + tup.1 + tup.2);
  }
  ```
  </details>

68 - Declare an outer_level variable with 5. Inside a block, declare inner_level with 10. Print the sum of both inside the block. Outside the block, try to print inner_level (what happens?).

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=f74d8944f2f63befc98254f2362534e1)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let outer_level: u8 = 5;
      {
          let inner_level: u8 = 10;
          println!("{:?}", outer_level + inner_level);
      }
      // println!("{:?}", outer_level + inner_level);
  }
  ```
  </details>

69 - Given an array data with [3, 2], calculate and print the result of data[0]+data[1]∗5. Then, calculate and print (data[0]+data[1])∗5.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=2be4208055486cc4d4bd3ee059a6fc07)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let data: [u8; 2] = [3, 2];

      //
      println!("{:?}", data[0] + data[1] * 5);
      println!("{:?}", (data[0] + data[1]) * 5);
  }
  ```
  </details>

70 - Given an array calc_values with [10, 3, 2], calculate and print calc_values[0]/calc_values[1]+calc_values[2]. Then, calculate and print calc_values[0]/(calc_values[1]+calc_values[2]).

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=3cdb6800da4f9c29b9b9101772b46918)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let calc_values: [u8; 3] = [10, 3, 2];

      //
      println!("{:?}", calc_values[0] / calc_values[1] + calc_values[2]);
      println!("{:?}", calc_values[0] / (calc_values[1] + calc_values[2]));
  }
  ```
  </details>

71 - Declare a global_factor variable with 2. Inside a block, declare an array nums with [1, 2, 3]. Sum the array elements and multiply the result by global_factor, printing the final result inside the block.

  [Playground!](https://play.rust-lang.org/?version=stable&mode=debug&edition=2024&gist=523af4bb8f140db9108f9a7a6162fea4)

  <details>
  <summary>Answers</summary>

  ```rust
  fn main() {
      //
      let global_factor: u8 = 2;
      {
          let block: [u8; 3] = [1, 2, 3];
          let result = (block[0] + block[1] + block[2]) * global_factor;
          println!("{:?}", result);
      }
  }
  ```
  </details>


swap() (Trocar elementos de posição)
Slice para Outro Slice com copy_from_slice()
Trocar Elementos com swap_with_slice()

**
 
let ponto3d = (10, 20, 30);
println!("Ponto 3D original: {:?}", ponto3d);

// Desestruturando a tuple
let (x, y, z) = ponto3d;

// Criando uma nova tuple com 'y' modificado
let novo_ponto3d = (x, y * 2, z);

**

chunks(), windows() e split_at() (Leitura de Partes)

Iteradores (iter(), iter_mut(), into_iter()) ++  (como map, filter, fold, sum, max, min, etc.) 

Create a tuple with the following values: Name, 20;
Write a tuple that can receive a name and an age given by the user. Arr = (name, age);


