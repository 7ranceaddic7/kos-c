# Changelog

## v0.3.0.0 (2017-04-07)

### Builtins

- Changed interface to staging functionality.
- Added `PrintAt` function for printing at specific screen locations.

### Compiler

- Added support for inline kOS script code.

### Other

- Updated documentation.
- Added test for prelude library.

## v0.2.0.1 (2017-04-04)

### Builtins

- Added missing `Vessel` constructor.

## v0.2.0.0 (2017-04-04)

### Compiler

- Global variables are now generated in topological order of their dependency graph.
- Disallowed circular inheritance.
- Added check that main function exists before trying to generate code.

### Builtins

- Added missing constructor `Body(String name)` in order to get references to bodies in kOS-C.
- Added rudimentary interface to time warping.

### Other Parts of Prelude

- Added function for launching into inclined orbit.

## v0.1.0.0 (2017-03-20)

Initial Release
