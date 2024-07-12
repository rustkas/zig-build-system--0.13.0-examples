# Standard Configuration Options

Standard optimization options allow the person running `zig` build to select between `Debug`, `ReleaseSafe`, `ReleaseFast`, and `ReleaseSmall`. By default none of the release options are considered the preferable choice by the build script, and the user must make a decision in order to create a release build.

`zig build --help`

`zig build -Dtarget=x86_64-windows -Doptimize=ReleaseSmall --summary all`
