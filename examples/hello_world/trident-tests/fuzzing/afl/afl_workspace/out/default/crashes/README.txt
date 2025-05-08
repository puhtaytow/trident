Command line used to find this crash:

/home/redrum/.local/share/afl.rs/rustc-1.88.0-nightly-e9f8103/afl.rs-0.15.18/afl/bin/afl-fuzz -c0 -i /home/redrum/Projects/puhtaytow/trident/examples/hello_world/trident-tests/fuzzing/afl/afl_workspace/in -o /home/redrum/Projects/puhtaytow/trident/examples/hello_world/trident-tests/fuzzing/afl/afl_workspace/out -E 10000 -V 20 /home/redrum/Projects/puhtaytow/trident/examples/hello_world/trident-tests/fuzzing/afl/afl_target/debug/fuzz_0

If you can't reproduce a bug outside of afl-fuzz, be sure to set the same
memory limit. The limit used for this fuzzing session was 0 B.

Need a tool to minimize test cases before investigating the crashes or sending
them to a vendor? Check out the afl-tmin that comes with the fuzzer!

Found any cool bugs in open-source tools using afl-fuzz? If yes, please post
to https://github.com/AFLplusplus/AFLplusplus/issues/286 once the issues
 are fixed :)

