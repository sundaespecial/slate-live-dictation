# Open Slate — Offline Dictation

An Android dictation and note-taking app by Elijah Wright. Formerly named Slate.

## Download

[Download Open Slate 1.4.0](https://github.com/sundaespecial/slate-live-dictation/releases/download/v1.4.0/Open-Slate-1.4.0.apk)

Requires **Android 8.0 or newer and an arm64-v8a device**. Speech recognition supports **English**.

Open `Open-Slate-1.4.0.apk` on your Android device and allow installation from the app used to open it when prompted. Existing Slate users can install it as an update: the package ID (`dev.basalt.slate`) and signing identity are retained. Installing the update preserves saved notes; uninstalling the app removes its local data.

## What's new in 1.4.0

- The app is now **Open Slate**.
- **Phonon-2** runs natively on the phone for offline English transcription, including punctuation and capitalization. Recordings are not uploaded for transcription.
- The loaded engine is reused, and long recordings are split at quiet points.
- The upgrade refreshes old interface caches while preserving notes and pairing settings.

The signed release was tested on a Pixel Fold. An 11-second speech sample transcribed correctly in about 1.3 seconds on a warm run. Performance varies with the device and recording. JavaScript regression tests and on-device recognition, repeatability, and silence tests passed.

## Verify your download

SHA-256 for `Open-Slate-1.4.0.apk`:

```text
94a1487d366636d10ded4a6666bc540a48d117283a90b5061080deb63c977c15
```

Checksums are also available in [SHA256SUMS.txt](SHA256SUMS.txt) and attached to the release. [Earlier releases](https://github.com/sundaespecial/slate-live-dictation/releases) remain available.

This repository contains downloadable Android builds and release documentation. Application source code is not included.

## License

Copyright 2026 Elijah Wright. The author's original Slate/Open Slate application work and this repository's documentation are licensed under the [Apache License, Version 2.0](LICENSE).

For this distribution, the copyright owner grants Apache 2.0 rights to the original application work, superseding its legacy embedded Slate Source-Available Licence. Third-party libraries, models, and other components retain their respective licenses and notices. See [NOTICE](NOTICE).

Phonon-2 is by Fermion Research and derives from NVIDIA's Parakeet TDT 0.6B v3. Its weights are **CC BY 4.0**; the native engine and header are **Apache 2.0**. Full attribution and license texts are in [PHONON-NOTICES.txt](PHONON-NOTICES.txt), also bundled in the app and attached to the release.
