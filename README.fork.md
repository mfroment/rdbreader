See README for instructions.

Modifications made:
- Migrate project to Visual Studio 2022.
- Statically link MSVCP140.dll and VCRUNTIME140.dll so it can run without Visual Studio installed.
- Changes in `config.h`:
  - Only extract (ogg) music, sfx, and lip
