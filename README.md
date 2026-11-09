# Compose Quadrant

A screen split into four equal colored quadrants, each describing one basic Compose composable (Text, Image, Row, Column).

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Compose quadrant" practice problem).

## Features

- 2x2 grid of info cards with a bold title and justified description
- Each quadrant has its own background color

## Built with

- Kotlin, Jetpack Compose, Material 3
- `Row`/`Column` with `Modifier.weight` to split the screen evenly
- A reusable private `ComposableInfoCard` composable
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
