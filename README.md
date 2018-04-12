# Languages Hosted in Rust Working Groups

*This is an* **unofficial** *Rust group for communicating and coordinating around
the creation of programming languages and runtimes in the Rust programming
language.*

## General Purposes
- A central place of discussion to bring together runtime implementation ideas
  - a library of articles and papers relevant to implementing runtimes in Rust
  - a survey of the landscape: low-level descriptions of existing languages hosted in Rust
- To explore common safe-Rust abstractions for a reasonable variety of memory management approaches
  - arriving at mature abstractions and reference implementations, making Rust a great choice for building other languages on
- to track other core ecosystem components and features, such as futures, tokio, await/async, ensuring good integration

## Long term goals
- A language and runtime that is to Rust as CPython is to C
  - Deliberately creating a scripting/glue language is strategic.
    Languages such as Python, Ruby and PHP proliferate quickly into every
    domain and where they go, so goes their host language.
    This goal forms an important long-term part of the Rust ecosystem.
  - familiar, low friction, broad appeal, a new gateway to using Rust for many
  - an accessible implementation
  - low friction to implementing new and wrapping existing libraries for it in Rust
  - doesn’t compromise the memory safety of the host language
- Mature implementations of a variety of memory management runtimes wrapped in safe APIs
  - well documented
  - documenting where safe abstraction is not possible without unreasonable trade-offs
  - The ideal result is a common set of traits that could be implemented by
    allocators, GCs and managed data structures such that a change in a GC
    strategy could be as simple as swapping in a different crate and recompiling.

# Code of Conduct

All communication shall be conducted within the framework of the
[Rust Code of Conduct](https://www.rust-lang.org/en-US/conduct.html.)

# Legal

The Rust logo used inside the `rust-hosted-langs` logo is
[owned by Mozilla](https://www.rust-lang.org/en-US/legal.html)
and distributed under the terms of the Creative Commons Attribution license
(CC-BY). The use of the Rust logo as a part of the `rust-hosted-langs`
organization logo is under the terms granted as an *unofficial* and
*non-commercial* entity.

Unless otherwise specified in a `LICENSE` file, all `rust-hosted-langs`
content is available under the [Creative Commons Attribution license (CC-BY)](https://creativecommons.org/licenses/by/4.0/)

Unless otherwise specified in a `LICENSE`, copyrights in this organization
are retained by their contributors.
