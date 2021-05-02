# Hash Table Implementation in [Rust](https://rust-lang.org/)

![unsafe](./unsafe.gif)

Purely for educational and recreational purposes. For real world production please use [std::collections::HashMap](https://doc.rust-lang.org/std/collections/struct.HashMap.html).

For resolving collisions we use [Open Addressing](https://en.wikipedia.org/wiki/Hash_table#Open_addressing). For the hash function we use [djb2](http://www.cse.yorku.ca/~oz/hash.html)

## Quick Start

```console
$ cargo run --release
```

## References

- https://en.wikipedia.org/wiki/Hash_table
- https://github.com/rust-lang/hashbrown
