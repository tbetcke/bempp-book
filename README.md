# The Bempp Handbook

The Handbook for Bempp

## Usage

### Building the book

If you'd like to develop on and build the The Bempp Handbook book, you should:

- Clone this repository and run
- Run `pip install requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `The Bempp Handbook/_build/` directory
- Run `jupyter-book build The Bempp Handbook/`

A fully-rendered HTML version of the book will be built in `The Bempp Handbook/_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. A GitHub actions workflow has been created that automatically builds and pushes the book to this branch on a push or pull request to master.

If you wish to disable this automation, you may remove the GitHub actions workflow and build the book manually by:

- Navigating to your local build; and running,
- `ghp-import -n -p -f The Bempp Handbook/_build/html`

This will automatically push your build to the `gh-pages` branch. More information on this hosting process can be found [here](https://jupyterbook.org/publish/gh-pages.html#manually-host-your-book-with-github-pages).

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/tbetcke/the_bempp_handbook/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
