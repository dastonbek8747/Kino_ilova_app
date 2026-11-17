# Android Movie App

> An Android movie application written in Java. It lists movies from an API and plays them in a video player.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)


## Features

- Movie list from a remote API.
- Detail screen with a poster and description.
- Built-in video player.
- Custom adapter for the list.

## Tech Stack

| Layer | Technology |
|---|---|
| Platform | Android |
| Language | Java |
| Build | Gradle (Kotlin DSL) |

## Build and Run

```bash
git clone https://github.com/dastonbek8747/android-movie-app.git
cd android-movie-app
./gradlew assembleDebug
```

Install the APK on a device or emulator, or open the project in Android Studio.

## Project Structure

```
app/src/main/java/com/example/kinoilovasi/
├── MainActivity.java
├── PlayerActivity.java
├── KinoAdapter.java
└── ApiClient.java
```

## License

MIT © 2026 Doston Sultonov.
