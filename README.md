# git-remote-wiki
Use various wikis as a git remote, enabling offline wiki access

Why? Because wikis suck. Limited search, stupid WYSIWYG editors, no offline
access...

This is the start of a tool to make various wikis valid remotes for git.

Note that there's already a mediawiki git remote helper which works well if
your wiki is suitably configured - it needs api.php enabled. Since several of
the wikis I'd like to scrape are either not configured that way, or else use
another wiki system, such as confluence, I started this project.

Useful links:
https://www.kernel.org/pub/software/scm/git/docs/gitremote-helpers.html

https://rovaughn.github.io/2015-2-9.html

An existing mediawiki git remote helper: https://github.com/moy/Git-Mediawiki/wiki
