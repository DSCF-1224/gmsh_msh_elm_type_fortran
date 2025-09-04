# gmsh_msh_elm_type_fortran

Fortran module for reading `elm-type` in the [Gmsh][GmshReferenceManualTop] [MSH file format][GmshReferenceManualMshFileFormat].

`elm-type` is used in [Gmsh][GmshReferenceManualTop] [MSH file format][GmshReferenceManualMshFileFormat] version [1][GmshReferenceManualMsh1] and [2][GmshReferenceManualMsh2].

## Requirements

This module requires a Fortran compiler with the following features:

- Fortran 2008 or later standard
  - User-defined derived-type I/O (defined I/O) support for formatted READ operations
- ISO C binding (`iso_c_binding` intrinsic module)
  - `c_int` type for C interoperability

## Documentation

Documentation is available at [https://dscf-1224.github.io/gmsh_msh_elm_type_fortran/](https://dscf-1224.github.io/gmsh_msh_elm_type_fortran/).

## Dependents

- [gmsh_msh1_reader_fortran](https://github.com/DSCF-1224/gmsh_msh1_reader_fortran)

[GmshReferenceManualTop]: https://gmsh.info/doc/texinfo/gmsh.html
[GmshReferenceManualMshFileFormat]: https://gmsh.info/doc/texinfo/gmsh.html#MSH-file-format
[GmshReferenceManualMsh1]: https://gmsh.info/doc/texinfo/gmsh.html#MSH-file-format-version-1-_0028Legacy_0029
[GmshReferenceManualMsh2]: https://gmsh.info/doc/texinfo/gmsh.html#MSH-file-format-version-2-_0028Legacy_0029

<!-- EOF -->
