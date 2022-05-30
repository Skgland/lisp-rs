# lisp-rs

A simple Lisp interpreter in Rust. The interpreter has been developed as a **teaching aid** to explain how Lisp interpreters work and how can they be implemented using the Rust programming language. 

## Dialect
The interpreter is based on a modified subset of [Scheme](https://en.wikipedia.org/wiki/Scheme_(programming_language)). More information about the dialect can be found at

- [Syntax](https://github.com/vishpat/lisp-rs/wiki/Lisp-Syntax)
- [Sample Programs](https://github.com/vishpat/lisp-rs/wiki/Sample-programs)

## Implementation

The interpreter has been implemented in three phases across different branches.

- Phase I: Complete interpreter and REPL implementation with support for basic data types (integers and boolean), variables, lambdas, and lambda calls (branch 0.0.1)
- Phase II: Support for advanced data types (string, float, and lists) and functional constructs (branch 0.0.2)
- Phase III: Support for closures and tail call optimization (branch 0.0.3)


For a detailed code-walkthrough about Phase-I implementation refer to the [docs](https://vishpat.github.io/lisp-rs). For code-walkthrough of all the phases, get the [e-book](https://www.amazon.com/dp/B0B1Z48DMT/ref=cm_sw_r_apan_QD16PC5E2EZWMKB1EZMK).

[![asciicast](https://asciinema.org/a/VVQQfGpp15a4BaoNgnEKIqqrr.svg)](https://asciinema.org/a/VVQQfGpp15a4BaoNgnEKIqqrr)
