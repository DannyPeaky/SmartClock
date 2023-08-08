# Smart Clock

Executable for [Smart Clock](https://www.smartclock.app)

## Automatic Installer

If installing on a Debian based system, you can set it up with one command:
```bash
bash -c "$(curl -fsSL https://www.smartclock.app/scripts/install.sh)"
```
It is recommended to only install on a clean install of DietPi.

## Install Dependencies

```bash
apt install -fy libnss3-dev zlib1g-dev fuse
```

## Deployment

To run:

```bash
chmod +x smartclock_{version}_{arch}.AppImage
./smartclock_{version}_{arch}.AppImage
```
