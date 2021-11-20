# UMD dissertation template
A simple template for dissertations following the style guidelines ([2021](https://gradschool.umd.edu/sites/gradschool.umd.edu/files/uploads/DissertationThesis/etd_style_guide_201708.pdf)).

With thanks to Dorothea F. Brosius and their [Latex template](https://terpconnect.umd.edu/~dbrosius/LatexThesisTemplate/).

## Compiling
Use `latexmk` on one of the `dissertation-*` files.
For example,
```
$ latexmk dissertation-electronic.tex
```
By default, running `latexmk` will compile the electronic version of the dissertation.
See the `latexmkrc` to configure defaults.
