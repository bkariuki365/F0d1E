# F0d1e
An android App utilising the Restful Spoonacular API 
This is a simple app that displays recipes from search input
A recipe instruction is also shown 
Added TTS- Text to speech so that you can listen to the recipe

This project utilizes the following opensource libraries
Credits goes to:
1. Android Opensource Project
2. Square Refrofit 
3. Square Picasso
4. Spoonacular API
5. JakeWhaton Butterknife
6. Firebase Authentication

# Project Structure/Tree

├─ .idea
│  ├─ codeStyles
│  │  ├─ Project.xml
│  │  └─ codeStyleConfig.xml
│  ├─ dictionaries
│  │  └─ F0d1e.xml
│  ├─ gradle.xml
│  ├─ misc.xml
│  └─ runConfigurations.xml
├─ app
│  ├─ src
│  │  ├─ androidTest
│  │  │  └─ java
│  │  │     └─ com
│  │  │        └─ brian
│  │  │           └─ f0d1e
│  │  │              └─ ExampleInstrumentedTest.java
│  │  ├─ main
│  │  │  ├─ java
│  │  │  │  └─ com
│  │  │  │     └─ brian
│  │  │  │        └─ f0d1e
│  │  │  │           ├─ Adapter
│  │  │  │           │  ├─ InstructionAdapter.java
│  │  │  │           │  └─ MyAdapter.java
│  │  │  │           ├─ Model
│  │  │  │           │  ├─ InstructionResponse.java
│  │  │  │           │  ├─ Recipe.java
│  │  │  │           │  ├─ RecipiesResponse.java
│  │  │  │           │  └─ Step.java
│  │  │  │           ├─ Retrofit
│  │  │  │           │  ├─ ApiClient.java
│  │  │  │           │  └─ ApiInterface.java
│  │  │  │           ├─ MainActivity.java
│  │  │  │           └─ RecipeDetailsActivity.java
│  │  │  ├─ res
│  │  │  │  ├─ drawable-v24
│  │  │  │  │  └─ ic_launcher_foreground.xml
│  │  │  │  ├─ drawable
│  │  │  │  │  ├─ header.png
│  │  │  │  │  ├─ ic_launcher_background.xml
│  │  │  │  │  └─ searchview_rounded.xml
│  │  │  │  ├─ layout
│  │  │  │  │  ├─ activity_main.xml
│  │  │  │  │  ├─ activity_recipe_details.xml
│  │  │  │  │  ├─ content_recipe_details.xml
│  │  │  │  │  ├─ recycler_row.xml
│  │  │  │  │  └─ steplist_row.xml
│  │  │  │  ├─ mipmap-anydpi-v26
│  │  │  │  │  ├─ ic_launcher.xml
│  │  │  │  │  └─ ic_launcher_round.xml
│  │  │  │  ├─ mipmap-hdpi
│  │  │  │  │  ├─ ic_launcher.png
│  │  │  │  │  ├─ ic_launcher_foreground.png
│  │  │  │  │  └─ ic_launcher_round.png
│  │  │  │  ├─ mipmap-mdpi
│  │  │  │  │  ├─ ic_launcher.png
│  │  │  │  │  ├─ ic_launcher_foreground.png
│  │  │  │  │  └─ ic_launcher_round.png
│  │  │  │  ├─ mipmap-xhdpi
│  │  │  │  │  ├─ ic_launcher.png
│  │  │  │  │  ├─ ic_launcher_foreground.png
│  │  │  │  │  └─ ic_launcher_round.png
│  │  │  │  ├─ mipmap-xxhdpi
│  │  │  │  │  ├─ ic_launcher.png
│  │  │  │  │  ├─ ic_launcher_foreground.png
│  │  │  │  │  └─ ic_launcher_round.png
│  │  │  │  ├─ mipmap-xxxhdpi
│  │  │  │  │  ├─ ic_launcher.png
│  │  │  │  │  ├─ ic_launcher_foreground.png
│  │  │  │  │  └─ ic_launcher_round.png
│  │  │  │  └─ values
│  │  │  │     ├─ colors.xml
│  │  │  │     ├─ dimens.xml
│  │  │  │     ├─ ic_launcher_background.xml
│  │  │  │     ├─ strings.xml
│  │  │  │     └─ styles.xml
│  │  │  ├─ AndroidManifest.xml
│  │  │  └─ ic_launcher-playstore.png
│  │  └─ test
│  │     └─ java
│  │        └─ com
│  │           └─ brian
│  │              └─ f0d1e
│  │                 └─ ExampleUnitTest.java
│  ├─ .gitignore
│  ├─ build.gradle
│  └─ proguard-rules.pro
├─ gradle
│  └─ wrapper
│     ├─ gradle-wrapper.jar
│     └─ gradle-wrapper.properties
├─ .gitignore
├─ README.md
├─ build.gradle
├─ gradle.properties
├─ gradlew
├─ gradlew.bat
└─ settings.gradle


