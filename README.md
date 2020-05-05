# vscode_latex_workspace

A minimal workspace that sets up vs-code to become a pleasant Latex development environment. This template only takes care of Visual Studio Code, you still need to make sure you have a Latex distribution and creat your own Latex structure.

## Getting started

Download this repository and open the folder in VS-code, not the folder containing this repository, but the repository itself, VS-code should be opened INSIDE the folder!
A pop up should appear that suggests the required extensions for installation, install these.

## spell checking

This setup uses cspell and does English language checks,
to stop cspell from giving a warning for a special word such as Ug-Three or ARMv6, add them in a list at the top of the file in which the warning is raised, e.g.:

```Latex
% cspell:words Ug-Three, ARMv6
```

## TODO's

To prevent accidentally leaving visible TODO's in your document, this workspace highlights commented out TODO's.
Additionally you can list all the todo's in your document by pressing the List TODOs button in the bottom bar of vscode.
