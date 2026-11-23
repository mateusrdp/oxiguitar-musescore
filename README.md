# oxiguitar-musescore

A placeholder for a MuseScore format plugin for [OxiGuitar](https://github.com/mateusrdp/oxiguitar), a free, open-source guitar tablature and score viewer, editor and player for Windows, macOS and Linux.

**This plugin isn't being built.** MuseScore support was dropped on 9 November 2026, and this repository is kept only as the empty scaffold it was. To bring a MuseScore score into OxiGuitar today, export it from MuseScore as MusicXML (**File → Export**, MusicXML) and open that with the MusicXML plugin.

## What MuseScore is

[MuseScore Studio](https://musescore.org/) is a free, open-source notation program, one of the most used in the world, now developed by Muse Group. Its own files (`.mscz`) are a ZIP archive holding the score as XML, in a format that changes with each major version of the program. Following those changes closely enough to read and write them well is a big job, which is why OxiGuitar goes through MusicXML instead, a format MuseScore reads and writes well.

## What's here

Nothing that runs: the repository layout, CI, licence and contribution rules every OxiGuitar plugin repository starts with. The user manual and the plugin developer guide live in the [OxiGuitar repository](https://github.com/mateusrdp/oxiguitar). If you would like to see MuseScore support come back, say so in [OxiGuitar's Discussions](https://github.com/mateusrdp/oxiguitar/discussions): anyone can write a format plugin with the SDK.

## Credits

[MuseScore Studio](https://github.com/musescore/MuseScore) is by Muse Group and its contributors (GPL-3.0); OxiGuitar studies its engraving and guitar features. OxiGuitar's plugin SDK is by Mateus Rocha de Paula and the OxiGuitar contributors. MuseScore is a trademark of Muse Group; this repository is not affiliated with it. Thank you to the MuseScore community for a free notation program millions rely on.

## Licence

GPL-3.0-or-later. See LICENSE.
Contributions are welcome under the same terms; see
[CONTRIBUTING.md](CONTRIBUTING.md).
