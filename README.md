# Smart Clock

Executable for [Smart Clock](https://www.smart-clock.co.uk)

## Dependencies

Run (as sudo) to install dependencies:

```
apt install -fy libgtk2.0-0 libgtk-3-0 libgbm-dev \
libnotify-dev libgconf-2-4 libnss3 libxss1 libasound2 \
libxtst6 xauth xvfb libnss3-dev libgdk-pixbuf2.0-dev \
libgtk-3-dev libxss-dev fuse libfuse2 jq
```

## Deployment

To run:

```bash
chmod +x SmartClock-{version}-{arch}.AppImage
./SmartClock-{version}-{arch}.AppImage
```

## Acknowledgements

- [thorsten-gehrig/alexa-remote-control](https://github.com/thorsten-gehrig/alexa-remote-control)
- [Apollon77/alexa-cookie](https://github.com/Apollon77/alexa-cookie)
