## [1.5.0] - 2026-09-02

### Added
- Support for aonHelper FG stylegrounds bloom controllers. @earthwise01
- Custom bloom colors. @aonkeeper4

### Changed
- Use a `DetourConfigContext` when loading hooks (facilitates mod cross-compatibility). @earthwise01
- Add compatibility with motion smoothing's fractional camera positions. @cruzgodar
- `GetMaskSlices` performance improvements. @karl2883


## [1.4.0] - 2025-09-05

### Added
- Support for zoom out - @earthwise01
- Styleground Mask Tilesets - @earthwise01
	-  Adding a `styleMaskHelper_maskTag="maskTag"` attribute to a tileset will cause any background stylegrounds with the tag `mask_maskTag` to be rendered as part of the tileset (behind each of its tiles)
