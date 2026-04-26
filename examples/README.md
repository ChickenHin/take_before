# Examples for beman.take_before

<!--
SPDX-License-Identifier: 2.0 license with LLVM exceptions
-->

List of usage examples for `beman.take_before`.

## Samples

Check basic `beman.take_before` library usages:

* local [./take_before_compose.cpp](./take_before_compoese.cpp) or [sample.cpp@Compiler Explorer](https://godbolt.org/z/ebEzYc5fv)
* local [./take_before_ntbs.cpp](./take_before_ntbs.cpp) or [std_vs_beman.cpp@Compiler Explorer](https://godbolt.org/z/P1c8x135M)
* local [./take_before_direct_usage.cpp](./take_before_direct_usage.cpp) or [direct usage @Compiler Explorer](https://godbolt.org/z/9ad7qE7v9)
* local [./take_before_as_default_projection.cpp](./take_before_as_default_projection.cpp)


### Local Build and Run

```shell
# building
$ cmake --workflow --preset gcc-release

# run sample.cpp
$ ./build/examples/take_before_direct_usage 
Original: 10 20 30 40 
Take before 30: 10 20 

```
