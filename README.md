## Benchmarks

1. A summary of all AIG benchmarks by [Alan](https://people.eecs.berkeley.edu/~alanmi/benchmarks/)
2. LUT benchmarks and sub-optimum AIGs from [EPFL](https://github.com/lsils/benchmarks)

## Intro to ABC

1. Download abc from: [github](https://github.com/berkeley-abc/abc)
2. Read abc documentation from [webpage](https://people.eecs.berkeley.edu/~alanmi/abc/)
3. Read 4 basic operations from [paper](./Papers/Scalable_Generic_Logic_Synthesis:_One_Approach_to_Rule_Them_All.pdf) and [paper](./Papers/Scalable_Logic_Synthesis_using_a_Simple_Circuit_Structure.pdf)



## Demo

1. Compile the verilog format circuit into an FPGA board.
2. Compare the performance difference between the best design and the worst design.
3. Implement a GUI to show the process of optimization

## Utilities

### Simulated Annealing of Rewrite (SA_rwr)

To get started:
```
    ./Util/SA_rwr -i benchmarks/tautology/t6_src.blif \
                  -o output.blif \
                  -n 10000 \
                  -r 0.99 \
                  -t 10 \
                  -v 1
```
