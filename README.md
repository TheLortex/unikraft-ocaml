# ocaml for Unikraft

This is the port of ocaml for Unikraft as external library.

Please refer to the [`README.md`](https://github.com/unikraft/unikraft/tree/staging/README.md)
as well as the documentation in the [`doc/`](https://github.com/unikraft/unikraft/tree/staging/doc/)
subdirectory of the main unikraft repository.

## what

This _package_ has Unikraft rules to build libasmrun.a, which is suitable to 
link with an OCaml program generated with `-output-obj`, as long as the 
architecture matches.

Requires the use of pthread-embedded and newlib.
