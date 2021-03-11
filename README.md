# Plateau GUI

Grapical File Browser for the Plateau project.

Built on top of the elementary os files app.

## Building, Testing, and Installation

You'll need the following dependencies:
* meson
* valac
* libcanberra-dev
* libcloudproviders-dev >= 0.3.0
* libdbus-glib-1-dev
* libgail-3-dev
* libgee-0.8-dev
* libglib2.0-dev
* libgranite-dev >= 5.3.0
* libgtk-3-dev
* libnotify-dev
* libpango1.0-dev
* libplank-dev
* libsqlite3-dev
* libunity-dev
* libzeitgeist-2.0-dev

Run `meson build` to configure the build environment. Change to the build directory and run `ninja` to build

```bash
meson build --prefix=/usr
cd build
ninja
```

To install, use `ninja install`, then execute with `io.elementary.plateau-gui`

```bash
sudo ninja install
io.elementary.plateau-gui
```
