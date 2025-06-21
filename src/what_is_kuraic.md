# What is kuraic?

(This feels like a copy of Rust book lol)
Welcome to "The kuraic book"! `kuraic` is the compiler for the Kurai programming language, provided by the project itself. The compiler can take your source code and compile it into an executable at the time of writing this book.

Personally, I wouldn't use `kuraic` for compiling your project, instead we could use a program called `Kuros`. `Kuros` uses `kuraic` under the hood though. But for more advanced programmers, go ahead and use `kuraic`! No one's stopping you.

# Basic usage

First things first, go ahead and create a `hello.kurai` file. Let's say this is what you wrote in `hello.kurai`:

```
fn main() {
    printf("Hello, World!");
}
```

To turn this source code into an executable, you can use `kuraic`:

```
$ kuraic hello.kurai -o hello
```

To run it:

```
$ ./hello # on a \*NIX
$ .\hello # on a Windows
```
