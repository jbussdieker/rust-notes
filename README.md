Rust packages are called crates. There are 2 types of crates:
* Binary crate
* Library crate

Variables are by default immutable but adding `mut` to the declaration will make them mutable

Variables passed to functions default to byval but can be passed byref using `&variablename`

This makes an immutable reference but using  `&mut variable name` we can get a mutable reference to the variable

Associated or static methods are referenced by `::`

Lines are terminated using `;`

Most functions return a `Result` enumeration to indicate success or failure and provide the returned value

Macros are called using `macroname!` where the `!` differentiates it from a normal method call

The standard library does not support random number generation but there is a `rand` crate available

It’s possible to build documentation for all installed dependencies using `cargo doc --open`

Normal member methods are referenced by `.`

You can shadow previous variables by defining them again

Variable types can be assigned using annotations which follow a colon `let guess: u32` this will create an immutable variable named guess with annotation indicating type is a 32-bit unsigned integer

The docs seem to prefer snake_case for source file names, variables and methods
