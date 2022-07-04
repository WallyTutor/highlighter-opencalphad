# OpenCALPHAD Syntax Highlighter

Basic syntax highlighting for OpenCALPHAD macros created with [Yeoman generator tool](https://yeoman.io/).

**NOTE:** this is a work in progress and partial matching *i.e. the interactive way of writing macros*. is not yet supported. For now this solves my needs, so I am in no hurry to add that sort of support simply because shortcuts represent a bad scripting practice. After you spend a few months without using the tool, good luck reading the macros at a fast pace. I strongly recommend any serious macro that is gonna be used in a real world project to be written with full syntax.

## Installation instructions

Simply copy the directory [ocm](ocm/) to your VS Code extensions directory.

Under most Linux distributions this can be done with a simple:

```bash
cp -avr $(pwd)/ocm/ ${HOME}/.vscode/extensions/

# or for development just link symbolically.
ln -s $(pwd)/ocm/ ${HOME}/.vscode/extensions/
```

For Windows users, you should have a directory called `.vscode` in your user profile.
