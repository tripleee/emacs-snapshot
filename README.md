# `emacs-snapshot` for Travis

This fork of [`emacs-mirror`](https://github.com/emacs-mirror/emacs)
contains some adaptations to make it palatable for Travis.
The script which performs this is in a separate GitHub repository;
https://github.com/tripleee/emacs-snapshot-travis

This creates a simple monolithic build from the upstream sources.
No fancy shmancy partitioning into separate packages for `emacsen-common`
etc -- just a single big ole package with the results from building Emacs.

<!-- # Not true right now
In order to make this more palatable for Travis, any reference to
the six characters s-e-t-u-i-d are blotted out by simple lexical
substitution in this fork.

This makes for some amusing diffs, but it gets old pretty fast.
-->

The intent is to make this a weekly or even daily build, but as of now,
this is in the earliest stages of prototyping.
