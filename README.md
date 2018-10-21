# Anas_CV

Anas Abou Allaban's CV.

Base on the template 'simple-resume-cv':
**Website:**<br>
https://github.com/zachscrivena/simple-resume-cv

**Lead author:**<br>
Zach Scrivena (zachscrivena@gmail.com)

## Overview

The main XeLaTeX source file is `CV.tex`; the compiled document is `CV.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "CV.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
	- `xelatex "CV.tex"`
	(run multiple times to resolve cross-references if needed)

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.
