# Documentation for Learning Blocks
This documentation uses markdown files with Sphinx. For more info visit Sphinx andhttps://github.com/executablebooks/MyST-Parser 

## Create new documentation folder
To create a documentation folder, create a directory and run sphinx-quickstart.
```shell
mkdir my_new_library && cd $_
sphinx-quickstart
> Separate source and build directories (y/n) [n]: y
> Project name: My New Library
> Author name(s): My New Library
> Project release []: 1.0.0
```
extensions = ['myst_parser']
html_theme = "pydata_sphinx_theme"
html_theme = "furo"
html_theme = "sphinx_book_theme"