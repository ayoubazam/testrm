## About The Project

The project consist on building an Android mobile app, that contains a 5 steps Captcha, using Ocapi API.

The final goal is to create a library of a Captcha system that can be used  easily in other mobile projects for Android.



### Built With

* [Kotlin](https://kotlinlang.org/)
* [AndroidStudio](https://developer.android.com/studio)



## Getting Started

You can open this project using Android Studio. So you can set it up locally.
Please follow these steps below, to avoid errors running the project.

### Prerequisites

Before installing Android SDK, you need to install Java Development Kit (JDK).Ensure that your JDK is at or above 1.8. You can check your JDK version with command "javac -version".

### Installation

1. Get a free API Key at teklia
2. Clone the repo
   ```sh
   git clone https://github.com/username/name.git
   ```
3. Enter your API in `file.kt`
   ```kt
   const API_KEY = 'ENTER YOUR API';
   ```

## Gradle

You should add the following dependencies into the gradle file for the project to run properly.

First, add the "hilt-android-gradle-plugin" plugin to your project's root build.gradle file:

```kt
   buildscript {
    ...
    dependencies {
        ...
        classpath 'com.google.dagger:hilt-android-gradle-plugin:2.38.1'
    }
}
   
```
Then, apply the Gradle plugin and add these dependencies in your app/build.gradle file:

1. Hilt

   ```kt
      ...
   plugins {
   id 'kotlin-kapt'
   id 'dagger.hilt.android.plugin'
   }

   android {
      ...
   }

   dependencies {
      implementation "com.google.dagger:hilt-android:2.38.1"
      kapt "com.google.dagger:hilt-compiler:2.38.1"
   }

   ```
2. Retrofit
   ```kt
   implementation 'com.squareup.retrofit2:retrofit:2.5.0'
   implementation "com.squareup.retrofit2:converter-moshi:2.5.0"
   implementation "com.jakewharton.retrofit:retrofit2-kotlin-coroutines-adapter:0.9.2"
   ```
3. Moshi
   ```kt
   implementation "com.squareup.moshi:moshi:1.8.0"
   kapt "com.squareup.moshi:moshi-kotlin-codegen:1.8.0"
   ```
4. Kotlin couroutines
   ```kt
   implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.0.0'
   implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.0.0' 
   ```





## Usage



To see some usage examples and learn more about the project, please refer to the [Documentation](https://github.com/github_username/repo_name/doc)_



## Roadmap

- [x] User Interface
- [x] Dagger-Hilt Integration
- [x] Make UI responsive
- [x] API functions
- [x] Unit-test
- [x] Timer
- [x] Pepeline
- [ ] Library



See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).


## Contributing

Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

