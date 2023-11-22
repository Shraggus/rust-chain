All tests were conducted in the local directories on separate frameworks due to difficulties faced in building a unified testing pipeline
**To run tests:**
For CPP: navigate to build and do hyperfine make to get basic benchmarks
Hyperfine will automatically determine the number of runs to perform for each command. By default, it will perform at least 10 benchmarking runs and measure for at least 3 seconds. To change this, you can use the -r/--runs option
hyperfine --runs 5 'sleep 0.3'
You can use the --export-json "json-name" option to create tables
For Rust: navigate to rust-blockchain folder and do cargo bench to get results