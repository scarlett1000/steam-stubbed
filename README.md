# Steam Stubbed

Plug n Play DLL that allows to patch SteamStub on the fly. Can be loaded by placing it in the `load_dlls` folder of [GBE](https://github.com/Detanup01/gbe_fork) or through any loader.

Tested against various basic SteamStub games and also works in games where [Steamless](https://github.com/atom0s/Steamless) fails to execute, such as Hi-Fi Rush.

## Download

Grab the latest build from GitHub:

- **Stable releases**: [Releases](https://github.com/denuvosanctuary/steam-stubbed/releases)
- **Nightly builds**: [Actions](https://github.com/denuvosanctuary/steam-stubbed/actions) (artifacts from the latest workflow run)

## Building from Source

```bash
cargo build --release
```

The output DLL will be in `target/release/steam_stubbed.dll`.

## Disclaimer

This project is for educational and research purposes only. Use responsibly and respect software licenses.
