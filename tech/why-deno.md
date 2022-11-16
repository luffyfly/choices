### Why do we choose Deno as our js engine?
With rust, wo have two choices for the js engine: Deno or Boa.

#### Compare

| | Deno | Boa | Exlain |
| --- | --- | --- | --- |
| Matureness | 5 | 1 | The current version of Boa is 0.16 and Boa is not stable for now.  |
| Api supporting | 5 | 2 | Deno supports fetch and WebWorker apis, and aoa does not.  |
| WebAssembly supporting | 5 | 1 | Deno supports wasm, and Boa does not.  |
| Debugging | 5 | 1 | Boa does not support debugging for now. |
| Performance | 5 | 3 | Deno uses V8 which is very fast. |

PS: We does not test the performance between Deno and Boa, because other reasons are enough to prove that Deno is better. 

So we choose Deno.
