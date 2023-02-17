Command line used to find this crash:

afl-fuzz -m none -V 43200 -i /home/jongmunyang/fuzzing_tcpdump4/tcpdump-tcpdump-4.9.2/tests/ -o /home/jongmunyang/fuzzing_tcpdump4/out/ -s 123 -- /home/jongmunyang/fuzzing_tcpdump4/install/sbin/tcpdump -vvvvXX -ee -nn -r @@

If you can't reproduce a bug outside of afl-fuzz, be sure to set the same
memory limit. The limit used for this fuzzing session was 0 B.

Need a tool to minimize test cases before investigating the crashes or sending
them to a vendor? Check out the afl-tmin that comes with the fuzzer!

Found any cool bugs in open-source tools using afl-fuzz? If yes, please post
to https://github.com/AFLplusplus/AFLplusplus/issues/286 once the issues
 are fixed :)

