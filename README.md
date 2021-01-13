# parsec-flatpak
This is a flatpak-builder manifest for parsec.

To install:
```sh
$ git clone https://github.com/Kozova1/parsec-flatpak.git
$ cd parsec-flatpak
$ flatpak-builder --user --install app.parsec.Parsec.yml
```

To run:
```sh
$ flatpak run app.parsec.Parsec
```
