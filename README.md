# tamasaver

Legacy Android application project for `com.hwsknudsen.tamasaver`, stored in the older Eclipse/Ant Android project format.

## Project status

This repository targets a deprecated Android toolchain and appears to be a historical project rather than an actively maintained application.

## Repository layout

| Path | Purpose |
| --- | --- |
| `TamaSaver/AndroidManifest.xml` | Android app manifest |
| `TamaSaver/project.properties` | Legacy Android project target settings |
| `TamaSaver/src` | Java source files |
| `TamaSaver/res` | Android resources |

## Toolchain details

- Eclipse-style Android project layout
- Ant-era Android build configuration
- Project target: `android-16`
- Manifest package: `com.hwsknudsen.tamasaver`

## Maintenance notes

- This project will not build cleanly on a modern Android toolchain without migration work.
- If the application is still needed, the next step should be an explicit decision: migrate it to Android Studio/Gradle or archive it.
- Until that decision is made, this repository should be treated as legacy/reference code.
