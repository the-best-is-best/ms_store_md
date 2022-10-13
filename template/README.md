# ms_store 

A MS Store project created in flutter 3.3.4. 
MS Store support mobile only.

MS Store now ui only supported maps and locations.

## Features:
- Responsive
- Performance friendly
-  Google Map ready
- Splash Screen
- Login
- Register
- Forget Password
- Login with Social
- Theme
- Easy to edit
- Null safety
- more coming soon

## Up-Coming Features:

- Dark Mode

**Step 1:**

## how add your map api key

### android

* go to android/app/src/main/AndroidManifest.xml
``` xml 
.....
  <!-- Google Map-->
    <meta-data android:name="com.google.android.geo.API_KEY"
        android:value="your key"/>
```

### ios

* go to ios/Runner/AppDelegate.swift

``` swift
....
Bool {
    GMSServices.provideAPIKey("your key")
....
```

**Step 2:**
Go to project root and execute the following command in console to get the required dependencies: 

```yaml
flutter pub get 
```

### Folder Structure
Here is the core folder structure which flutter provides.

```
flutter-app/
|- android
|- build
|- ios
|- lib
|- test
```


Here is the folder structure we have been using in this project

```
lib/
|- app/
|- dummy/
|- features/
|- models/
|- services/
|- widgets/
|- main.dart
```

### app
|- components/
|- functions/
|- resources/
|- utils/
|- app.dart
|- extensions.dart

## app 

### utils
- Know is tablet or phone

### resources
```
|- assets_manager.dart
|- color_manager.dart
|- font_manager.dart
|- style_manager.dart
|- icons_manager.dart
|- routes_manager.dart
|- strings_manager.dart
|- themes_manager.dart
|- values_manager.dart
```
## dummy
```
|- cart_dummy.dart
|- category_dummy.dart
|- product_dummy.dart
|- favorite_dummy.dart
|- product_dummy.dart
```
## feature
 it is ui

## services
get locations and maps

