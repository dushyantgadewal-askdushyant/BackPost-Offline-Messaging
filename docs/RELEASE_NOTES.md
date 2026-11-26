# BackPost for Android 1.0.0 · build 18

**Release status** · First stable Android release.

This release includes direct QR and nearby pairing, verified device identities, encrypted messaging and file transfers, delivery and read checks, chat retention, and per-chat muting.

BackPost is free to install and use. See [BackPost licensing](../LICENSE.md) for the terms that apply to this APK.

## What changed in build 18

- One branded Android launch screen highlights peer-to-peer messaging and end-to-end encryption.
- Scan QR and Find nearby phones guide you to Settings when Bluetooth is off.

## APK and verification

- GitHub release asset · **BackPost-Android-1.0.0+18-release.apk**
- SHA-256 · **b8fef1a8a1c5c2679a2f86b140b72a45acaf26f0e9f255164817541e0b7c21d8**
- Availability · Use the [README download link](../README.md#download-for-android).

On Windows, open PowerShell in your download folder and run the command below. Compare the result to the SHA-256 above.

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath './BackPost-Android-1.0.0+18-release.apk'
```

## Updating a test installation

Android can install an update over an existing BackPost installation when the package and signing certificate match and the new build has a compatible version. If an earlier test APK used a different signing certificate, Android may require you to remove it first. Uninstalling removes app-local history and pairing information. Save anything you need before uninstalling.

## Android and connection limits

- Pairing and delivery depend on nearby radio access and the receiving phone being reachable.
- Large file transfers require approval above 50 MB. If you retry after an interruption, the file starts again.
- Background availability is temporary and depends on Android permissions and device behavior.
