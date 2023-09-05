# TJALib
A very W.I.P library to work with .tja files (for Taikojiro and others). The main focus is primarily to read tja files and support things like branching, dan courses etc. As a future goal, it would also be great to find a way to reverse this process as well.

## Project goals
- [ ] Read chart metadata
- [ ] Read basic tja charts
- [ ] Read charts with 2P alterations
- [ ] Read charts with branches

## Building from source
Building TJALib from source should be relatively straight-forward and easy. Start by cloning the repository by using:
```bash
git clone https://github.com/Jaika1/tjalib.git
```

From here, you should be ready to build! You could likely create a build directory and use `cmake ..` from the command line with minimal arguments, although I have yet to test such since I have been using my IDE of choice (Visual Studio Code with the "CMake Tools" extension) to do most of this configuration for me and it has been working no problem. I have also only tested builds on Windows so far, so do let me know of any issues that may arise when attempting to compile on other platforms.