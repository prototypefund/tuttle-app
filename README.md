# Tuttle Desktop App

## Build

```
npx electron-forge make --arch=<arch> --platform=<platform>
```

where

- `<arch>` is `x86`, `arm64`, ...
- `<platform>` is `darwin` (macOS), `linux`, ...


```
npx electron-forge make --arch=arm64 --platform=darwin
```