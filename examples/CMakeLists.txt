# SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception

set(ALL_EXAMPLES take_before_direct_usage take_before_as_default_projection take_before_compose)
message("Examples to be built: ${ALL_EXAMPLES}")

foreach(example ${ALL_EXAMPLES})
    add_executable(${example})
    target_sources(${example} PRIVATE ${example}.cpp)
    target_link_libraries(
        ${example}
        PRIVATE beman::take_before
    )
endforeach()
