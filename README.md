# VEX BP Benchmarks
This is a collection of VEX contracts and utilities in use by the ProIt research group.
 

## Benchmarks
The benchmarks below are VEX contracts which are set on the `bpbenchmarks` account on Mainnet. They are executed during each block producers' schedule, and the timings recorded on-chain using the standard `cpu_usage_us` transaction field. The data is [freely available](https://explorer.vexanium.com/account/bpbenchmarks) to view and analyze, and we encourage doing so to help identify issues and improve block producer performance.


### CPU Benchmark

This benchmark targets the CPU by calculating Mersenne prime numbers. Calculating primes is an industry standard for measuring CPU performance and it uses code operations that are common in software development.

### RAM Benchmark

This benchmark targets VEX RAM by rapidly writing to and reading from a RAM table. Due to inefficiencies within the VEXCORE software this benchmark is currently CPU heavy and thus we consider it experimental and very similar to the CPU benchmark. As the software performance is improved we expect the results of this benchmark to become more meaningful.

--

#### Disclaimer
*VEX Token holders should not rely on VEX BP benchmark results as an absolute indication of block producers’ performance. Results are mainly intended for operators of the VEX infrastructure to have additional metrics that can aid them in testing different infrastructures, configurations and features while identifying performance differences and potential bottlenecks. These statistics are not subject to verification by other nodes on the network; therefore it is possible for block producers to manipulate them. Furthermore, running custom software or configurations may impact the measurement of these metrics.*

