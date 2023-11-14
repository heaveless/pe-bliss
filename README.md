# PE Bliss

**Cross-Platform Portable Executable C++ Library**

Compatible with Windows and Linux (tested on MSVC++ 2008, 2010, GCC 4.4 on Linux). Currently tested on little-endian systems only and might not support big-endian ones.

Library has many usage samples and is well unit-tested.

*Library is free to use in both commertial and non-commertial projects. You can also modify and redistribute it. If you are using it, please, do not forget to specify the name or other copyright of PE Bliss somewhere in the description of your project.*

---

**A huge update is coming soon!** Possible new features of the future update:

- more high-level classes and functions to work with PE resources;

- high-level .NET PE parsing (metadata tables, signatures, resources);

- C++/CLI wrapper, which allows .NET developers to use the library in C# or VB.NET projects;

- more samples and tests;

- bugfixes.

---

**Current version: 1.0.0**

## Summary
- [x] Read 32- and 64-bit PE files (PE, PE+) for Windows, work similar with both formats
- [x] Create PE/PE+ binaries from scratch
- [x] Rebuild 32- and 64-bit PE files
- [x] Work with directories and headers
- [x] Convert addresses
- [x] Read and write PE sections
- [x] Read and write imports
- [x] Read and write exports (forwarders supported)
- [x] Read and write relocations
- [x] Read and write resources
- [x] Read and write TLS (including callbacks and raw data)
- [x] Read and write image config (including SE Handlers and Lock Prefix addresses)
- [x] Read basic .NET information
- [x] Read and write bound imports
- [x] Read exception directory (PE+ only)
- [x] Read debug directory and extended debug information
- [x] Calculate entropy
- [x] Change file alignment
- [x] Change base address
- [x] Work with DOS Stub and Rich overlay
- [x] High-level resource reading: bitmaps, icons, cursors, version info, string and message tables
- [x] High-level resource editing: bitmaps, icons, cursors, version info

Library doesn't use WinAPI and doesn't execute PE files, so it's safe to use it with suspicious binaries.

---
Forked from: [Pe Bliss](https://code.google.com/archive/p/portable-executable-library/)
