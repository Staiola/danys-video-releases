# Dany’s Video

A Jellyfin client that turns your film library into VHS tapes in a room.

This is the official **downloads and automatic-update repository** for the Mac
and browser clients. The development project and private demo are kept separately.

**Public downloads are being prepared. There is no public installer here yet.**
The Mac package is going through signing and notarization. Bundled room assets
must also pass their redistribution review before either client is published.

## Mac

The planned download runs on Apple Silicon and Intel Macs with macOS 12 or later.
Download the app, move it to Applications, and connect to your Jellyfin server.
Automatic updates and a “Check for Updates…” menu will be included from the first release.

## Browser

The planned browser download contains the ready-to-host client. It does not include
a Jellyfin server or movies. A hosted HTTPS client needs a server connection the
browser permits; an HTTPS page cannot be assumed to reach a local HTTP server.
Installation and update instructions will accompany the package.

Browser clients necessarily deliver JavaScript and assets to the browser. This
repository will not publish the full development repository, its history, private
demo catalogue, credentials, or personal room data.

## Requirements and help

Use your own Jellyfin server and Jellyfin account. No separate Dany’s Video account
is required. Optional movie-art searches use TMDB; the client is not endorsed or
certified by TMDB or affiliated with the Jellyfin project.

For problems, [open an issue](https://github.com/Staiola/danys-video-releases/issues).
Never include passwords, access tokens or private server details in a public issue.

The app’s permanent update feed is [appcast.xml](https://raw.githubusercontent.com/Staiola/danys-video-releases/main/appcast.xml).
An empty feed means no public updates have been published yet.
