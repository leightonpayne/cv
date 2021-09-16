# Curriculum Vitae

This is the LaTeX source for my academic CV. Heavily inspired by [leouieda/cv](https://github.com/leouieda/cv).

**Download** the latest compiled PDF:
[leighton_payne_cv.pdf](https://leightonpayne.com/leighton_payne_cv.pdf)

## Building

The PDF is built from LaTeX using [Tectonic](https://tectonic-typesetting.github.io). I like Tectonic because it can be install via [conda](https://github.com/conda-forge/tectonic-feedstock) and it only downloads the packages being used – avoiding the need to install a full LaTeX system (which can be huge).

* `make` builds the PDF
* `make show` opens the PDF on the default viewer
* `make clean` removes the built PDF and any other generated files

## Deploying

A PDF is compiled automatically by GitHub Actions with every commit to the
*master* branch and uploaded to the server hosting my [website](https://leightonpayne.com) where it can be [downloaded](https://leightonpayne.com/leighton_payne_cv.pdf).

## License

All LaTeX template source code is distributed under the
[BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause).
