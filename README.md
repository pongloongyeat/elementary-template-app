# Template

<!-- data/screenshot.png here -->

## Building and Installation

You'll need the following dependencies:

- libgranite-dev
- libgtk-3-dev
- meson
- valac

Run `meson build` to configure the build environment. Change to the build directory and run `ninja` to build

```bash
meson build --prefix=/usr
cd build
ninja
```

To install, use `ninja install`, then execute with `com.github.pongloongyeat.elementary-template-app`

```bash
ninja install
com.github.pongloongyeat.elementary-template-app
```