# Tauri Youtube Music Desktop

Super simple Youtube Music Wrapper based on Tauri. Uses the native system webview to reduce the footprint.

The prebuilt macos binary incorporates [this patch](https://github.com/tauri-apps/wry/pull/280) to override the user agent on MacOS.

This program should also work fine on Windows and Linux if Google does not have an issue with the user agent of the native platform webviews. Once the patch is merged into Tauri, I'll properly test it on Windows and Linux and publish prebuilt binaries. It might require a restart after signing in.

This project requires rust nightly.