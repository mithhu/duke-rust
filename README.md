## Main.rs: Hello World in Rust

This is a simple "Hello World" program written in Rust.

```rust
fn main() {
    println!("Hello, World!");
}
```
# Devcontainer Configuration for Rust Development

The `devcontainer.json` file contains settings that define the development environment inside a Docker container. Some key specifications include:

- The **name** of the container ("Rust")
- Building the container from a Dockerfile in the current directory
- Extensions to install in VS Code, such as `rust-analyzer` and `aws-code-whisperer`
- Settings for `rust-analyzer`, such as enabling auto-reloading on cargo changes

This configuration facilitates opening the Rust project folder in a containerized development environment using the VS Code Codespaces.

## How to Use this Configuration:

1. Clone this repo and create a new Codespace configuration with dev containers in github.
2. You can now develop inside the containerized environment.

