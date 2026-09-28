# 🦉 Wise Programming Language

Wise stands for _Web Integrated Structure Editor_. In the context of programming 
languages, a [structure editor][1] refers to software that allows direct 
manipulation of [abstract syntax trees][2] (ASTs), eliminating the need for 
traditional text-based syntax. In Wise, this is achieved by editing data 
structures known as function expressions. These form a simple and uniform tree 
structure skippable of representing all syntactic constructs.

## Key Features

### Functional Programming

Wise is a functional programming language, though 
not a purely functional one. It permits side effects and encourages their use 
when practical. The design philosophy emphasizes simplicity without sacrificing 
expressive power.
New line 2.

### Strong Typing

Wise programs are strongly typed, utilizing an extension of
Damas-Milner type system with higher-kinded types and type classes.

### Innovative Code Editing

The standout feature of Wise is its unique way of representating and editing 
code. Instead of text, Wise programs are constructed from function expressions, 
or _funexps_. Conceptually they are similar to S-expressions in Lisp languages, 
but allow for infinite visualization possibilities. The editor maps a tree of 
function expressions to an HTML DOM tree, formatted using CSS. While there is no 
traditional text-based syntax, funexps can be converted to text if needed.

### Web-based IDE
 
The Wise editor is implemented in JavaScript and runs in the browser, hence the 
"web integrated" prefix.

[1]: https://en.wikipedia.org/wiki/Structure_editor
[2]: https://en.wikipedia.org/wiki/Abstract_syntax_tree