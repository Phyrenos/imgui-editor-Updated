# 🔥 **Phyrenos/imgui-editor-Updated**

<div align="center">
<a href="https://Phyrenos/imgui-editor-Updated">
    <img width="100%" src=".github/images/logo.svg" alt="@Phyrenos/imgui-editor-Updated's logo">
</a>
</div>

---

## 🤔 **About the project**

Thanks to https://github.com/pers0na2dev/imgui-editor - Ive decided i want to update it a bit more, add more options
<br></br>
I've been planning on adding more options to it such as buttons, Children, Graphs. ETC ETC
<br></br>
Dont expect this to be updated constantly since i've got irl stuff to do aswell
---

## ⚡ **Compiling**


### Prerequisites

- IDE (either)
  - [Visual Studio](https://visualstudio.microsoft.com/)
  - [CLion](https://www.jetbrains.com/clion/)
- C++ Compiler (either)
  - [MinGW](https://sourceforge.net/projects/mingw/)
  - [MSVC](https://visualstudio.microsoft.com/downloads/)
- CMake [https://cmake.org/download/](https://cmake.org/download/)

### Installation

This guide assumes you have already installed the prerequisites.

1. Install [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812)
2. Clone the repo
   ```cmd
   git clone https://github.com/kaazedev/imgui-editor.git
    ```

#### Visual Studio

1. Open the project in Visual Studio using File > Open > CMake
2. Select the CMakeLists.txt file
3. Select the build type (Debug or Release)
4. Click "Configure"
5. Click "Generate"
6. Click "Open Project"
7. Build the project

#### CLion

1. Open the project by selecting the CMakeLists.txt file
2. Select the build type (Debug or Release)

### 📦 codegen-cli compilation
To generate c++ imgui code, you need to use the codegen-cli in this repository. 

To compile the application, install the latest version of the Golang compiler, 
open the "codegen-cli" folder in the terminal and write:

To run without compiling:
```cmd
go run main.go
```

To build an .exe file:
```cmd
go build -o codegen.exe
```

## 🎉 Was the Project helpful?

<a href="https://star-history.com/#Phyrenos/imgui-editor-Updated&Timeline"><img src="https://api.star-history.com/svg?repos=Phyrenos/imgui-editor-Updated&type=Timeline" alt="Star History Chart" height="386"></a>

Enjoy! 😃

---

## 🙏 **Acknowledgements**

* [omar (ocornut)](https://github.com/ocornut) - For creating ImGui

---

## ⚖️📝 **License and Changelog**

See the license in the '**[LICENSE](LICENSE)**' file.

Watch the changes in the '**[CHANGELOG.md](CHANGELOG.md)**' file.

---
