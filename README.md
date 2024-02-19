# gomod-multiple-modules

The repository contains a top-level two submodules.

The spam-module is versioned separately (see the git tags). There's
no tag for eggs-module - Cachito should give it a `v0.0.0-*` [pseudo-version][pseudo-version].

The submodules depend on different versions of rsc.io/quote - Cachito should download
and report both.

[pseudo-version]: https://go.dev/ref/mod#pseudo-versions
