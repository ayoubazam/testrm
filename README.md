## About The Project


The project aims to create a library of a Captcha system that can be used  easily in other mobile projects for Android.

The beginnings of the project was about creating a 5 steps Captcha game using Captcha service by Ocapi project(by teklia)


### Built With

* [Kotlin](https://kotlinlang.org/)
* [AndroidStudio](https://developer.android.com/studio)



## Getting Started

You can open this project using Android Studio. So you can set it up locally.
Please follow these steps below, to avoid errors running the project.

### Prerequisites



* something
  ```sh 
   install something -g
  ```

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





<!-- USAGE EXAMPLES -->
## Usage



To see some usage examples and learn more about the project, please refer to the [Documentation](https://example.com)_



## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
