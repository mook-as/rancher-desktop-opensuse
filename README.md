# tucows-opensuse

This contains scripts to build an OpenSUSE distribution for Rancher Desktop.

## Usage

This is built using `docker`:
```sh
make TYPE=qcow2 # For Linux/darwin hosts
make TYPE=tar.xz # For WSL hosts
```

Note that currently this builds for the native architecture; cross-builds are
planned but not implemented.
