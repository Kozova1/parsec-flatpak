# parsec-flatpak
This is a flatpak-builder manifest for parsec.

First, make sure you have the freedesktop SDK:

```sh
$ flatpak install org.freedesktop.Sdk/x86_64/19.08
```

To install:
```sh
$ git clone https://github.com/Kozova1/parsec-flatpak.git
$ cd parsec-flatpak
$ flatpak-builder --user --install build-dir app.parsec.Parsec.yml
```

To run:
```sh
$ flatpak run app.parsec.Parsec
```
