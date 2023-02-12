# Interpreters and Compilers

Build an interpreter and a compiler for the `Lox` language in various programming
languages.

## Introduction

I attended [David Beazley's](https://dabeaz.com/) bootcamp on writing a compiler. As part
of the course, I read the book [Crafting Interpreters](https://craftinginterpreters.com/)
and really liked it. I also read [Writing An Interpreter In Go](https://interpreterbook.com/)
and [Writing A Compiler In Go](https://compilerbook.com/). I really liked the way the
authors of these books explained the concepts. I decided to write down my notes and
implement the code in various programming languages. I hope this book will help you
understand the concepts of interpreters and compilers. I do not plan to make any money
from this book and am making it available under the [MIT License](https://opensource.org/licenses/MIT).
I hope that people will find this book useful and will contribute to it to make it even
better.

## The "Book"

[Read the "book"](https://adityagudimella.github.io/intcomop/)

## The code

The code for the book is available in the [`code`](https://github.com/AdityaGudimella/CommandLineProgrammingLanguages/tree/main/code)
directory. Each language has its own directory. You can also find a link to the code
corresponding to each chapter at the end of each chapter.

Since the code in this book builds on the code from the previous chapter, it is not
organized as one directory per chapter. Instead, I use git tags to mark the code for
each chapter in the book. You can use the following command to check out the code
corresponding to a chapter:

```bash
git checkout <tag>
```

where `<tag>` is the tag for the chapter. For example, to check out the code for
chapter 1, you can use the following command:

```bash
git checkout chapter-1
```

## The languages

1. [C#](https://dotnet.microsoft.com/languages/csharp)
2. [Python](https://www.python.org/)
3. [Rust](https://www.rust-lang.org/)
4. [Go](https://golang.org/)

## References

1. [Crafting Interpreters](https://craftinginterpreters.com/)
2. [Writing An Interpreter In Go](https://interpreterbook.com/)
3. [Writing A Compiler In Go](https://compilerbook.com/)
