# Rust Chapter XI

#### Telling the program not to use any parallelism

```shell
cargo test -- --test-threads=1
```

#### Showing Function Output

```shell
cargo test -- --show-output
```

#### Running a Subset of Tests by Name

```shell
cargo test [test_name]
```

#### Filtering to Run Multiple Tests

```shell
cargo test [filtered_name]
```

#### Running ignored tests

```shell
cargo test -- --ignored
```

### Reference

https://doc.rust-lang.org/stable/book/ch11-00-testing.html
