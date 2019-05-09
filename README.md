# go-tun2socks-ios

Demo for building and using `go-tun2socks` on iOS and Android.

## Prerequisites

- macOS (iOS)
- Xcode (iOS)
- make
- Go >= 1.11
- A C compiler (e.g.: clang, gcc)
- gomobile (https://github.com/golang/go/wiki/Mobile)
- Other common utilities (e.g.: git)

## Build
```bash
go get -d ./...

# Build an AAR
make android

# Build a Framework
make ios

# Both
make
```
