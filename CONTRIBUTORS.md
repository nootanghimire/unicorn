# Contributing to unicorn

## Public domain declaration

unicorn is free and unencumbered software released into the public domain. We can only accept your contributions if you dedicate it to the public domain as per the clauses of the [LICENSE](LICENSE). We request you to please sign the declaration mentioned in [CREDITS](credits.md) by adding your name and email to the list of contributors as part of your patch.

Please refrain from contributing patches that conflict with the LICENSE or that you do not own the right to dedicate to public domain.

## Build

### Pre-requisites

- [Rust](https://www.rust-lang.org/) v1.7.0+ with `cargo`.

### Building from source

- Clone the repo
- At the root of the repo, run:

      ```
      $ cargo build
      ```

This will create the compiled binary at `./target/debug/unicorn`.

### Creating a release build

If you want a build with all optimizations in place, run this at the root of the repo:

```
$ cargo build --release
```

This will create the compiled binary at `./target/release/unicorn`.

## Tests

```
$ cargo test
```
