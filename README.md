# UMD dissertation template
A simple template for dissertations following the style guidelines ([2021](https://gradschool.umd.edu/sites/gradschool.umd.edu/files/uploads/DissertationThesis/etd_style_guide_201708.pdf)).

*Note*: The style guidelines have since been updated. I could not find a changelog so I don't know what has changed. Please verify that the template still abides by the graduate school's guidelines before using. Updates to the template are welcome, if necessary (or let me know they are not!)

With thanks to Dorothea F. Brosius and their [Latex template](https://terpconnect.umd.edu/~dbrosius/LatexThesisTemplate/).

## Compiling
Use `latexmk` on one of the `dissertation-*` files.
For example,
```
$ latexmk dissertation-electronic.tex
```
By default, running `latexmk` will compile the electronic version of the dissertation.
See the `latexmkrc` to configure defaults.
