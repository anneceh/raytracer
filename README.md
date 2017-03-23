# raytracer
Ray tracer in Rust from the Itera ray tracer workshop. For more information visit https://github.com/Itera/rust-raytracer-workshop

## Setup
The first thing you need to do (if you haven't already) is to install Rust, you can find the installation instructions [here](https://www.rust-lang.org/en-US/install.html).
**Note for Windows users:** you also need to install the [VS C++ toolchain](http://landinghub.visualstudio.com/visual-cpp-build-tools).

There are language support in most major text editors, and in some IDEs.
Check out [Are we IDE yet](https://areweideyet.com/) for a list of plugin support for your favorite editor.
The only thing you really need is syntax highlighting for the `.rs` file extension.

By default the latest version of Rust will be installed, together with the latest version of Cargo.
Cargo is the build tool and package manager for rust, it lets us build libraries and executables, and run tests and the executables we have defined in the project.

There's three commands you will find usable for this project:
* `cargo check` - this command checks whether the project will compile or not, any compilation warning (and trust me, you will encounter them) will be shown as part of the command output (this command requires that you have the latest version of Rust installed on your system).
* `cargo test` - this command builds the project *and* runs all the tests in the project.
You should run this command while you solve the assignments, they should indicate when you have passed the different steps.
* `cargo run --bin image` - this command builds the project *and* runs the executable file found in `src/bin/image.rs` (this file contains a `main()` function, and is therefore an executable).
