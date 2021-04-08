# Performance Analysis of Different Parallelization Frameworks on Heat Flow Application

This repo contains a class project for the course EC526 - Parallel Algorithms for High Performance Computing by Dr. Richard Brower, Spring 2021 at Boston University.

Potential Parallelization Frameworks to be tried are: 
-   OpenACC
-   C++ `<threads>`
-   C++ `<aysnc>`
-   C++ `<packaged_task>`
-   OpenMP
-   MPI
-   CUDA ??
-   GoLang
-   OpenCL

The serial implementation the Heat Flow Application will be written and then set as a baseline for comparison with accelerated versions of the same code using some of the frameworks listed above.


## Preliminary Investigation

Todo: Run some tests to see perfomr

Todo: See how different scheduling variations of OpenMP (dynamic, static, chunked) may affect a typical parallelized application, or maybe just ours. 



## Things to look into:

-   Find a code / write a code for the application. 
-   Verify that the code works as expected -> Discuss with Brower.
-   Write/Find + Test the python (or something else) visualization for the output. 