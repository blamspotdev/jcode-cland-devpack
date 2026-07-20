# C/C++ Dev Pack for JCode

Language support for C and C++ in [JCode](https://github.com/blamspotdev/j-code-android), the
native Android IDE.

## What's included

- **Syntax coloring** for C (`.c`, `.h`) and C++ (`.cpp`, `.cc`, `.cxx`, `.hpp`, `.hh`, `.hxx`, `.ipp`)
- **Completions and snippet helpers** — loops, classes, header guards, RAII patterns, and more
- **Formatter** — runs `clang-format` when available, with sensible basic rules as fallback

## Toolchain integration

Installing the pack automatically resolves:

- the **C/C++ toolchain** (clang, clangd, lldb, gdb) from the Toolchains manager
- the **clangd** language server for code intelligence

Suggested (manual install): **lldb-dap** for debugging C/C++ with breakpoints and stepping.

## Building

Pack with [j-code-make-tools](https://github.com/blamspotdev/j-code-make-tools):

```sh
jext pack . -o dist/
```

## License

MIT — see [LICENSE](LICENSE).
