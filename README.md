# diabetes.page jitisi-meet

This the frontend of the videostreaming service of diabetes.page. It is a modified version of [`jitsi-meet`](https://github.com/jitsi/jitsi-meet).

## Installation

You will need to have `node` installed already.

```bash
npm install
make
dpkg-buildpackage -d -A -rfakeroot -us -uc -tc
```

This creates a bunch of  `.deb`, `.buildinfo` and `.changes` files in the parent directory of this repository. With these files, follow the instructions from our `jitsi-docker` repo README.

