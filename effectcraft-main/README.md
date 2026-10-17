# FixLinux EffectCraft

**A Linux-focused community fork of EffectCraft.**

FixLinux EffectCraft aims to improve the Linux desktop experience of EffectCraft, with a sharper, more consistent interface inspired by Adobe After Effects and a focus on Linux compatibility.

> **Unofficial project:** This is a community modification and is not affiliated with or endorsed by the original EffectCraft developers.

## ✨ Goals

- **Sharper UI:** Reduce excessive rounded corners and create a more precise, professional interface.
- **Neutral dark theme:** Aim for consistent grey surfaces, clear borders, and fewer gradients and shadows.
- **Linux desktop consistency:** Improve the experience across KDE Plasma and GNOME.
- **Graphics compatibility:** Investigate rendering issues affecting effects such as Displacement Map on Linux.
- **Accessible distribution:** Provide convenient packages for Linux users.

## 🖥️ Platform Support

The project primarily targets Linux, with a focus on:

- Arch Linux
- KDE Plasma
- GNOME

Other Linux distributions may work, but compatibility must be tested individually.

## 📦 Downloads

Check the project's **GitHub Releases** for available builds.

| Format | Intended use |
| --- | --- |
| `.AppImage` | Portable application |
| `.flatpak` | Installable Flatpak package |
| `.tar.gz` | Compressed archive for manual use |

Only formats actually published in a release should be considered available. Build availability and compatibility may vary.

## 🛠️ Building from Source

The project uses Rust and Cargo.

1. Install Rust and the dependencies required by the original project.
2. Clone this repository.
3. Follow the original project's build instructions.
4. Build the modified source using the appropriate Cargo command.

```
cargo build --release -p effectcraft
```

The resulting executable is normally located in `target/release/`.

Packaging the executable as an AppImage or Flatpak is a separate step.

## 🧪 Compatibility and Testing

The modified interface has been tested by the maintainer on Linux.

Displacement Map compatibility across different Linux graphics environments remains under investigation until it has been independently verified.

Reports containing the Linux distribution, desktop environment, graphics hardware, and reproduction steps are welcome.

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome.

Please include:

- Your Linux distribution and version
- Your desktop environment and display server, if known
- Steps to reproduce the issue
- Relevant terminal output or screenshots

## ⚖️ Credits and Licensing

FixLinux EffectCraft builds upon the original EffectCraft project.

- Original project: [https://github.com/storytold/effectcraft](https://github.com/storytold/effectcraft)
- Original authors retain credit for their work.
- This fork's license and redistribution terms must comply with the original project's license and the licenses of its dependencies.

Please consult the original repository's license before redistributing source code or binaries.

---

**FixLinux EffectCraft — A sharper EffectCraft experience on Linux.**

## About This Fork

This repository contains a community fork of EffectCraft focused on improving the user interface, fixing bugs, and enhancing the Linux experience.

The project is based on the original EffectCraft codebase developed by the ArtCraft Team and its contributors.

## Changes and Improvements

- User interface refinements
- Bug fixes and stability improvements
- Linux usability improvements
- Ongoing development and experimentation

*Features listed above are goals and areas of development; not all improvements may be implemented yet.*

## Downloads

Prebuilt releases for Linux will be available on the GitHub Releases page.

Available packages may include:

- AppImage
- Flatpak
- Compressed archive

Check each release's notes for compatibility and installation instructions.

## License

This project retains the original MIT License. See the `LICENSE` file for the full license text.

Original copyright:\
Copyright (c) 2026 ArtCraft Team and the EffectCraft contributors.

This fork contains community modifications. Original copyright notices are retained where applicable.
