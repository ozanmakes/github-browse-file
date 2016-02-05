github-browse-file
==================

View the file you're editing in Emacs on GitHub.

### Installation:

Available as a package in [Marmalade](https://marmalade-repo.org/) and [MELPA](http://melpa.org/).

`M-x package-install github-browse-file`

You can change some defaults using `M-x customize-group github-browse-file`

### Usage:
Call `github-browse-file` (for the git blob) or `github-browse-file-blame`
(for the git blame) to view current file on GitHub. With a prefix argument
(`C-u`), you can force them to use the "master" branch.

`github-browse-commit` can be used to link to the current commit.

### Contributors
* [Charles Comstock](https://github.com/dgtized)
* [Justin Talbott](https://github.com/waymondo)
* [William Roe](https://github.com/wjlroe)
* [Yukihiro Hara](https://github.com/yukihr)
