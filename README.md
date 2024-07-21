# Hexadecimal SVG Image Generator

This program takes a hexadecimal input and generates an SVG image from it. The
objective of this project is introducing parallelism in Rust. The first version
of the program (the one in the master branch) is the single threaded
implementation. To view the multithreaded implementation, reference the parallel
branch.

## Usage

Run the program with a hexadecimal input argument:

1. Clone the repository
   ```text
   git clone https://github.com/freddiehaddad/render-hex
   ```
1. Build and run
   ```text
   cargo run -- a4d4d44d44d44d4
   ```
1. Open the `sample.svg` file in any SVG viewer.

## Commands

| hex value | command        |
| --------- | -------------- |
| `0`       | Home           |
| `a`       | Turn Left      |
| `b`       | Turn Left      |
| `c`       | Turn Left      |
| `d`       | Turn Right     |
| `e`       | Turn Right     |
| `f`       | Turn Right     |
| `1`       | Forward 1 unit |
| `2`       | Forward 2 unit |
| `3`       | Forward 3 unit |
| `4`       | Forward 4 unit |
| `5`       | Forward 5 unit |
| `6`       | Forward 6 unit |
| `7`       | Forward 7 unit |
| `8`       | Forward 8 unit |
| `9`       | Forward 9 unit |

## Requirements

- The Rust toolchain
