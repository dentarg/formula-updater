Formula Updater
===============

Automatically update a [Homebrew][5] [formula][4] to the latest version
found on GitHub. Just give it the formula name:

    $ ./formula_updater svtplay-dl

Prerequisites:
* The formula is hosted on GitHub and tags new versions in a sane way
* You have forked [mxcl/homebrew][3]
* Your username on GitHub is the same as `$USER`

Note: I have only [tested][1] this script with [svtplay-dl][2].

[1]: https://github.com/mxcl/homebrew/pull/17355
[2]: https://github.com/spaam/svtplay-dl
[3]: https://github.com/mxcl/homebrew
[4]: https://github.com/mxcl/homebrew/wiki/Formula-Cookbook
[5]: http://mxcl.github.com/homebrew/
