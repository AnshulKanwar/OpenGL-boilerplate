# OpenGL boilerplate code

For macOS

## Compilation

```shell
clang++ -I /opt/homebrew/include -L /opt/homebrew/Cellar/glfw/3.3.6/lib/ -lglfw -framework opengl -o main main.cpp
```
or in vscode compile using <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>B</kbd>

## Provides

- Boilerplate code common to all OpenGL applications
- Code for creating a window
- A shader helper library
- A Camera
- A function to load textures
- [stb_image.h](https://github.com/nothings/stb/blob/master/stb_image.h)
