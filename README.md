# woke-snap
This repository contains [Snapcraft](https://snapcraft.io/docs/snapcraft-overview) build files for [woke](https://github.com/get-woke/woke).

To optionally permit _woke_ to access either `$HOME/.woke.yaml` or `$HOME/.config/woke.yaml`, connect the `dot-config-woke` snap interface:

```
snap connect woke:dot-config-woke
```

The snap can be manually built by cloning this project and running the _snapcraft_ command in its root.

The snap build is not endorsed by the woke project.
