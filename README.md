# Curriculum Vitae

[![compile-pdf](https://github.com/leouieda/cv/workflows/compile-pdf/badge.svg?event=push)](https://github.com/leouieda/cv/actions)

This is the LaTeX source for my academic CV. Heavily inspired by (i.e. mostly stolen from) [@leouieda](https://github.com/leouieda/cv).

**Download** the latest compiled PDF:
[leighton_payne_cv.pdf](https://leightonpayne.com/leighton_payne_cv.pdf)

## Building

The PDF is built from LaTeX using[Tectonic](https://tectonic-typesetting.github.io), which can be installed via [conda](https://github.com/conda-forge/tectonic-feedstock).

* `make` builds the PDF
* `make show` opens the PDF on the default viewer
* `make clean` removes the built PDF and any other generated files

## Deploying

A PDF is compiled automatically by GitHub Actions with every commit to the
*main* branch and uploaded to the server hosting my website.

## License

All LaTeX template source code is distributed under the
[BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause).
