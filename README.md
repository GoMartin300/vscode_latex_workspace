[\\]: <> (
    cSpell:words TODOs
    )

# vscode_latex_workspace

A minimal workspace that sets up vs-code to become a pleasant Latex development environment. This template only takes care of Visual Studio Code, you still need to make sure you have a Latex distribution and create your own Latex structure.

## Getting started

Download this repository and open the folder in VS-code, not the folder containing this repository, but the repository itself, VS-code should be opened INSIDE the folder!
A pop up should appear that suggests the required extensions for installation, install these.

## spell checking

This setup uses cspell and does English language checks,
to stop cspell from giving a warning for a special word such as Ug-Three or ARMv6, add them in a list at the top of the file in which the warning is raised, e.g.:

```Latex
% cspell:words Ug-Three, ARMv6
```

## TODO highlighting

To prevent accidentally leaving visible TODOs in your document, this workspace highlights commented out TODOs.
Additionally you can list all the TODOs in your document by pressing the List TODOs button in the bottom bar of vscode.

### Custom markers

By following the instructions in the /.vscode/settings.json file, one can add custom markers, useful to diversify TODOs based on type, severity, work load, ...
