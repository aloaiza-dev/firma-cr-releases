# FirmaCR — releases

Public distribution point for [FirmaCR](https://github.com/aloaiza-dev/firma-cr),
a macOS app for signing and verifying PDFs with the Costa Rican digital
signature card.

This repository holds only the Sparkle appcast and the signed release archives.
The source lives in a separate, private repository.

Every archive is signed with an EdDSA key. The app verifies that signature
before installing anything, so a tampered download is rejected regardless of how
it was obtained.

## Appcast

    https://raw.githubusercontent.com/aloaiza-dev/firma-cr-releases/main/appcast.xml
