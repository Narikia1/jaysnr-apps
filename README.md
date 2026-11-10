# JaySnr downloads

JaySnr records your screen and camera with titles and sounds, and goes live on YouTube, Twitch, TikTok and more
at once. It is part of the JayApps family by Narikia.

**Get it at [jaysnr.narikia.com](https://jaysnr.narikia.com).** The website always links to the latest release here.

| Device | File |
| --- | --- |
| Mac (macOS 14 or later, Apple silicon and Intel) | `JaySnr-mac.dmg`, signed with an Apple Developer ID and notarized by Apple |
| Windows 10 or 11 | Coming soon |
| iPhone and iPad | Coming to the App Store |
| Android | Coming soon |

`SHA256SUMS.txt` in each release lets you check a download is the file we published:
`shasum -a 256 -c SHA256SUMS.txt` on Mac.

## Open source inside

JaySnr removes background noise with [nnnoiseless](https://github.com/jneem/nnnoiseless), the Rust version of
RNNoise (BSD licence), and uses fonts under the SIL Open Font License. The full list of projects and licences is
at [jaysnr.narikia.com/en/licences](https://jaysnr.narikia.com/en/licences).

## What is in this repository

Only the published files. JaySnr itself is built in Narikia's own repository.
