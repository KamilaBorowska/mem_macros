# `mem_macros`

`std::mem::size_of` and `std::mem::align_of` as a macro, to avoid turbofish notation.

## Examples

```
#[macro_use]
extern crate mem_macros;
assert_eq!(1, size_of!(u8));
```
