# woke-snap
This repository contains [Snapcraft](https://snapcraft.io/docs/snapcraft-overview) build files for [woke](https://github.com/get-woke/woke).

The following home directory locations are supported for woke's configuration file:

- `$HOME/.config/woke.yaml`
- `$HOME/.config/woke.yml`
- `$HOME/.woke.yaml`
- `$HOME/.woke.yml`

Remote files can be accessed after connecting the network interface:

`snap connect woke:network`

If your project directory is on another storage device, mounted via _/media_, _/run/media_ or _/mnt_, you will need to connect the removable-media interface to permit woke access:

`snap connect woke:removable-media`

The snap can be manually built by cloning this project and running the _snapcraft_ command in its root.

The snap build is not endorsed by the woke project.
