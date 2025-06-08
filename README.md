<h1 align="center">Hello, my name is Byte Dice!</h1>
<p  align="center">
  <img src="./assets/arrow-left.png" style="width: 1em; vertical-align: middle;">
  Certified insect exterminator in coding, Helldivers 2, and sometimes real life.
  <img src="./assets/arrow-right.png" style="width: 1em; vertical-align: middle;">
</p>

## About me

```rs
struct Person<'a> {
    name:          &'a str,
    pronouns:      &'a str,
    languages: Vec<&'a str>,
    websites:  Vec<&'a str>,
}

fn main() {
  let me = Person {
    name: "Byte Dice",
    pronouns: "up to your imagination (any)",
    languages: vec![
      "Rust",
      "HTML / CSS / JS",
      "Kotlin",
      "Python",
    ],
    websites: vec!["https://ByteDice.net"]
  };

  // unoptimal but more readable
  println!("Hello, I'm {}!", me.name);
  println!("My pronouns are {}.", me.pronouns);
  println!("I code in {}.", me.languages.join(", "));
  println!("Check out my websites:\n{}", me.websites.join("\n"));
}
```
\
**Little Bits of Byte:**
* POSTFIX NOTATION FOREVER!!!
* If it takes more than 0.5s to load, it's too slow. No exceptions. Go fix your code.
  * If it's a library that takes more than 0.5s to load -- then it's an unoptimized one.
