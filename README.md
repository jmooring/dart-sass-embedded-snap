> [!Note]
> The Dart Sass team discontinued Embedded Dart Sass, with v1.62.1 as the final release. Dart Sass v1.63.0 and later include the embedded compiler, accessible by running `sass --embedded`.

---

# Snap package for Embedded Dart Sass

[![dart-sass-embedded](https://snapcraft.io/dart-sass-embedded/badge.svg)](https://snapcraft.io/dart-sass-embedded)

Embedded Dart Sass is a wrapper for [Dart Sass] that implements the compiler side of the [Embedded Sass Protocol]. It's designed to be embedded in a host language, which then exposes an API for users to invoke Sass and define custom functions and importers.

Documentation: <https://sass-lang.com>

Project: <https://github.com/sass/dart-sass-embedded>

Package: <https://snapcraft.io/dart-sass-embedded>

## Install and remove

Use the commands below to install or remove:

```text
sudo snap install dart-sass-embedded
sudo snap remove dart-sass-embedded
```

## Update

Snap packages that you install are automatically updated when a new version is available.

## Usage

To display the version:

```text
dart-sass-embedded --version
```

[Dart Sass]: https://sass-lang.com/dart-sass
[Embedded Sass Protocol]: https://github.com/sass/sass/blob/main/spec/embedded-protocol.md
