---
# Lox            ![Repo Stars](https://img.shields.io/github/stars/dino65-dev/lox?style=social) ![Forks](https://img.shields.io/github/forks/dino65-dev/lox?style=social) ![Watchers](https://img.shields.io/github/watchers/dino65-dev/lox?style=social)

Lox is a dynamically-typed, object-oriented programming language with a focus on simplicity and flexibility. I've written this code Using  the Book [Crafting Interpreters](https://craftinginterpreters.com/) by [Bob Nystrom](https://github.com/munificent) Designed in Java (Jlox). Designed to be lightweight and easy to use, Lox is perfect for developers who want to experiment with scripting or dive into language design concepts. It runs on Python 3.12 and is currently under active development.

## Key Features:
- **Dynamic Typing**: Variables are not restricted by type, providing flexibility in coding.
- **Minimal Syntax**: Clean, readable code with minimal boilerplate.
- **Object-Oriented**: Supports classes and inheritance, making it ideal for modular programming.
- **Interpreted**: Lox runs without the need for compilation, allowing for rapid testing and debugging.

## Project Status:
Lox is still in development. We are actively improving the language and its interpreter. Feedback, issues, and contributions are welcome!

## Requirements:
- Python 3.10 or higher

## Installation:
To use Lox, you first need to clone the repository:

```bash
git clone https://github.com/dino65-dev/lox.git
```

Navigate to the cloned directory:

```bash
cd lox
```

## Usage:
Run the Lox interpreter to execute `.lox` files:

```bash
python lox.py <your-file>.lox
```

You can write your Lox scripts with basic constructs like variables, loops, and functions, or explore more advanced features like object-oriented programming.

Example Lox code:

```lox
// Example Lox Program
class Person {
    init(name) {
        this.name = name;
    }
    
    greet() {
        print "Hello, " + this.name + "!";
    }
}

var john = Person("John");
john.greet(); // Output: Hello, John!
```

## Contributing:
Contributions are encouraged! If you’d like to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a clear description of the changes.

## License:
This project is licensed under the Apache 2.0 License. Please see the `LICENSE` file for details.

---
