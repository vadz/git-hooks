Git Hooks
=========

This repository is just a collection of generally useful git hooks.

update-no-exec-text-files
-------------------------

This is an update, i.e. server-side, hook which can be used to block pushing
the changes to text files making them executable. This is especially useful
with Cygwin git, as file permissions under Cygwin often change accidentally.
