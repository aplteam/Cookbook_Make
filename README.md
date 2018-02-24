# Cookbook Make

This is a Dyalog APL program that takes markdown files as input and compiles HTML files as output.

The associated INI file must point to the home directory of the cookbook folder. It's supposed to host, among other stuff, these two directories:

`manuscript\`

: Holds all the markdown files defining the chapters and appendices.

`HTML\`

: All the HTML files will be written to this directory

: This directory must also host the directories `CSS\`, `Images\` and `JavaScript\`.

If all goes well then the program performs all its actions and `⎕OFF`s under a runtime exe.

When running under development no `⎕OFF` is executed.

In case something goes wrong an error is signalled.