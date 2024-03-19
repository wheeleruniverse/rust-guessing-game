## Rust Guessing Game

Follows the [Programming a Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html) section from The Rust Programming Language book.

### Build 

```
cargo build
```

### Run

```
cargo run
```

### Gameplay

The game will generate a random number known as `secret_number`. The goal is to keep guessing until you guess the `secret_number`. The game will provide hints like `Too small!` and `Too big!` while looping until you guess correctly or kill the program. Non-numeric input will not be accepted by the game, and you will immediately be re-prompted. 
