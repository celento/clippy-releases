# clippy-releases

Signed and notarized Clippy releases for macOS (Apple silicon and Intel).

Download the latest version from the [Releases](https://github.com/celento/clippy-releases/releases/latest) page.
Each release holds:

| File | What it is |
| --- | --- |
| `Clippy-X.Y.Z.dmg` | The installer: open it and drag Clippy to Applications |
| `Clippy-X.Y.Z.zip` | The same app as a zip, which installed copies download when they update |
| `appcast.xml` | The update feed Clippy checks (every six hours and from Clippy ▸ Check for Updates…) |

Every app and disk image is signed with a Developer ID certificate, notarized by Apple and stapled; the update
feed is signed with an EdDSA key that only the matching key inside the app accepts. This repository holds no
source code.
