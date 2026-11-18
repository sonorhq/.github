# Sonor

Sonor is a music player for Subsonic and Navidrome servers, for macOS, Windows, Linux, iOS (with
CarPlay) and Android (with Android Auto).

## Try the public beta

Beta builds for macOS, Windows, Linux and Android are on
**[sonorhq/sonor › Releases](https://github.com/sonorhq/sonor/releases)**. iOS betas go through
TestFlight. Each beta expires 90 days after it is built, so download the newest one to keep
going. To report a bug or suggest something, [open an issue](https://github.com/sonorhq/sonor/issues).

## Repositories

- **[sonor](https://github.com/sonorhq/sonor):** public beta builds, and the LGPL source bundles
  for each release.
- **[sonor.fi](https://github.com/sonorhq/sonor.fi):** the website and the API behind
  `api.sonor.fi`. It's public so anyone can check what the update check records.

## Open-source components

Sonor's desktop apps include libmpv, FFmpeg and other libraries licensed under the GNU Lesser
General Public License. Sonor itself is not open source, but those libraries are separate files
inside the installed app, so you may swap them for your own builds of the same libraries.

Every release in **[sonorhq/sonor › Releases](https://github.com/sonorhq/sonor/releases)**
includes:

- the exact source code of those libraries;
- our patches;
- the build scripts;
- `README-REBUILD.txt`, with instructions to rebuild the libraries and replace them in an
  installed copy of Sonor.

To ask for the source in another form, [open an issue](https://github.com/sonorhq/sonor/issues).
