# bevity

A tool to use Unity as an editor for the Bevy rust game engine.

<!-- TODO: Write the rest of this -->

## Setup

1. Ensure that a Unity editor above 2019.4 is installed.
2. Clone this repo.
3. Run `cargo build` in the repo root (this compiles and caches your rust deps).

### Unity Example Project

This repo provides an example Unity project in the `unity` directory. This project is used to test bevity and is not required to use bevity in your own project.

> [!WARNING]\
> These instructions may change as the bevity project matures.

1. Open or create a project in Unity.
2. Add the `sdk` folder from this repo as a local Package in the Unity project.
   1. Using your computer’s file manager (for example the Windows File Explorer or the macOS Finder), navigate to the `sdk` directory.
   2. Open the Unity Package Manager window and follow the [instructions for installing a local package](https://docs.unity3d.com/Manual/upm-ui-local.html).
   3. The new package appears in the Package Manager window and in the Project window, where you can view and modify the package contents.

You should now be able to use the bevity package in your Unity project.

## Usage

<!-- TODO: Write the rest of this -->