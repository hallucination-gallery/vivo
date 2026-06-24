# godot-cpp template
This repository serves as a quickstart template for GDExtension development with Godot 4.0+.

## Contents
* Preconfigured source files for C++ development of the GDExtension ([src/](./src/))
* An empty Godot project in [project/](./project), to test the GDExtension
* godot-cpp as a submodule (`godot-cpp/`)
* GitHub Issues template ([.github/ISSUE_TEMPLATE.yml](./.github/ISSUE_TEMPLATE.yml))
* GitHub CI/CD workflows to publish your library packages when creating a release ([.github/workflows/builds.yml](./.github/workflows/builds.yml))
* An SConstruct file with various functions, such as boilerplate for [Adding documentation](https://docs.godotengine.org/en/stable/tutorials/scripting/cpp/gdextension_docs_system.html)

## Development
This project was built using the official [Godot Engine C++ Template](https://github.com/godotengine/godot-cpp-template)

To contribute to this project, perform these steps after setting up your toolchain (as per [the official Godot compilation guidelines]())

1. Clone the repository to your local computer
2. Initialize the godot-cpp git submodule via `git submodule update --init`
3. Perform a first compilation and configure your language server via `scons compiledb=yes`
4. Test by opening the [example project](./project) in Godot and running the example scene.
