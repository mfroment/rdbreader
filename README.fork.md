### How to
- Check out `mine` branch (branched from `master`)
- Build with Visual Studio 2022, Release/Win32
- See README for additional details
- The exporter in this project misses certain assets. Use the utility batch in [the `develop-mine`](https://github.com/mfroment/tswrdb/blob/develop-mine/README.fork.md) of the fork of the `tswrdb` project instead.
- Use `lipreader` from this project to convert `lip` files to `ogg`.

### Changes
- Migrate project to Visual Studio 2022.
- Statically link MSVCP140.dll and VCRUNTIME140.dll so it can run without Visual Studio installed.
- Changes in `config.h`:
  - Only extract (ogg) music, sfx, and lip
