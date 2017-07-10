# vnc-desktop

Runs Ubuntu 14.04 in a docker container and exposes a full desktop over VNC.

### Run

```bash
docker run -p 5900:5900 -d ambroselli/vnc-desktop
open vnc://localhost:5900 # The password is: "pazzword"
```