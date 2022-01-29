<h1 align="center">Blender custom bpy</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/Leandro-Bertoluzzi/blender-custom?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/Leandro-Bertoluzzi/blender-custom?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Leandro-Bertoluzzi/blender-custom?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/Leandro-Bertoluzzi/blender-custom?color=56BEB8">
</p>

<hr>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/Leandro-Bertoluzzi" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This project shows how the source code of Blender can be modified to compile a personalized version of the software, and even build it as a Python package.
In order to access and modify freely the Blender source code, a [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks) of the official Github repo is used as a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## :rocket: Technologies ##

The following tools were used in this project:

- [Blender](https://www.blender.org/)
- [Visual Studio](https://visualstudio.microsoft.com/es/)
- [CMake](https://cmake.org/)
- [Git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

## :white_check_mark: Requirements ##

In order to build Blender from source code, you'll need to install development tools according to your OS:
- [Linux](https://wiki.blender.org/wiki/Building_Blender/Linux)
- [Windows](https://wiki.blender.org/wiki/Building_Blender/Windows#Quick_Setup)
- [MacOS](https://wiki.blender.org/wiki/Building_Blender/Mac#Quick_Setup)

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/Leandro-Bertoluzzi/blender-custom

# Access
$ cd blender-custom

# Init and update the submodules
$ git submodule update --init --recursive
```

In order to build Blender, follow the instructions in the official docs, corresponding to your OS:

- [Linux](https://wiki.blender.org/wiki/Building_Blender/Linux)
- [Windows](https://wiki.blender.org/wiki/Building_Blender/Windows)
- [MacOS](https://wiki.blender.org/wiki/Building_Blender/Mac)

If you want to build Blender as a Python package, follow the next guide:
- [Build Blender as a Python module](https://wiki.blender.org/wiki/Building_Blender/Other/BlenderAsPyModule)

## :memo: License ##

This project is under GNU public license. For more details, see the [LICENSE](LICENSE) file.


Made with :heart: by <a href="https://github.com/Leandro-Bertoluzzi" target="_blank">Leandro Bertoluzzi</a>

<a href="#top">Back to top</a>
