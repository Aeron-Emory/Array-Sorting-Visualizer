# Array Sorting Visualizer

> **Originally from:** [dipesh-m/Sorting-Visualizer](https://github.com/dipesh-m/Sorting-Visualizer)  
> *(Did not fork as I wanted it to be a standalone solution.)*

## What's Changed?

This project functions exactly like the original, with the **same controls** and **features**.  
However, the code has been **updated from SDL2 to SDL3**.

**Note:** No `.exe` is provided in this repository since the original repo already has an **SDL2 executable** in its releases, which works fine.  
This repository is purely for the **updated SDL3 code**.

## How to Use

1. **Clone this repository** to your local machine.
2. **Install [Visual Studio](https://visualstudio.microsoft.com/)** (if not already installed).
3. **Open the solution file** (`.sln`).
4. **Click "Run"** and it should work, **provided you have added the SDL3 library in the linker**.

get the lib from: 🔗 [**SDL3-devel-3.2.8-VC.zip**](https://github.com/libsdl-org/SDL/releases/download/release-3.2.8/SDL3-devel-3.2.8-VC.zip)

extract it
find the directory
SDL3-3.2.8\lib\(x64/x86/arm64)
copy the directory based on your machine
paste it in the SDL3 folder inside the Sort Array Folder

## Notes

- Make sure the **SDL3 library** is correctly linked in **Visual Studio**.
- If you encounter issues, double-check your **linker settings** and **dependencies**.
