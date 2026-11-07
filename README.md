> **Fork (emildeev/amneziawg-android):** adds *Settings → Connect on app launch*
> (on by default) — opening the app brings up the last used tunnel (or the first
> one) if nothing is connected yet. Installs next to the official app as
> `org.amnezia.awg.autoconnect`. Signed APKs are published by `release.yml` on
> `v*` tags; the signing key lives in OpenBao `kv/apps/amneziawg-android`.

# Android GUI for [AmneziaWG](https://amnezia.org/learn-more/31_amneziawg)

**[Download from the Play Store](https://play.google.com/store/apps/details?id=org.amnezia.awg)**

This is an Android GUI for [AmneziaWG](https://amnezia.org/learn-more/31_amneziawg).

## Building

```
$ git clone --recurse-submodules https://github.com/amnezia-vpn/amneziawg-android
$ cd amneziawg-android
$ ./gradlew assembleRelease
```

macOS users may need [flock(1)](https://github.com/discoteq/flock).
