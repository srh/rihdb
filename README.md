[![Build Status](https://travis-ci.org/srh/nihdb.svg?branch=master)](https://travis-ci.org/srh/nihdb)

# NIHdb

A simple single-threaded KV store, with read/write/range-get operations.

A work in progress.  Run "cargo test".

Its license right now is MIT.

Right now this is a very simple LSM-tree storage library.  Here's why
you shouldn't use it:

  - It has no crash resistance
  - It doesn't use bloom filters
  - It doesn't use compression
  - It has some inefficient implementations
  - The file format won't be backwards compatible

Here's why you should use it:

  - It's simple and correct
