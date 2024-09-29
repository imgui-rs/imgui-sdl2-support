# imgui-sdl2-support

This crate provides an SDL2 based backend platform for imgui-rs.

A backend platform handles window/input device events and manages their
state.

## Using the library

There are three things you need to do to use this library correctly:

1. Initialize a `SdlPlatform` instance
2. Pass events to the platform (every frame)
3. Call frame preparation callback (every frame)

For a complete example, take a look at the imgui-rs' GitHub repository.
