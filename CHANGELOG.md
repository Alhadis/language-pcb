Change Log
==========

This project honours [Semantic Versioning](http://semver.org).

[Staged]: https://github.com/Alhadis/language-pcb/compare/v1.0.1...HEAD


[Staged]
------------------------------------------------------------------------
* __Added;__ Auto-detection of files with `EESchema-DOCLIB` headers
* __Added:__ Support for KiCad 6's new project format (`.kicad_sch`)
* __Added:__ Support for `sym-lib-table` and `*.kicad_dru` files
* __Fixed:__ Broken auto-detection of `EESchema-LIBRARY` headers
* __Fixed:__ Broken highlighting of strings containing escape sequences


[v1.0.1]
------------------------------------------------------------------------
**July 29th, 2017**  
This patch updates Gerber's list of file extensions, refines its pattern
for matching file headers, and applies a hacky fix for Scheme files that
share the `.sch` extension.

[v1.0.1]: https://github.com/Alhadis/language-pcb/releases/tag/v1.0.1


[v1.0.0]
------------------------------------------------------------------------
**July 28th, 2017**  
Initial release. Adds syntax highlighting for KiCad and Gerber files.

[v1.0.0]: https://github.com/Alhadis/language-pcb/releases/tag/v1.0.0
