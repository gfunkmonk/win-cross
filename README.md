# $${\color{red}win\\color{white - }\color{lightblue}cross}$$

This is a simple, lightweight project for making cross-compilation toolchain with MinGW.

## Supported targets

|       _Target_      | **GCC** | **MinGW** | **Binutils** | **MOLD** |
|:-------------------:|:-------:|:---------:|:------------:|:--------:|
| $${\color{salmon}i686-w64-mingw32}$$    | $${\color{skyblue}16.2.0}$$  | $${\color{violet}14.0.0}$$    |     $${\color{hotpink}2.47}$$     | $${\color{#FFEE8C}2.42.0}$$   |
| $${\color{salmon}x86_64-w64-mingw32}$$  | $${\color{skyblue}16.2.0}$$  | $${\color{violet}14.0.0}$$    |     $${\color{hotpink}2.47}$$     | $${\color{#FFEE8C}2.42.0}$$   |
| $${\color{salmon}aarch64-w64-mingw32}$$ | $${\color{skyblue}16.2.0}$$  | $${\color{violet}14.0.0}$$    |     $${\color{hotpink}2.47}$$     | $${\color{#FFEE8C}2.42.0}$$   |
| $${\color{salmon}armv7-w64-mingw32}$$   | $${\color{skyblue}16.2.0}$$  | $${\color{violet}14.0.0}$$    |     $${\color{hotpink}2.47}$$     | $${\color{#FFEE8C}2.42.0}$$   |

## How to use

Download the tarball from the [release page](https://github.com/gfunkmonk/win-cross/releases) and extract it to `/opt/x-tools`:

```sh
sudo mkdir -p /opt/x-tools
sudo tar -xf ${target}.tar.xz -C /opt/x-tools
```

## How to build

Fork this project and create a new release, or build manually:

```sh
./scripts/make ${target}
```

## License

MIT

## Acknowledgements

We would like to express our gratitude to the following individuals and projects:

- [crosstool-ng](https://github.com/gfunkmonk/crosstool-ng)
- [mingw-w64](https://www.mingw-w64.org)
