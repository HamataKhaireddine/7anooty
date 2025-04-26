# 📝 About 7anooty marketplace app :


## Open Source eCommerce Mobile App


[kestay](https://kestay.com/) revolutionizes the world of mobile commerce with its open-source eCommerce mobile app solution. This open-source mobile ecommerce app seamlessly transforms your kestay store into a powerful mobile platform, providing real-time synchronization of products and categories. With a user-friendly interface, managing orders becomes a breeze, making it an essential tool for tech-savvy individuals and those new to eCommerce.

This mobile app, built on the foundation of the kestay eCommerce framework and leveraging the robust Laravel stack, offers many features for a comprehensive and efficient mobile shopping experience. The app ensures easy product information management and accelerates time-to-market for your products, all while giving you complete control over your store.


## Features

The open-source ecommerce mobile app comes with an array of features to improve your customers' shopping experience.


### Interactive Home Page and Search

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/interactive-homepage-and-search.png)

### All Type Product Supported

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/product-details.png)

### Dark Mode and Push Notification

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/dark-theme-and-push-notifications.png)

### Discount Coupons and Guest Checkout

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/coupon-and-guest-checkout.png)

### Wishlist and Product Category

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/category%3Dpage-and-wishlist.png)

### Order Details and Product Reviews

![enter image description here](https://raw.githubusercontent.com/bagisto/temp-media/master/order-details-and-product-reviews.png)

### Installation Guide

Before beginning with the installation, you will need the following with the mentioned versions

- kestay Version - v2.2.2
- Android Studio Version - Flamingo | 2022.2.1
- Flutter Version - 3.19.2
- Dart - 3.3.0
- Xcode - 15.2
- Swift - 5

Make sure you have installed the API module and set this up properly on your kestay.

> NOTE: It is recommended that you run a simple Hello World program in Flutter first before proceeding further so that you are sure that the environment is properly set up.

### Installation Steps

#### Clone the repository

- Open your terminal or command prompt
- Navigate to the directory where you want to save the project
- Use the git clone command followed by the repository URL

```sh
git clone https://github.com/HamataKhaireddine/7anooty.git
```
#### Install dependencies

- Navigate to the project's directory

```sh
cd <repository-name>
```

- Run the following command to install the required packages

```sh
flutter pub get
```
#### Generate Required files

- Navigate to the project's directory

```sh
cd <repository-name>
```

- Run the following command to generate the required files

```sh
flutter pub run build_runner build --delete-conflicting-outputs 
```

#### Connect a device or emulator

* Physical Device

  1. Enable USB debugging on your device
  2. Connect it to your computer using a USB cable.

* Emulator

  1. Start an Android or iOS emulator using your preferred IDE or tools.

#### Run the Project

- Use the following command to build and run the project

```sh
flutter run
```
### Minimum Versions

- Android: 22
- iOS: 14

### Configurations Steps

#### For Setup

Change the baseUrl  as per your store

**Path:** lib/utils/server_configuration.dart

```sh
static const String baseUrl = ‘....’;
```
> Note: Add the value of the complete URL ending with the GraphQL API endpoint. E.g - https://example.com/graphql

#### For Theme

Change the Theme for your app

**Path:** lib/utils/mobikul_theme.dart

```sh
static const Color primaryColor = Color(***********);  
static const Color accentColor = Color(***********); 
```

#### For Push Notification Service

- Android

Replace "google-services.json".
- iOS

Replace "GoogleService-Info.plist".


#### For Application Title

* Android

  1. **Path:** android/app/src/main/AndroidManifest.xml
  2. **Change app name:** android:label="***********"

* iOS

  1. Go to the general tab and identity change the display name to your app name

> For Homepage Header Title - Go to ‘assets/language/en.json’
> (Note: Here, “en” in en.json refers to the languages that would be supported within the application)

#### For Splash Screen

* For adding Lottie as Splash Screen

  1. **Path:** assets/lottie/splash_screen.json
  2. After updating the Lottie file, update the ‘splashLottie’ in lib/utils/assets_constants.

```sh
 static const String splashLottie = "assets/lottie/splash_screen.json";
```

* For adding an Image as a Splash Screen

  1. **Path:** assets/images/splash.png
  2. After updating the Image file, update the ‘splashImage’ in lib/utils/assets_constants.

```sh
  static const String splashImage = "assets/images/splash.png";
```
#### For App Icon

* **Android:** Open the android folder in Android Studio and then right click app > new > Image Asset set Image.
* **iOS:** Replace the icons over the path > ios/Runner/Assets.xcassets/AppIcon.appiconset



### Usage

For detailed usage instructions, refer to the official documentation

### Contributing

Contributions are welcome! Follow the contribution guidelines to get started.

### License

MIT License © 2025 — Hamata Khaireddine

