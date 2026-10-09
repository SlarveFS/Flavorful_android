# Flavorful for Android

### A recipe app for culinary students: search recipes, save favorites, and cook step by step

The Android version of Flavorful, built in **2021** (April to July) alongside the [iOS version](https://github.com/SlarveFS/IPV). Search a large library of recipes, check the ingredients, save favorites to your account, and follow recipes step by step.

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)

## Features

- **Recipe search** by keyword
- **Favorites** saved to your account and available later
- **Step-by-step cooking guide** for each recipe
- **Ingredients list**, so you don't forget anything at the store
- **Sign up and log in** with Firebase Authentication

## How it's built

| Area | Details |
|---|---|
| Language and UI | Java, AndroidX, Navigation component (fragments for Discover, Details, Step by step, Favorites), ViewModels |
| Networking | OkHttp for API requests, Picasso for images |
| Backend | Firebase Authentication, Cloud Firestore, Firebase Storage |

## Running it

Open the `Flavorful` folder in Android Studio and run on an emulator or device. Firebase features need your own `google-services.json`.

---

Built by **Slarve Benoit** · [@SlarveFS](https://github.com/SlarveFS)
