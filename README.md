# cache-simulator

This was a project completed for ECE463, Advanced Microprocessor design to simulate an N-way set-associative single-hierarchy cache. The project was written in C. To compile use the makefile.

### Command line arguments:
`>./sim_cache <BLOCKSIZE> <L1_SIZE> <L1_ASSOC> <L2SIZE> <L2_ASSOC> <REPL_POLICY> <INCLUSION> <TRACE_FILE>`*

**Note that for this project, L2 options and inclusion policy do nothing.*

#### sim_cache.c:
Contains main.

#### add_zeros.c
Adds leading zeros to a binary char array.

#### binary_tree.c
Provides functions that travel through a binary tree array, using Eytzinger's method, either starting with the top node, or one of the bottom nodes.

#### cache_process.c
Contains all functions processing the cache instance, hits, misses, replacements, etc.

#### hex_to_bin.c
Converts hex char array to binary char array.

#### parse.c
Parses binary char array into integer tags and indexes.

