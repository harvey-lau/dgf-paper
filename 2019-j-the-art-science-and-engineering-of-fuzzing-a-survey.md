# 精读：[*The Art, Science, and Engineering of Fuzzing: A Survey*](https://ieeexplore.ieee.org/abstract/document/8863940)

- Definition 1 (Fuzzing). Fuzzing is the execution of the PUT using input(s) sampled from an input space (the "fuzz input space") that protrudes the expected input space of the PUT.
- Definition 2 (Fuzz Testing). Fuzz testing is the use of fuzzing to test if a PUT violates a correctness policy.
- Definition 3 (Fuzzer). A fuzzer is a program that performs fuzz testing on a PUT.
- Definition 4 (Fuzz Campaign). A fuzz campaign is a specific execution of a fuzzer on a PUT with a specific correctness policy.
- Definition 5 (Bug Oracle). A bug oracle is a program, perhaps as part of a fuzzer, that determines whether a given execution of the PUT violates a specific correctness policy.
- Definition 6 (Fuzz Configuration). A fuzz configuration of a fuzz algorithm comprises the parameter value(s) that control(s) the fuzz algorithm.

Algorithm 1: Fuzz Testing

Figure 1: Genealogy tracing significant fuzzers' lineage back to Miller et al.'s seminal work.

Table 1: Overview of fuzzers sorted by their instrumentation granularity and their name.
