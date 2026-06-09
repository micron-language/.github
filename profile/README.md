# Welcome to the Micron Programming Language

Micron is a systems programming language with
a syntax similar to Oberon+ and the flexibility of C. It is designed to
be useful for both, low-level operating system and driver programming usually
accomplished with assembler and C, but also high-level application programming,
optionally with automatic memory management, controlled by language levels.

The name "Micron" is an abbreviation of "MicroOberon".


See [The Micron Programming Language Specification](https://github.com/micron-language/specification/blob/master/The_Micron_Programming_Language_Specification.adoc) for more information.


Micron translates to defined intermediate language. The Micron Intermediate Languae (MIL) uses a
subset of the ECMA-335 Common Intermediate Language (CIL) without
managed types, and with manual memory management, and extended by
explicit control-flow syntax. Because of the latter no explicit branch
instructions are required, and different types of analyses, as well as
translations to high-level languages like C or lower-level
representations like CIL or LLVM IR are straight-forward.

See [The Micron Intermediate Language Specification](https://github.com/micron-language/specification/blob/master/The_Micron_Intermediate_Language_Specification.adoc) for more information.


