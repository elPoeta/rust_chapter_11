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

### Integration tests

#### The tests Directory

```
adder
├── Cargo.lock
├── Cargo.toml
├── src
│   └── lib.rs
└── tests
    └── integration_test.rs

```

#### Run a particular integration test

```shell
cargo test --test integration_test
```

### Submodules in integration tests

```
├── Cargo.lock
├── Cargo.toml
├── src
│   └── lib.rs
└── tests
    ├── common
    │   └── mod.rs
    └── integration_test.rs
```

### Reference

https://doc.rust-lang.org/stable/book/ch11-00-testing.html
