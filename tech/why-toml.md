### Why use toml as our config file format?

After doing some research, I found four choices: toml, ini, yaml, json and xml from [this link](https://www.barenakedcoder.com/blog/2020/03/config-files-ini-xml-json-yaml-toml/).

#### Goals
- Simple
- Powerfull
- Compatiable with Rust
#### Comparison
Scores: 5 is best and 1 is worse.
| Feature | toml | ini | yaml | json | xml | Explain |
| ----- | -- | -- | --- | -- | -- | ----- |
| Simple |  4 | 5 | 3 | 3 | 2 | |
| Powerful | 3 | 2 | 3 | 4 | 5 | See [wiki](https://en.wikipedia.org/wiki/TOML) |
| Compatiable with Rust | 5 |  4 | 4 | 4 | 4 | Rust is born with `toml`. |
| Total |  12 | 11 | 11 | 11 | 11 | |

So we choose `toml` as our config file format.
