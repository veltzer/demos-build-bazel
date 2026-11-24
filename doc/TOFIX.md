# TOFIX

Findings from a code scan on 2026-10-04.

## High

- `README.md:2` - the repo claims to hold "Demos for the Bazel build system" but contains no Bazel content at all (no `MODULE.bazel`, `BUILD.bazel`, or sources; 26 commits are all fleet config); add a first demo (e.g. a `cc_binary` + `cc_library` hello world under `src/hello/` with `MODULE.bazel`) and a processor that runs `bazel build //...` on it, or delete the repo.
