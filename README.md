# Introduction
This is the repo for optimized version of MrBayes used in SCC17, Nov 2017.
In the competition, we used the code on master branch, which is implemented in AVX256. 

The AVX512 version is under AVX512 branch. 

# Performance
Since AVX512 is capable of doing calculation on 512 bits at once, it can achieve 4x theoretical speedup. On the given data set prior to SCC17, we also observed a 4x speedup.
