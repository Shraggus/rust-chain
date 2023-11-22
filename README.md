# RustChain
Group No: 13
**Members**
Gautham Roopesh (2021A7PS2471G)
Abhiram Ajith (2021A7PS2471G)
Advaith Krishna (2021A7PS2831G)
Kenz Abdulla (2021A7PS2664G)
**Problem statement:**
This Project aims to showcase the differences between Rust and C++ when it comes to performance in a blockchain implementation; the contrasting behaviour of both these languages are showcased. Rust has an in-bult memory management system, without a garbage collector which ensures in making safe and stable code, whereas a low-level language like C++, has its higher performance capabilities to its advantage. We are comparing our own simple Rust blockchain implementation to an open source C++ implementation. Tools such as 'hyperfine' and 'criterion' were used to gather the performance metrics such as CPU utilization. All statistics, results and graphs will be provided in the results directory
**Software Used:**
The Rust blockchain makes uses of relevant libraries such as 'tokio' (for asynchronous code writing), 'serde' (for serialization and deserialization of data structures), 'chrono' (time monitoring) and 'libp2p' (for p2p connection services). The C++ blockchain used is a simple open source implementation. For benchmarking and graphing, we have used hyperfine and criterion, with python graphing tools and gnuplot for results. The testing framework for criterion is included in the repo, but hyperfine has to be installed on the running machine
**POPL Aspects:**
Various POPL Aspects were critical into the making of this project. An imperative style of programming was used for the making of the Rust blockchain. This allowed to describe the program operated step by step. Several memory management features such as ownership system, borrowing and references, annotations, safe abstractions etc. enabled us to write memory-safe code in a clear and concise manner. 
**Results and Validation:**
Performance tests for both programs were conducted using the aforementioned software. We were able to get the basic speed and time consumption statistics for the implementations. Multiple sets of tests were run, with iterations having over a thousand blocks in the ledger to account for a moderately busy blockchain. 
**Potential for future work:**
A more complete version of the project with better implementations of the blockchain, with more features such as a consensur mechanism. We also were not able to do a full comparitive analysis of the programs, and more work can be done on that side. A more detailed comparitive analysis of the program can be run in order to finely analyze the system's performance and robustness. 