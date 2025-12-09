# Unofficial Home Assistant Apps (Add-ons) Repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/lmagyar/repository-test
```

## Add-ons provided by this repository

### &#10003; [Tailscale with features][addon-tailscale]

![Latest Version][tailscale-version-shield]
![Supports armhf Architecture][tailscale-armhf-shield]
![Supports armv7 Architecture][tailscale-armv7-shield]
![Supports aarch64 Architecture][tailscale-aarch64-shield]
![Supports amd64 Architecture][tailscale-amd64-shield]
![Supports i386 Architecture][tailscale-i386-shield]

Zero config VPN for building secure networks

[:books: Tailscale with features add-on documentation][addon-doc-tailscale]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

Open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Tailscale with features][tailscale-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2025 [homeassistant-apps][github-org]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-tailscale]: https://github.com/lmagyar/homeassistant-addon-test/tree/v0.26.1.5
[addon-doc-tailscale]: https://github.com/lmagyar/homeassistant-addon-test/blob/v0.26.1.5/README.md
[tailscale-issue]: https://github.com/lmagyar/homeassistant-addon-test/issues
[tailscale-version-shield]: https://img.shields.io/badge/version-v0.26.1.5-blue.svg
[tailscale-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tailscale-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tailscale-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tailscale-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tailscale-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[gitlabci-shield]: https://gitlab.com/lmagyar/repository-test/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/lmagyar/repository-test/pipelines
[issue]: https://github.com/lmagyar/repository-test/issues
[license-shield]: https://img.shields.io/github/license/lmagyar/repository-test.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html
[github-org]: https://github.com/homeassistant-apps