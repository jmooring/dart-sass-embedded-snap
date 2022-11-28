# Snap package for Embedded Dart Sass

Embedded Dart Sass is a wrapper for [Dart Sass] that implements the compiler side of the [Embedded Sass protocol]. It's designed to be embedded in a host language, which then exposes an API for users to invoke Sass and define custom functions and importers.

Project: <https://github.com/sass/dart-sass-embedded>

Package: TBD

## Install and remove

Use the commands below to install or remove:

```text
sudo snap install dart-sass-embedded
sudo snap remove dart-sass-embedded
```

The Snap packages that you install are automatically updated when a new version is available.

## Usage

Start the compiler and listen on stdin

```text
dart-sass-embedded
```

Display version

```text
dart-sass-embedded --version
```

[Dart Sass]: https://sass-lang.com/dart-sass
[Embedded Sass protocol]: https://github.com/sass/sass-embedded-protocol/blob/master/README.md#readme
[Scoop commands]: https://github.com/ScoopInstaller/Scoop/wiki/Commands
