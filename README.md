# Basement Windows tools layer

This layer builds upon the [Basement
layer](https://github.com/BobBuildTool/basement) and provides various pre-built
tools for Windows.

# How to use

You need to add at least the `basement` and `basement-win32-bin` layers to your
project. To do so add a `layers` entry to `config.yaml`:

    bobMinimumVersion: "0.20"
    layers:
        - basement-win32-bin
        - basement

and then add the repositories as submodules to your project:

    $ git submodule add https://github.com/BobBuildTool/basement-win32-bin.git layers/basement-win32-bin
    $ git submodule add https://github.com/BobBuildTool/basement.git layers/basement

