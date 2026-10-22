# Awesome Rename Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![CI](https://github.com/ugzv/Awesome-Rename-Tools/actions/workflows/ci.yml/badge.svg)](https://github.com/ugzv/Awesome-Rename-Tools/actions/workflows/ci.yml) [![Last Commit](https://img.shields.io/github/last-commit/ugzv/Awesome-Rename-Tools)](https://github.com/ugzv/Awesome-Rename-Tools/commits/main)

> A curated list of file renaming tools, libraries, and resources for batch renaming, metadata-based organization, and filename cleanup.

New tool submissions must be free to use and open source. Existing commercial listings are maintained for accuracy.

`Free` can mean a free tier or use limited to personal projects; check the entry and project license for restrictions. Commercial plans are labeled `Paid`. Projects with relevant maintenance or compatibility limits are labeled `Stale` or `Legacy`.

Last reviewed: October 22, 2026.

## Contents

- [AI-Powered Renaming](#ai-powered-renaming)
- [Command Line Tools](#command-line-tools)
- [Desktop Applications - Cross-platform](#desktop-applications---cross-platform)
- [Desktop Applications - Windows](#desktop-applications---windows)
- [Desktop Applications - macOS](#desktop-applications---macos)
- [Desktop Applications - Linux](#desktop-applications---linux)
- [Web-Based Tools](#web-based-tools)
- [Media and Metadata-aware Tools](#media-and-metadata-aware-tools)
- [File Manager Integrations](#file-manager-integrations)
- [Development Tools](#development-tools)
- [Browser Extensions](#browser-extensions)
- [Mobile Apps](#mobile-apps)
- [File Automation](#file-automation)
- [Resources](#resources)

## AI-Powered Renaming

*Tools that inspect file contents and generate names automatically.*

- [Renamer.ai](https://renamer.ai) - AI renaming for PDFs, images, and documents with custom naming templates, folder organization, and watched-folder automation for Windows, macOS, and web workflows; includes a free tier. `Free` `Paid`.

## Command Line Tools

*Tools for batch renaming files from the terminal.*

- [brename](https://github.com/shenwei356/brename) - Go-based batch renamer with regex support, undo records, and collision checks. `Free`.
- [detox](https://github.com/dharple/detox) - Unix filename cleanup utility with dry-run support; development is paused and the repository is archived. `Free` `Stale`.
- [edir](https://github.com/bulletmark/edir) - Bulk rename tool that lets you edit a file list in your text editor with preview and git-aware moves. `Free`.
- [F2](https://github.com/ayoisaiah/f2) - Cross-platform renaming tool with dry runs, variables, EXIF support, and conflict handling. `Free`.
- [massren](https://github.com/laurent22/massren) - Batch rename tool that opens filenames in your text editor and applies the edited result. `Free`.
- [mmv](https://github.com/rrthomas/mmv) - Classic Unix tool for moving, copying, linking, or renaming files with wildcard source and target patterns. `Free`.
- [nomino](https://github.com/yaa110/nomino) - Rust batch renamer with regex patterns, sort-based numbering, JSON maps, and dry-run mode. `Free`.
- [PowerShell Rename-Item](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/rename-item) - PowerShell cmdlet for scripted file and folder renaming with pipeline support and a `-WhatIf` preview. `Free`.
- [rename (Perl)](https://manpages.debian.org/trixie/rename/rename.1.en.html) - Batch renamer that applies Perl expressions to filenames, also packaged as `file-rename`. `Free`.
- [rename.ul (util-linux)](https://manpages.debian.org/trixie/util-linux/rename.ul.1.en.html) - Batch renamer that replaces literal text in filenames; its syntax differs from the Perl variant. `Free`.
- [renamer](https://github.com/75lb/renamer) - Node.js renaming tool with plugin support and flexible input handling. `Free`.
- [renameutils](https://www.nongnu.org/renameutils/) - POSIX utility suite including `qmv`, `qcp`, `imv`, `icp`, and `deurlname` for interactive and editor-based renaming. `Free`.
- [rnr](https://github.com/ismaelgv/rnr) - Rust-based regex renamer with dry-run mode, backups, and recursive directory support. `Free`.

## Desktop Applications - Cross-platform

*Graphical renaming tools that work across more than one desktop operating system.*

- [Advanced Renamer](https://www.advancedrenamer.com/) - Batch renamer for Windows and macOS with metadata rules; free for occasional personal use, with a license required for frequent personal or commercial use. `Free` `Paid`.
- [Flut Renamer](https://github.com/sun-jiao/flut-renamer) - Flutter-based batch renamer for desktop and mobile platforms with metadata and EXIF insertion. `Free`.
- [Renamer](https://renamer.com/) - Multi-step batch renamer with workflows and presets for macOS and Windows. `Paid`.
- [Szyszka](https://github.com/qarmin/szyszka) - Rust and GTK4 renamer with combinable rules and good performance on large file sets. `Free`.

## Desktop Applications - Windows

*Graphical renaming tools built for Windows users.*

- [Ant Renamer](https://www.antp.be/software/renamer) - Lightweight Unicode-aware batch renamer with common transformation rules. `Free`.
- [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/) - Windows batch renamer; free for private use at home, with paid licenses for commercial use and additional features. `Free` `Paid`.
- [PowerRename](https://learn.microsoft.com/en-us/windows/powertoys/powerrename) - Microsoft PowerToys renaming utility with regex, preview, and shell integration. `Free`.
- [ReNamer](https://www.den4b.com/products/renamer) - Rule-based Windows renamer with presets and multi-step transformations. `Free` `Paid`.

## Desktop Applications - macOS

*Native or macOS-first renaming tools.*

- [A Better Finder Rename](https://www.publicspace.net/ABetterFinderRename/) - Finder-integrated batch renamer with rich metadata and camera-oriented rules. `Paid`.
- [Name Mangler](https://manytricks.com/namemangler/) - Native macOS renamer with fast batch processing and many metadata fields. `Paid`.
- [NameChanger](https://mrrsoftware.com/namechanger/) - Simple macOS batch renamer with regex support and drag-and-drop workflow. `Free`.

## Desktop Applications - Linux

*Linux-focused GUI renaming tools and file manager helpers.*

- [Bulky](https://github.com/linuxmint/bulky) - Linux Mint batch renamer for files and directories across Cinnamon, MATE, GNOME, and other Linux desktops. `Free`.
- [GPRename](https://gprename.sourceforge.net/) - GTK-based batch renamer for files and directories with replace, insert, and enumerate functions. `Free`.
- [KRename](https://apps.kde.org/krename/) - KDE renaming tool with EXIF and ID3 plugins, undo support, and scripting features. `Free`.
- [Thunar Bulk Renamer](https://docs.xfce.org/xfce/thunar/bulk-renamer/start) - Built-in bulk rename interface for the Thunar file manager. `Free`.

## Web-Based Tools

*Browser-based tools for quick renaming jobs.*

- [WebRename](https://www.webrename.com/) - Pattern-based renaming with real-time preview in the browser. `Free`.

## Media and Metadata-aware Tools

*Tools that rename files using embedded media metadata or media databases.*

- [beets](https://github.com/beetbox/beets) - Music library manager that tags and renames audio files with MusicBrainz and AcoustID. `Free`.
- [digiKam](https://www.digikam.org/) - Photo manager for Windows, macOS, and Linux with batch renaming from metadata, dates, and sequence numbers. `Free`.
- [ExifRenamer](https://www.qdev.de/?location=mac/exifrenamer) - macOS app for renaming photos from EXIF metadata such as capture date and camera details. `Free`.
- [ExifTool](https://exiftool.org/) - Industry-standard metadata utility for renaming and organizing files across hundreds of formats. `Free`.
- [FileBot](https://www.filebot.net/) - Movie and TV renamer that matches files to online databases and fetches metadata. `Paid`.
- [Mp3tag](https://www.mp3tag.de/en/) - Audio tag editor that can rename and move files from metadata templates. `Free` `Paid`.
- [MusicBrainz Picard](https://picard.musicbrainz.org/) - Cross-platform GUI music tagger with scripting and MusicBrainz-based renaming. `Free`.
- [PhotoRenamer](https://www.tgmdev.be/applications/photorenamer/photorenamer.php) - Windows photo organizer with metadata-driven naming and duplicate detection. `Free`.
- [tinyMediaManager](https://www.tinymediamanager.org/) - Movie and TV organizer with renaming in the free edition and additional metadata sources and integrations in the paid Pro edition. `Free` `Paid`.
- [TV Rename](https://www.tvrename.com/) - Windows TV episode manager focused on clean naming and show organization. `Free`.
- [XnView MP and XnConvert](https://www.xnview.com/) - Image management and conversion tools with batch renaming and EXIF-aware tokens; free for private or educational use, with licenses required for company use. `Free` `Paid`.

## File Manager Integrations

*Rename features built into file managers or tightly integrated with them.*

- [Directory Opus Advanced Rename](https://docs.dopus.com/doku.php?id=file_operations:renaming_files:advanced_rename) - Advanced rename module for Directory Opus with wildcards, regex, metadata, and scripts. `Paid`.
- [Double Commander Multi-Rename](https://doublecmd.github.io/doc/en/multirename.html) - Built-in multi-rename tool for the Double Commander file manager. `Free`.
- [GNOME Files Batch Rename](https://apps.gnome.org/Nautilus/) - Template-based batch rename built into GNOME Files. `Free`.
- [macOS Finder Batch Rename](https://support.apple.com/guide/mac-help/mchlp1144/mac) - Built-in Finder feature for replace, add, and format renaming templates. `Free`.
- [Total Commander Multi-Rename Tool](https://www.ghisler.ch/wiki/index.php?title=Multi-rename_tool) - Built-in batch renaming tool for Total Commander. `Paid`.

## Development Tools

*Renaming tools that are specific to codebases, projects, or developer workflows.*

- [Unity Mulligan Renamer](https://github.com/redbluegames/unity-mulligan-renamer) - Unity asset renamer for batch updates inside game projects. `Free`.

## Browser Extensions

*Extensions that organize downloaded files or rename them at the browser edge.*

- [RegExp Download Organizer](https://chromewebstore.google.com/detail/regexp-download-organizer/oamembonjndgangicfphlckkdmagpjlg) - Chrome extension for sorting downloads into folders and renaming them by rule. `Free`.

## Mobile Apps

*Renaming tools that work directly on mobile devices.*

- [Bulk Renamer](https://play.google.com/store/apps/details?id=com.panaustik.bulkrenamer) - Android batch renamer with ads and in-app purchases. `Free` `Paid`.
- [Flut Renamer](https://play.google.com/store/apps/details?id=net.sunjiao.renamer) - Android app version of the cross-platform Flut Renamer project. `Free`.
- [Renamer - Batch file renamer](https://apps.apple.com/us/app/renamer/id6739964693) - iPhone and iPad batch renamer with a limited free trial and a one-time Pro purchase. `Paid`.

## File Automation

*Rule-based tools for renaming, sorting, and organizing files automatically.*

- [Hazel](https://www.noodlesoft.com/) - Rule-based macOS automation tool for renaming and moving files as they arrive. `Paid`.
- [organize](https://github.com/tfeldmann/organize) - Rule-based file renaming and organization using metadata, document text, and templates, with a simulation mode for checking changes. `Free`.

## Resources

*Documentation, learning material, and communities for better file naming and renaming workflows.*

- [Data Management Best Practices](https://guides.library.stanford.edu/data-best-practices) - Stanford guide to organizing and managing research files.
- [PowerShell Rename Cmdlets](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/) - Official Microsoft documentation for PowerShell file operations.
- [Regular Expressions for File Renaming](https://regex101.com/) - Interactive regex tester and learning resource.
- [r/DataHoarder](https://www.reddit.com/r/DataHoarder/) - Community discussions about storage, organization, and file management.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

If you maintain a listed project, you are welcome to link back with a badge:

```md
[![Mentioned in Awesome Rename Tools](https://awesome.re/mentioned-badge.svg)](https://github.com/ugzv/Awesome-Rename-Tools)
```
