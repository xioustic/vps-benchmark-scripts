## UnixBench
Benchmark score using [UnixBench 5.1.3](http://code.google.com/p/byte-unixbench/). Multiple tests are conducted using various methods to create a baseline score that's indicative of the servers performance when running single, multiple & parallel tasks. Higher scores are better.

## I/O Benchmark
The speed that the server can read and write a 1GB file using the following command: dd if=/dev/zero of=sb-io-test bs=1M count=1k conv=fdatasync. Higher scores are better.

## IOPS Seek Benchmark
The number of uncached random reads per second with [IOPing](http://code.google.com/p/ioping/).

## BearScore
Bearscore is calculated by taking the average monetary value for UnixBench, I/O Benchmark, Bandwidth Benchmark, HDD, and RAM of a hosting plan. It's calculated separately for VPS & Dedicated hosting.