# vnc-desktop

Runs Ubuntu 14.04 in a docker container and exposes a full desktop over VNC.

### Run

```bash
docker run -p 5900:5900 -d ambroselli/vnc-desktop
open vnc://localhost:5900 # The password is: "pazzword"
```

### Notes
- The resolution is set to 1680x1050 pixel. This can be set by adding the following arguments after run: `-e SCREEN_WIDTH=1680 -e SCREEN_HEIGHT=1050`