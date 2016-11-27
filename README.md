# Sublime Text plugin: HgCommitMsg

Basic port of [GitCommitMsg](https://github.com/cbumgard/GitCommitMsg) to Mercurial, only tested on OSX

Shows the hg commit history for one or more lines of code.
Essentially it performs a ```hg annotate``` on the selected line(s) of code,
and then performs a ```hg log``` on the resulting commit(s).

Inspired by ["Every line of code is always documented"](http://mislav.uniqpath.com/2014/02/hidden-documentation/)

## Usage

 * Supports Sublime Text 2 & Sublime Text 3
 * Mac: Default keybinding is __Command+Shift+m__
 * Linux: Default keybinding is __Alt+Shift+m__
 * Assumes ```hg``` is installed and in the ```$PATH```

