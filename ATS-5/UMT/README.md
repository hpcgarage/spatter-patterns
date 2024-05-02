# UMT Spatter Patterns README

This directory contains patterns for the UMT application : https://github.com/LLNL/UMT

The following tables provides  details of what each compressed pattern file contains and how it was generated:


| File               | Function Profiled | Type        | UMT Benchmark | Run command                                          |
|--------------------|-------------------|-------------|---------------|------------------------------------------------------|
| umt_b1.json.gz     | sweepucbxyz_      | Function    | 1             | test_driver -B global -d 3,3,3 -b 1                  |
| umt_b2.json.gz     | sweepucbxyz_      | Function    | 2             | test_driver -B global -d 3,3,3 -b 2                  |
| umt_gpu_b1.json.gz | SweepUCBxyzKernel | CUDA Kernel | 1             | test_driver --use_cuda_sweep -B global -d 3,3,3 -b 1 |
| umt_gpu_b2.json.gz | SweepUCBxyzKernel | CUDA Kernel | 2             | test_driver --use_cuda_sweep -B global -d 3,3,3 -b 2 |




