# downloads.notengobattery.com

Package feeds and images for NoTengoBattery's OpenWrt builds, served through GitHub Pages.

Layout follows the OpenWrt download tree under `projects/<dist>-<version>/`:

- `targets/<target>/<subtarget>/` — images, manifest, sha256sums and the target kmod feed
- `packages/<arch>/<feed>/` — package feeds

`public-key.pem` is the apk signing key for these feeds. The images already carry it in `/etc/apk/keys/`.
