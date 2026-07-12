<p align="center">
  <img src="https://github.com/hei-templates/hei-synd-logos/blob/a47918f96647efdc10d30127b5e194b1f1005cff/hei-en.svg" alt="HEI-Vs Logo" width="350">
</p>

# HEI-Vs Engineering School - AProg Advanced Programming

<p align="center">
  <img src="https://github.com/hei-templates/hei-synd-logos/blob/a47918f96647efdc10d30127b5e194b1f1005cff/orientations/it-logo.svg" alt="Systems Engineering Infotronics Logo" width="350">
</p>

<p align="center">
  <img src="https://github.com/hei-templates/hei-synd-logos/blob/a47918f96647efdc10d30127b5e194b1f1005cff/courses/aprog.svg" alt="Advanced Programming Logo" width="150">
</p>

Welcome to the **AProg Advanced Programming** course of the [HEI-Vs Engineering School](https://synd.hevs.io) in Sion, Switzerland. AProg is part of the module SwD Software Development for the orientation [Infotronics](https://synd.hevs.io/education/infotronics.html) and runs in Semester 3 (105h, 7 ECTS).

AProg teaches modern software development through **[Rust](https://www.rust-lang.org/)**: from imperative basics to object-oriented idioms, design patterns, concurrency and software quality. You will spend most of your time hands-on, writing, running and debugging real code.

## Course Content

| # | Chapter | You will learn |
|---|---------|----------------|
| 1 | Introduction | Course setup, Rust toolchain, Cargo, `clippy`, `rustfmt` |
| 2 | Imperative Programming | Variables, types, control flow, functions, ownership & borrowing |
| 3 | Object-Oriented Programming | Structs, enums, traits, trait objects, modules & visibility |
| 4 | Design Patterns | Idiomatic Rust patterns (Builder, Strategy, Newtype, Iterator, ...) |
| 5 | Concurrency & Parallel Programming | Threads, channels, `async`/`await`, Tokio, Rayon |
| 6 | Debugging, Testing & Documentation | Unit/integration/doc tests, `dbg!`, logging, `rustdoc` |

## Repositories

Here are the repositories available for this course:

- [aprog-docs](https://github.com/hei-synd-swd/aprog-docs): This repository contains all the course materials, including lecture slides, exercises, laboratory and projects documents.
- [aprog-labs](https://github.com/hei-synd-swd/aprog-labs): This repository contains additional resources for the laboratories and exercises.
- [aprog-project](https://github.com/hei-synd-swd/aprog-project): This repository contains additional resources for the project.

## Prerequisites

To follow along and solve the exercises you need the Rust toolchain and the [LangQuest](https://github.com/tschinz/langquest) exercise runner.

```bash
# 1. Install Rust (includes cargo, rustc)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# 2. Add the formatter and linter
rustup component add rustfmt clippy
cargo install cargo-edit cargo-generate just

# 3. Install the LangQuest exercise runner
cargo install --git https://github.com/tschinz/langquest
```

On Windows, install Rust from [rustup.rs](https://rustup.rs) and run the same `rustup`/`cargo` commands.

## Contributing

We welcome contributions from students and faculty members of HEI-Vs Engineering School. If you would like to contribute to any of the repositories, please follow these steps:

1. Fork the repository you want to contribute to.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your forked repository.
5. Open a pull request in the original repository and describe your changes.

Please ensure that you follow the code of conduct and guidelines for contributing as outlined in each repository.

## Issues and Support

If you encounter any issues or have questions regarding the course or any of the repositories, please feel free to open an issue in the respective repository. Our team will be happy to assist you.

## Find us on

[Systems Engineering](https://synd.hevs.io) &nbsp;&middot;&nbsp;
[Smart Process Lab](https://spl.hevs.io) &nbsp;&middot;&nbsp;
LinkedIn [HEI-Vs](https://www.linkedin.com/showcase/school-of-engineering-valais-wallis/) &nbsp;&middot;&nbsp;
Youtube [HES-SO Valais-Wallis](https://www.youtube.com/user/HESSOVS) &nbsp;&middot;&nbsp;
Twitter [@hessovalais](https://twitter.com/hessovalais) &nbsp;&middot;&nbsp;
Facebook [@hessovalais](https://www.facebook.com/hessovalais) &nbsp;&middot;&nbsp;
