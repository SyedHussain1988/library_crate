# First Welcome Library Crate
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`library_crate = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "library_crate"
version = "0.1.0"
authors = ["SyedHussainAhmed121 <shas_virgo121@yahoo.com>"]
edition = "2018"

[dependencies]
library_crate = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use library_crate;
fn main() {
    println!("Hello, world!");
    library_crate::welcome();
}
```
following will also work:
```
use library_crate::welcome;
fn main() {
    println!("Hello, world!");
    welcome();
    }
```

now `cargo run` for results
