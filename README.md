## Last Updated

* 2023-01-02

## About

This repository contains example processes / protocols of a (Higher Order) Session $\pi$-calculus specification implemented in Maude as seen in Restrepo et al. [1], as implemented [here](https://gitlab.com/calrare1/session-types/-/tree/master/hospi).

## Prerequisites

1. You need to install [Maude](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).

   Follow this [link](http://maude.cs.illinois.edu/w/index.php/Maude_download_and_installation) for installation instructions.

   Make sure the Maude executable is accessible from the root folder this repository is cloned to. We recommend putting the the Maude executable's location in your PATH environment variable. Note, that you need all the files Maude comes along with, not just the executable.

2. Clone this repository locally.

3. You need a good understanding of (higher order) session-typed $\pi$-calculus.

   See this [tutorial](TODO: Put link) for a full walkthrough. The tutorial assumes the reader has completed at least 2 years of their Bachelor's program, though it's possible to read it without such knowledge, if the reader is self-sufficient to pursue concepts unfamiliar to them.

## Examples

* The `basic.maude` files in both the `spi` and `hospi` directories contain annotatied basic examples showcasing how one would use the constructs, as well as how they are typed.
* The `protocol.maude` files in both the `spi` and `hospi` directories contain examples showing more complex interactions of processes, as well as how they are typed. See [tutorial](TODO: Put link / section) for the corresponding sequence diagrams describing these protocols.

## Execution

```bash
maude spi/examples/<target>.maude
maude hospi/examples/<target>.mauade
```

Where:

```
<target> ::= basic
```

## References 

TODO: Put accents

[1] Carlos Alberto Ramirez Restrepo and Jorge A. Perez. Executable semantics and type checking for session-based concurrency in maude. In Rewriting Logic and Its Applications, pages 230–250. Springer International Publishing, 2022.