<p align="center">
  <img src="./demo/icon.png" width="150" />
</p>

# Paperless Share

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png"
     alt="Get it on Google Play"
     height="80">](https://play.google.com/store/apps/details?id=com.quinncasey.paperless_share)
     
An Android app that bridges your document scanner with your [paperless-ng](https://github.com/jonaswinkler/paperless-ng) server.

<img src="./demo/demo.gif" width="300" />

## Why?

I like using extremely refined scanning apps such as [Office Lens](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&hl=en_US&gl=US) for documents. **Paperless Share** adds Paperless to the Android share sheet for easy consumption.

It's similar in spirit to [TripleCamel](https://github.com/ebaschiera/TripleCamel), an app that does its job well and can be hidden from your launcher's app list.

## Getting Started

### Android

Download [latest release](https://github.com/qcasey/paperless_share/releases/) or build from source.

FDroid release is [waiting to be merged](https://gitlab.com/fdroid/fdroiddata/-/merge_requests/7828).

## Building

Install [Flutter](https://flutter.dev/docs/get-started/install) and [integrate with your IDE of choice](https://flutter.dev/docs/get-started/editor?tab=vscode). A release can then be built and installed using:

```bash
flutter pub get
flutter build appbundle
flutter build apk --split-per-abi
cd build/app/outputs/flutter-apk/
flutter install
```

## TODO

* Make PR to https://github.com/bauerj/paperless_app
* Make error handling better and less not-existing
