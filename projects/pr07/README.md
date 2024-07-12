## Dynamic Library

This build script creates a dynamic library from Zig code.

`zig build --summary all`

`zig build-exe demo.zig -l fizzbuzz -L fizzbuzz.lib`

`zig build --summary all -Denable-demo`