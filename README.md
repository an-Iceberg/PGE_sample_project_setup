# **olc::PixelGameEngine Sample Project for VSCode**

## A fully set up project structure with debug and release commands for Visual Studio Code

All you need to do is clone this repo and start coding in the `src` directory.

Don't forget to change or delete this readme and remove the `.gitignore` files in the build folders if you don't plan on publishing this project anywhere. They're only there because github ignores empty folders. Also add a folder named `graphics` or `sprites` if you want to add any sprites or decals to your program. The `docs` folder is only there if you want to also take advantage of github pages to publish your project to the web using WASM, otherwise it can be removed as well.

I try to keep the olc::PGE header file updated with the latest release but it isn't guaranteed to be the case.
It's best if you use your own copy.

---
## Dependencies

- [olc::PixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine)
  > Only the header file `olcPixelGameEngine.h` is required. Place it into the `include` folder.

- A C++ compiler that comes with libaries for OpenGL.
  > I recommend [this guide](https://www.youtube.com/watch?v=0HD0pqVtsmw) that shows you how to download and install the MinGW toolchain on windows using MSYS2.

- *optional:* [emscripten](https://emscripten.org/)
  > Check out [this video](https://www.youtube.com/watch?v=MrI5kkVY6zk) by the one and only javidx9 himself on how to install emscripten on your machine.
  (I couldn't figure out how to add VSCode build commands for emscripten)
