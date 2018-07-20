# Dumb Obfuscator

The answer to "why shouldn't people put RSA computations everywhere in their programs?".

## Setup ##

With a working Internet connection, run `./setup.sh` and pray the Linux Gods
that nothing fails.
This will download LLVM and clang and then compile them.

## Building the Pass ##

Run `./build.sh`.

This will basically create `./build/` and run cmake on it.

## Testing the Pass ##

Run `./test.sh`.

This will compile `./test/test.c` into human-readable LLVM IR, run the pass on
it and show the final IR.

