# FreeType

The **FreeType** engine is a free and portable font rendering engine, developed to provide advanced font support for a variety of platforms and environments. FreeType is a library which can open and manages font files as well as efficiently load, hint and render individual glyphs. FreeType is not a font server or a complete text-rendering library.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/freetype
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y freetype
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/freetype).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/freetype) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
