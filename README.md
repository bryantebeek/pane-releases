# pane-releases

Public release artifacts and Sparkle appcast for [Pane](https://github.com/bryantebeek/pane).

- **Landing page**: https://bryantebeek.github.io/pane-releases/
- **Sparkle appcast**: https://bryantebeek.github.io/pane-releases/appcast.xml
- **Release artifacts**: [Releases tab](https://github.com/bryantebeek/pane-releases/releases)

Releases are cut from the private `bryantebeek/pane` repo via `scripts/release-mac.sh`. See that script for the full pipeline (archive → codesign → notarize → staple → zip → sign_update).
