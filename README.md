<div align="center">
  <h1>Fusion</h1>
  <p>A next-generation mod menu for Geometry Dash.</p>
  <p><strong>Fork of Eclipse Menu · Geometry Dash 2.2091 · Geode v6</strong></p>
</div>

Fusion is an open-source Geometry Dash mod menu based on [Eclipse Menu](https://github.com/EclipseMenu/EclipseMenu). It retains the upstream feature set and architecture while developing under the Fusion name.

> **Compatibility status:** The 2.2091 port targets the Geode v6.0.0-alpha.1 SDK. Geode v6 is an experimental developer release, so this branch is experimental too. A successful build does not by itself guarantee runtime stability.

## Features

- 100+ gameplay, creator, visual and utility options inherited from Eclipse
- StartPos Switcher with Smart StartPos
- Show Hitboxes and Show Trajectory
- Internal Recorder and Replay Bot
- Customizable labels, keybinds and themes
- Tabbed, Panel and Sidebar layouts
- Windows, macOS, Android and iOS build targets

The Internal Recorder requires the optional [FFmpeg API](https://geode-sdk.org/mods/eclipse.ffmpeg-api) mod.

## Build

The GitHub Actions workflow builds Fusion for Windows, macOS, Android32, Android64 and iOS using the Geode SDK version declared in `mod.json`.

For a local build, install CMake, a C++23 compiler, Git, Geode CLI and the matching Geode SDK, then run:

```bash
cmake -B build -DCMAKE_BUILD_TYPE=RelWithDebInfo
cmake --build build --config RelWithDebInfo
```

## Upstream and credits

Fusion is derived from [Eclipse Menu](https://github.com/EclipseMenu/EclipseMenu). The original Eclipse developers and contributors retain credit for their work:

- [ninXout](https://github.com/ninXout)
- [prevter](https://github.com/prevter)
- [maxnut](https://github.com/maxnut)
- [Firee](https://github.com/FireMario211)
- [SpaghettDev](https://github.com/SpaghettDev)
- [Eclipse Menu contributors](https://github.com/EclipseMenu/EclipseMenu/graphs/contributors)

Additional upstream contributors and testers are credited in the original project history and documentation.

## License

Fusion retains the upstream **Eclipse Public License 2.0**. See [LICENSE.md](LICENSE.md) for the complete license terms.
