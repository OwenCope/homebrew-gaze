# Homebrew tap for Gaze

Gaze is an app that brings the Face ID feature of your iPhone to your Mac.

```sh
brew install --cask owencope/gaze/gaze
```

Gaze is not notarized by Apple, so this cask clears the macOS quarantine flag after
installing and on every upgrade. That is the same step as running
`xattr -dr com.apple.quarantine /Applications/Gaze.app` yourself.

More at [gazeunlock.com](https://gazeunlock.com) and [OwenCope/Gaze](https://github.com/OwenCope/Gaze).
