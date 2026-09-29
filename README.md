C++ engineer — native desktop and systems software for Windows and Linux;
build engineering (CMake, Conan).

## Open source


Contributions to [conan-center-index](https://github.com/conan-io/conan-center-index):

- **soxr: CMake 4 support** — filed [#27891](https://github.com/conan-io/conan-center-index/issues/27891),
  fixed in [#27892](https://github.com/conan-io/conan-center-index/pull/27892) (merged)
- **yasm: CMake 4 support** — filed [#27893](https://github.com/conan-io/conan-center-index/issues/27893),
  fixed in [#27894](https://github.com/conan-io/conan-center-index/pull/27894) (merged)
- **gcc 16.1.0** — requested [#30284](https://github.com/conan-io/conan-center-index/issues/30284),
  added in [#30285](https://github.com/conan-io/conan-center-index/pull/30285) (merged)
- **speexdsp 1.2.1** — requested [#30058](https://github.com/conan-io/conan-center-index/issues/30058),
  new recipe [#30059](https://github.com/conan-io/conan-center-index/pull/30059)
- **wxWidgets 3.3.0 build failure** — diagnosed the missing-submodules packaging
  issue (libwebp, lexilla, scintilla) in [#27922](https://github.com/conan-io/conan-center-index/issues/27922);
  resolved by a later community PR

Authored the initial Windows/MSVC portion of [pjproject](https://github.com/pjsip/pjproject)'s
CMake support ([#4494](https://github.com/pjsip/pjproject/pull/4494), merged) —
Winsock selection, WASAPI/UWP audio device — plus review and MSVC/clang-cl
build verification.

Fixed an ArrayIndexOutOfBounds bug in
[jackson-core](https://github.com/FasterXML/jackson-core)
([#221](https://github.com/FasterXML/jackson-core/pull/221), 2015) — applied by the
maintainer to the 2.5 and 2.6 branches.
