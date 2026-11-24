# Stella

Stella is a statically typed systems programming language designed for clarity, explicitness, and native performance.

> [!WARNING]
> Stella is currently under active development. Language syntax, standard library APIs, and ABI stability are not guaranteed until v1.0.0.

```stella
import "std/io.sl";

pub fn main() -> u8 {
	std.io.print("Hello, world!\n");
	return 0;
}
```
