# RustChain
**Problem statement:**
This Project aims to showcase the differences between Rust and C++ when it comes to performance in a blockchain implementation. We are comparing our own simple Rust blockchain implementation to an open source C++ implementation. We are using hyperfine and criterion as benchmarking tools for the programs. All statistics, results and graphs will be provided in the results directory
**Software Used:**
The rust blockchain makes uses of relevant libraries such as tokio (for asynchronous code writing), serde (for serialization and deserialization of data structures), chrono (time monitoring) and libp2p (for p2p connection services). The c++ blockchain is a simple open source implementation. For benchmarking and graphing, we have used hyperfine and criterion, with python graphing tools and gnuplot for results. The testing framework for criterion is included in the repo, but hyperfine has to be installed on the running machine
**POPL Aspects:**
**Results and Validation:**
We conducted performance tests for both programs using aforementioned software. We were able to get the basic speed and time consumption statistics for the implementations. We ran multiple sets of tests, with iterations having over a thousand blocks in the ledger to account for a decently busy blockchain
**Potential for future work:**
We could do a more complete version of the project with better implementations of the blockchain, with more features. We also were not able to do a full comparitive analysis of the programs, and more work can be done on that side