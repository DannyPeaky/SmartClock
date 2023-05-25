# Smart Clock

Executable for [Smart Clock](https://www.smartclock.app)

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
  smartclock-power -p on   # Turn on the display
  smartclock-power -p off  # Turn off the display
  smartclock-power         # Toggle display
```

### smartclock-remote

A slightly modified version of thorsten-gehrig's alexa-remote-control.

```bash
  Usage of smartclock-remote:
      -id string
          Smart Clock User ID
      -cmd string
        Alexa Command [login, devices, notifications, queue]
      -deviceSerialNumber string
          The Device Serial Number (Required for queue)
      -deviceType string
          The Device Type (Required for queue)
      -token string
          Alexa Token (Required for login)
```

An amazon refresh token can be obtained using Apollon77's alexa-cookie.

### smartclock-updater

Downloads the version of smartclock provided and installs.

```bash
  smartclock-updater {version}
```

## Acknowledgements

- [thorsten-gehrig/alexa-remote-control](https://github.com/thorsten-gehrig/alexa-remote-control)
- [Apollon77/alexa-cookie](https://github.com/Apollon77/alexa-cookie)
