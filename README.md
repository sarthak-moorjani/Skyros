## Scalable Reads on Skyros - Syros

Syros is a new replication protocol based on Skyros and Paxos Quorum Reads that offers high performance reads and writes in a geo distributed storage system. This repository contains all the source code of Syros’ implementation and all the experiments that were run as part of benchmarking in the paper - “Scalable Reads On Skyros”. 

Please look at https://github.com/sarthak-moorjani/Skyros/blob/master/experiments/README.md for running experiments. We have run the following experiments 
1. ycsb
2. micro-nilext-only
3. micro-nilext-reads

If you would like to run the cluster by yourself, please refer to [./src/README.md](./src/README.md). 
