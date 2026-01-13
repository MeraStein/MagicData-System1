# system1

## Overview

This project is a simple in-memory version control system implemented in C++.  
It supports repository initialization, staging, committing, branching, merging, and viewing the repository state.

## Build & Test

```cmd
mkdir build
cd build
cmake .. -G "Visual Studio 17 2022" -A x64
cmake --build .
system1_tests.exe   # run automated tests
system1_cli.exe     # run the CLI
