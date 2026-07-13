<h1 align="center">Hello, my name is Byte Dice!</h1>
<p  align="center">
  Award winning spaghetti chef<br>
  Award winning insect breeder<br>
  <sub>(In code, also a joke)</sub>
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
      "Python",
      "HTML / CSS / JS",
      "C#"
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

## Other things about me:
* Apparently people think I'm a femboy
* I really, really love Rust
* ...I know why people think I'm a femboy
