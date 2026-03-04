# Prebuilt GCC compiler toolchains for x86_64 Linux

## [Releases](https://github.com/binarylandia/build_gcc/releases)

Builds self-contained GCC installations on manylinux2014 (glibc 2.17) for maximum compatibility with older Linux distributions. Each release includes GCC with C, C++, and Fortran support, plus binutils, autoconf, automake, libtool, m4, and make.

Targets x86_64 Linux hosts.

## Features

- Statically linked against libgcc and libstdc++ for portability
- Supports C, C++, Fortran, and LTO
- Gold linker with plugin support
- Bootstrap build with LTO optimization
- Multiple GCC versions built in parallel

## Use Cases

- CI/CD pipelines requiring specific GCC versions
- Building portable Linux binaries on modern systems
- Reproducible builds with pinned compiler versions
- Cross-platform development with consistent toolchain

## Keywords

prebuilt gcc, gcc binary, gcc download, linux compiler, portable gcc, static gcc, manylinux compiler, glibc 2.17 gcc, self-contained gcc toolchain, gcc fortran, gcc lto
