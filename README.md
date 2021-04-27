# Set-Associative-Cache

This project included 5 main steps. The first step was to write a software benchmark program that calculated the Least Common Denominator (LCD) of two random integers x & y where 80 ≤ 𝑥 ≤ 130 and 10 ≤ 𝑦 ≤ 60.

The second step was to build a reference system. This reference system was a modified version of the SimpleCompArch_2021 system. The reference system included the implementation of the main memory module which operates at 1/25th the speed of the CPU, and the memory was a size of 4k 16 bit words.

The third step was to create a separate enhanced system. This enhanced system also used the SimpleCompArch_2021 system and was implemented with a 2-way set-associative cache. The intention was to use the cache as an interface between the main memory and CPU to limit memory accesses and enhance performance.

The fourth step was to compare both systems using the benchmark program from step 1 to evaluate their performances. The expectation was that the enhanced system would require less memory access than the reference system, which would enhance the performance. 

Finally, the last step was to load these systems onto an FPGA-board to debug the signals.
