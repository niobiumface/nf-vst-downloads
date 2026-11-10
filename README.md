# n-f.pro VST downloads

Free Windows builds of the n-f.pro VST3 plugins whose source code is not public – as GitHub releases with SHA-256 checksums. Watch this repository (“Releases only”) to get notified about new versions.

| Plugin | Type | Latest | Plugin page |
|---|---|---|---|
| **Double Up** | Zero-latency vocal doubler (VST3 + standalone) | [1.0.0](https://github.com/niobiumface/nf-vst-downloads/releases/tag/double-up-v1.0.0) | [n-f.pro/tools/double-up](https://n-f.pro/tools/double-up/) |
| **Trunk Rattle** | 808 synthesizer, VST3 instrument (VST3, setup, standalone) | [1.0.0](https://github.com/niobiumface/nf-vst-downloads/releases/tag/trunk-rattle-v1.0.0) | [n-f.pro/tools/trunk-rattle](https://n-f.pro/tools/trunk-rattle/) |
| **LOFI Maker Pro** | Bitcrusher, tape and vinyl (VST3) | [1.0.2](https://github.com/niobiumface/nf-vst-downloads/releases/tag/lofi-maker-pro-v1.0.2) | [n-f.pro/tools/lofi-maker-pro](https://n-f.pro/tools/lofi-maker-pro/) |

Plugins with public source code have their releases in their own repositories:

- **CUtTA** and **Sub** – [niobiumface/nf-vst-plugins](https://github.com/niobiumface/nf-vst-plugins/releases) (AGPLv3)
- **Abyss** – [niobiumface/abyss-vst](https://github.com/niobiumface/abyss-vst/releases) (AGPLv3)
- **Boilin'** – [niobiumface/Boilin](https://github.com/niobiumface/Boilin/releases)

## Requirements

Windows 10/11 x64 and a 64-bit DAW with VST3 support – or the standalone EXE where available.

## Install

1. Compare the SHA-256 checksum from the release notes: `Get-FileHash .\file.zip` in PowerShell.
2. Right-click the ZIP → Properties → tick **Unblock**, then extract it.
3. Copy the whole `.vst3` folder (or file) to `C:\Program Files\Common Files\VST3\` and rescan in your DAW.

Detailed guide for Ableton, FL Studio, Reaper, Bitwig, Cubase and Studio One: [Installing VST3 plugins on Windows](https://n-f.pro/blog/vst3-plugins-installieren/).

The binaries are not code-signed yet, so Windows SmartScreen may warn. If the checksum matches, choose *More info → Run anyway*.

## License

Freeware by n-f.pro – see [LICENSE](LICENSE). Free to download and use, including in commercial music productions.
