# Curriculum Vitae

This is the LaTeX source for my academic CV. 

Heavily inspired by [leouieda/cv](https://github.com/leouieda/cv).

<a href="https://github.com/leightonpayne/cv/" alt="Last update"><img src="https://img.shields.io/github/last-commit/leightonpayne/cv?label=last%20update" /></a>

## Building

The PDF is built from LaTeX using [Tectonic](https://tectonic-typesetting.github.io). I like Tectonic because it can be installed via [conda](https://github.com/conda-forge/tectonic-feedstock) and it only downloads the LaTeX packages being used – avoiding the need to install a full LaTeX system (which can be huge).

* `make` builds the PDF
* `make show` opens the PDF
* `make clean` removes the PDF and intermediate files

## Deploying

A PDF is compiled automatically using GitHub Actions when a new commit gets pushed. The compiled PDF is then uploaded to the server hosting my [website](https://leightonpayne.com) where it can be [downloaded](https://leightonpayne.com/leighton_payne_cv.pdf).

## License

