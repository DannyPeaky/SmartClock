# Smart Clock

Executable for [Smart Clock](https://www.smart-clock.co.uk)

## Usage

Download the .deb from the Releases page then run

```bash
dpkg -i smartclock_{version}_{arch}.deb; apt install -fy
```

as root to install and get dependencies.

(replace {version} and {arch} with your version and arch)

## Included Binaries

Once installed you will have access to 4 binaries.

### smartclock

The main program

### smartclock-power

```bash
  smartclock-power on   #Turn on the display
  smartclock-power off  #Turn off the display
```

### smartclock-remote

A slightly modified version of thorsten-gehrig's alexa-remote-control.

```bash
  smartclock-remote {userid} --rt {amazon refresh token} {command}
```

An amazon refresh token can be obtained using Apollon77's alexa-cookie.

### smartclock-updater

Downloads the version of smartclock provided and installs.

```bash
  smartclock-updater 3.1.1
```

## Acknowledgements

- [thorsten-gehrig/alexa-remote-control](https://github.com/thorsten-gehrig/alexa-remote-control)
- [Apollon77/alexa-cookie](https://github.com/Apollon77/alexa-cookie)
