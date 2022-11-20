## Why use Rust as our primary programming langauge?

To build 3d real-time applications, we must use a high-performance and low-level language which doesn't have a gc.
So we only have only two choices of C/C++ or Rust.

### Goals

- High-performance
- Supporting WebAssembly well
- Safe
- Mature
- Easy to use

### Comparison
Scores: 5 is best and 1 is worse.

| Feature | C/C++ | Rust | Why|
| --- | --- | --- | --- |
| Performance | 5 | 5 | Both are low-level languages. |
| WebAssembly | 3 | 5 | Rust supports wasm by their maintainer, but C/C++ supoorts wasm by the third party. |
| Safety | 2 | 5 | Rust’s type system and ownership model guarantee memory-safety and thread-safety. C/C++'s pointers are not safe.|
| Matureness | 5 | 5 | C/C++ has a long history and Rust has a great community. |
| Ease of use | 4 | 2 | Rust is hard to learn. |

C/C++'s score is 18 and Rust's score is 22.

For these reasons, we choose Rust as our programming language.
