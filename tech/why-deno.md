### Why do we choose Deno as our js engine?
With rust, wo have two choices for the js engine: Deno or Boa.

#### Goals
- Mature
- High-performance
- Supporting debugging
- Supporting WebAssembly
- Minimal-size

#### Comparison
Sores: 5 is best and 1 is worse.

| | Deno | Boa | Exlain |
| --- | --- | --- | --- |
| Matureness | 5 | 1 | The current version of Boa is 0.16 and Boa is not stable for now. Deno supports fetch and WebWorker apis, and Boa does not.  |
| Performance | 5 | 3 | Deno uses V8 which is very fast. |
| Debugging | 5 | 1 | Boa does not support debugging for now. |
| WebAssembly | 5 | 1 |  Boa does not support WebAssembly for now. |
| Size | 1 | 5 |  Deno(23.35) = deno(3.65 MB) + rusty_v8(19.7); Boa < 1MB |
| Total | 21 | 11 | |


PS: We does not test the performance between Deno and Boa, because other reasons are enough to prove that Deno is better. 

So we choose Deno.
