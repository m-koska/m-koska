## Hi, I'm Michał

student at **University of Warsaw**, passionate **programmer** and economist

### My skills:
- low latency C++
- cache-friendly programming
- algorithms
- finance
- data science in R (especially natural language processing)

*Recently I am also exploring **functional programming in Haskell***


### Take a look at some of my repos:

- [hft-engine-with-research-pipeline](https://github.com/m-koska/hft-engine-with-research-pipeline) - high performance research pipeline with sophisticated data structures, with ~ 10 ns performance on `AddOrder` measured on random price levels around the spread
  - **custom allocator**, bitboard, cache-friendly data design
  - NASDAQ ITCH 5.0 parser with historical data replayer
  - exporting orderflow imbalance to csv files for further research
- [gui-market-agent-model](https://github.com/m-koska/gui-market-agent-model) - a stochastic, multithreaded implementation of Brooks-Hommes model
  - lock-free **ring buffer**
  - profiled to reduce context switching overload
  - `std::barrier` and `std::atomic` instead of `std::mutex`
- [codecrafters-shell-haskell](https://github.com/m-koska/codecrafters-shell-haskell)
  - parsing commands
  - pattern matching
  - POSIX API
