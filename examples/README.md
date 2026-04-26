# Examples for beman.take_before

<!--
SPDX-License-Identifier: 2.0 license with LLVM exceptions
-->

List of usage examples for `beman.take_before`.

## Samples

Check basic `beman.take_before` library usages:

* local [./take_before_compose.cpp](./take_before_compose.cpp) or [compose@Compiler Explorer](https://godbolt.org/z/7qY1Eo5Pv)
* local [./take_before_ntbs.cpp](./take_before_ntbs.cpp) or [ntbs@Compiler Explorer](https://godbolt.org/z/vqrK7xrP3)
* local [./take_before_direct_usage.cpp](./take_before_direct_usage.cpp) or [direct usage @Compiler Explorer](https://godbolt.org/z/9ad7qE7v9)
* local [./take_before_as_default_projection.cpp](./take_before_as_default_projection.cpp) or [projection @Compiler Explorer](https://godbolt.org/z/cfGYMda6n)

### Local Build and Run

```shell
# building
$ cmake --workflow --preset gcc-release

# run sample.cpp
$ ./build/examples/take_before_direct_usage
Original: 10 20 30 40
Take before 30: 10 20

```
