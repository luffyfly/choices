### Why Rust

To build 3d real-time applications, we must use a high-performance and low-level language which doesn't have a gc.
So we only have only two choices of C/C++ or Rust.

#### Goals

- High-performance
- Supporting WebAssembly well
- Safe
- Mature
- Easy to use

#### Compare C/C++, Rust
Scores: 5 is best, 1 is worse.

| Lang | C/C++ | Rust | Why|
| --- | --- | --- | --- |
| Performance | 5 | 5 | Both are low-level languages. |
| WebAssembly | 3 | 5 | Rust supports wasm by their maintainer, but C/C++ supoorts wasm by the third party. |
| Safe | 2 | 5 | Rust’s type system and ownership model guarantee memory-safety and thread-safety. C/C++'s pointers is not safe.|
| Matureness | 5 | 5 | C/C++ has a long history and Rust has a great community. |
| Ease of use | 3 | 2 | Rust is hard to learn. |

C/C++' score: 18, Rust's score: 22

For these reasons, we choose Rust as our programming language.
