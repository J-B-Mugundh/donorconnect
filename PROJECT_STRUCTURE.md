## Project Structure

<!-- START_STRUCTURE -->
```
├── CODE_OF_CONDUCT.md
├── Contributors.md
├── LICENSE.md
├── PROJECT_STRUCTURE.md
├── README.md
├── analysis_options.yaml
├── android/
│   ├── app/
│   │   ├── build.gradle
│   │   ├── google-services.json
│   │   └── src/
│   │       ├── debug/
│   │       │   └── AndroidManifest.xml
│   │       ├── main/
│   │       │   ├── AndroidManifest.xml
│   │       │   ├── ic_launcher-playstore.png
│   │       │   ├── kotlin/
│   │       │   │   └── com/
│   │       │   │       └── example/
│   │       │   │           └── donorconnect/
│   │       │   │               └── MainActivity.kt
│   │       │   └── res/
│   │       │       ├── drawable/
│   │       │       │   ├── background.png
│   │       │       │   └── launch_background.xml
│   │       │       ├── drawable-hdpi/
│   │       │       │   ├── android12splash.png
│   │       │       │   ├── branding.png
│   │       │       │   └── splash.png
│   │       │       ├── drawable-hdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-mdpi/
│   │       │       │   ├── android12splash.png
│   │       │       │   ├── branding.png
│   │       │       │   └── splash.png
│   │       │       ├── drawable-mdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-night-hdpi/
│   │       │       │   └── android12splash.png
│   │       │       ├── drawable-night-hdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-night-mdpi/
│   │       │       │   └── android12splash.png
│   │       │       ├── drawable-night-mdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-night-xhdpi/
│   │       │       │   └── android12splash.png
│   │       │       ├── drawable-night-xhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-night-xxhdpi/
│   │       │       │   └── android12splash.png
│   │       │       ├── drawable-night-xxhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-night-xxxhdpi/
│   │       │       │   └── android12splash.png
│   │       │       ├── drawable-night-xxxhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-v21/
│   │       │       │   ├── background.png
│   │       │       │   └── launch_background.xml
│   │       │       ├── drawable-xhdpi/
│   │       │       │   ├── android12splash.png
│   │       │       │   ├── branding.png
│   │       │       │   └── splash.png
│   │       │       ├── drawable-xhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-xxhdpi/
│   │       │       │   ├── android12splash.png
│   │       │       │   ├── branding.png
│   │       │       │   └── splash.png
│   │       │       ├── drawable-xxhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── drawable-xxxhdpi/
│   │       │       │   ├── android12splash.png
│   │       │       │   ├── branding.png
│   │       │       │   └── splash.png
│   │       │       ├── drawable-xxxhdpi-v31/
│   │       │       │   └── android12branding.png
│   │       │       ├── mipmap-hdpi/
│   │       │       │   └── ic_launcher.png
│   │       │       ├── mipmap-mdpi/
│   │       │       │   └── ic_launcher.png
│   │       │       ├── mipmap-xhdpi/
│   │       │       │   └── ic_launcher.png
│   │       │       ├── mipmap-xxhdpi/
│   │       │       │   └── ic_launcher.png
│   │       │       ├── mipmap-xxxhdpi/
│   │       │       │   └── ic_launcher.png
│   │       │       ├── values/
│   │       │       │   └── styles.xml
│   │       │       ├── values-night/
│   │       │       │   └── styles.xml
│   │       │       ├── values-night-v31/
│   │       │       │   └── styles.xml
│   │       │       └── values-v31/
│   │       │           └── styles.xml
│   │       └── profile/
│   │           └── AndroidManifest.xml
│   ├── build.gradle
│   ├── gradle/
│   │   └── wrapper/
│   │       └── gradle-wrapper.properties
│   ├── gradle.properties
│   └── settings.gradle
├── assets/
│   └── images/
│       ├── OnBoarding1.jpg
│       ├── OnBoarding2.jpg
│       ├── OnBoarding3.jpg
│       ├── donorConnect.png
│       ├── donorConnect1.png
│       ├── empty_calendar.png
│       ├── google.png
│       ├── home.png
│       ├── home_image1.png
│       ├── home_image2.png
│       ├── launcher_icon.png
│       ├── launcher_icon1.png
│       ├── login.jpg
│       ├── logo.png
│       ├── logo1.png
│       └── signup.jpg
├── devtools_options.yaml
├── firebase.json
├── ios/
│   ├── Flutter/
│   │   ├── AppFrameworkInfo.plist
│   │   ├── Debug.xcconfig
│   │   └── Release.xcconfig
│   ├── Podfile
│   ├── Podfile.lock
│   ├── Runner/
│   │   ├── AppDelegate.swift
│   │   ├── Assets.xcassets/
│   │   │   ├── AppIcon.appiconset/
│   │   │   │   ├── Contents.json
│   │   │   │   ├── Icon-App-1024x1024@1x.png
│   │   │   │   ├── Icon-App-20x20@1x.png
│   │   │   │   ├── Icon-App-20x20@2x.png
│   │   │   │   ├── Icon-App-20x20@3x.png
│   │   │   │   ├── Icon-App-29x29@1x.png
│   │   │   │   ├── Icon-App-29x29@2x.png
│   │   │   │   ├── Icon-App-29x29@3x.png
│   │   │   │   ├── Icon-App-38x38@2x.png
│   │   │   │   ├── Icon-App-38x38@3x.png
│   │   │   │   ├── Icon-App-40x40@1x.png
│   │   │   │   ├── Icon-App-40x40@2x.png
│   │   │   │   ├── Icon-App-40x40@3x.png
│   │   │   │   ├── Icon-App-60x60@2x.png
│   │   │   │   ├── Icon-App-60x60@3x.png
│   │   │   │   ├── Icon-App-64x64@2x.png
│   │   │   │   ├── Icon-App-64x64@3x.png
│   │   │   │   ├── Icon-App-68x68@2x.png
│   │   │   │   ├── Icon-App-76x76@1x.png
│   │   │   │   ├── Icon-App-76x76@2x.png
│   │   │   │   └── Icon-App-83.5x83.5@2x.png
│   │   │   ├── BrandingImage.imageset/
│   │   │   │   ├── BrandingImage.png
│   │   │   │   ├── BrandingImage@2x.png
│   │   │   │   ├── BrandingImage@3x.png
│   │   │   │   └── Contents.json
│   │   │   ├── LaunchBackground.imageset/
│   │   │   │   ├── Contents.json
│   │   │   │   └── background.png
│   │   │   └── LaunchImage.imageset/
│   │   │       ├── Contents.json
│   │   │       ├── LaunchImage.png
│   │   │       ├── LaunchImage@2x.png
│   │   │       ├── LaunchImage@3x.png
│   │   │       └── README.md
│   │   ├── Base.lproj/
│   │   │   ├── LaunchScreen.storyboard
│   │   │   └── Main.storyboard
│   │   ├── GoogleService-Info.plist
│   │   ├── Info.plist
│   │   └── Runner-Bridging-Header.h
│   ├── Runner.xcodeproj/
│   │   ├── project.pbxproj
│   │   ├── project.xcworkspace/
│   │   │   ├── contents.xcworkspacedata
│   │   │   └── xcshareddata/
│   │   │       ├── IDEWorkspaceChecks.plist
│   │   │       └── WorkspaceSettings.xcsettings
│   │   └── xcshareddata/
│   │       └── xcschemes/
│   │           └── Runner.xcscheme
│   ├── Runner.xcworkspace/
│   │   ├── contents.xcworkspacedata
│   │   └── xcshareddata/
│   │       ├── IDEWorkspaceChecks.plist
│   │       └── WorkspaceSettings.xcsettings
│   └── RunnerTests/
│       └── RunnerTests.swift
├── l10n.yaml
├── lib/
│   ├── Utils/
│   │   ├── Textbox.dart
│   │   ├── constants/
│   │   │   ├── images_string.dart
│   │   │   └── text_string.dart
│   │   ├── show_snackbar.dart
│   │   └── validation_helpers.dart
│   ├── cubit/
│   │   ├── auth/
│   │   │   ├── auth_cubit.dart
│   │   │   └── auth_state.dart
│   │   ├── forgot_password/
│   │   │   ├── forgot_password_cubit.dart
│   │   │   └── forgot_password_state.dart
│   │   ├── locate_blood_banks/
│   │   │   └── locate_blood_banks_cubit.dart
│   │   ├── profile/
│   │   │   ├── profile_cubit.dart
│   │   │   └── profile_state.dart
│   │   └── theme_toggle/
│   │       ├── theme_cubit.dart
│   │       └── value_cubit.dart
│   ├── firebase_options.dart
│   ├── l10n/
│   │   ├── intl_en.arb
│   │   ├── intl_gu.arb
│   │   └── intl_hi.arb
│   ├── language/
│   │   ├── cubit/
│   │   │   └── language_cubit.dart
│   │   ├── helper/
│   │   │   ├── langauge_popup.dart
│   │   │   ├── language.dart
│   │   │   └── language_extention.dart
│   │   └── services/
│   │       └── language_repositoty.dart
│   ├── main.dart
│   ├── models/
│   │   ├── user_model.dart
│   │   └── verification_status.dart
│   ├── secrets.dart
│   ├── services/
│   │   ├── blood_bank_service.dart
│   │   └── verification_service.dart
│   └── views/
│       ├── common_widgets/
│       │   ├── events_card.dart
│       │   ├── home_card.dart
│       │   ├── home_card_form.dart
│       │   └── toggle_button.dart
│       ├── controllers/
│       │   └── onboarding/
│       │       └── onboarding_controller.dart
│       ├── pages/
│       │   ├── camps/
│       │   │   ├── calendarPage.dart
│       │   │   └── campsPage.dart
│       │   ├── forgot_password/
│       │   │   ├── change-password.dart
│       │   │   └── forgot-password.dart
│       │   ├── learn_about_donation/
│       │   │   └── learn_about_donation.dart
│       │   ├── locate_blood_banks/
│       │   │   └── locate_blood_banks.dart
│       │   ├── login/
│       │   │   └── login.dart
│       │   ├── main_home/
│       │   │   ├── bottom_nav.dart
│       │   │   ├── chatbot.dart
│       │   │   ├── home_pages/
│       │   │   │   └── home_screen.dart
│       │   │   └── homepage.dart
│       │   ├── onboarding/
│       │   │   ├── onboarding.dart
│       │   │   └── widgets/
│       │   │       ├── onboarding_dot_navigation.dart
│       │   │       ├── onboarding_next_button.dart
│       │   │       ├── onboarding_page.dart
│       │   │       └── onboarding_skip.dart
│       │   ├── profile/
│       │   │   └── profile_screen.dart
│       │   ├── register/
│       │   │   └── signup.dart
│       │   ├── search/
│       │   │   ├── search_screen.dart
│       │   │   └── widgets/
│       │   │       ├── blood_bank_form.dart
│       │   │       └── blood_donor_form.dart
│       │   └── welcome/
│       │       └── welcome_screen.dart
│       └── verificationform.dart
├── linux/
│   ├── CMakeLists.txt
│   ├── flutter/
│   │   ├── CMakeLists.txt
│   │   ├── generated_plugin_registrant.cc
│   │   ├── generated_plugin_registrant.h
│   │   └── generated_plugins.cmake
│   ├── main.cc
│   ├── my_application.cc
│   └── my_application.h
├── macos/
│   ├── Flutter/
│   │   ├── Flutter-Debug.xcconfig
│   │   ├── Flutter-Release.xcconfig
│   │   └── GeneratedPluginRegistrant.swift
│   ├── Podfile
│   ├── Runner/
│   │   ├── AppDelegate.swift
│   │   ├── Assets.xcassets/
│   │   │   └── AppIcon.appiconset/
│   │   │       ├── Contents.json
│   │   │       ├── app_icon_1024.png
│   │   │       ├── app_icon_128.png
│   │   │       ├── app_icon_16.png
│   │   │       ├── app_icon_256.png
│   │   │       ├── app_icon_32.png
│   │   │       ├── app_icon_512.png
│   │   │       └── app_icon_64.png
│   │   ├── Base.lproj/
│   │   │   └── MainMenu.xib
│   │   ├── Configs/
│   │   │   ├── AppInfo.xcconfig
│   │   │   ├── Debug.xcconfig
│   │   │   ├── Release.xcconfig
│   │   │   └── Warnings.xcconfig
│   │   ├── DebugProfile.entitlements
│   │   ├── GoogleService-Info.plist
│   │   ├── Info.plist
│   │   ├── MainFlutterWindow.swift
│   │   └── Release.entitlements
│   ├── Runner.xcodeproj/
│   │   ├── project.pbxproj
│   │   ├── project.xcworkspace/
│   │   │   └── xcshareddata/
│   │   │       └── IDEWorkspaceChecks.plist
│   │   └── xcshareddata/
│   │       └── xcschemes/
│   │           └── Runner.xcscheme
│   ├── Runner.xcworkspace/
│   │   ├── contents.xcworkspacedata
│   │   └── xcshareddata/
│   │       └── IDEWorkspaceChecks.plist
│   └── RunnerTests/
│       └── RunnerTests.swift
├── native_splash.yaml
├── pubspec.lock
├── pubspec.yaml
├── readme/
│   └── gssoc_ext_2024.png
├── repo_structure.txt
├── test/
│   └── widget_test.dart
├── web/
│   ├── favicon.png
│   ├── icons/
│   │   ├── Icon-192.png
│   │   ├── Icon-512.png
│   │   ├── Icon-maskable-192.png
│   │   └── Icon-maskable-512.png
│   ├── index.html
│   ├── manifest.json
│   └── splash/
│       └── img/
│           ├── branding-1x.png
│           ├── branding-2x.png
│           ├── branding-3x.png
│           ├── branding-4x.png
│           ├── branding-dark-1x.png
│           ├── branding-dark-2x.png
│           ├── branding-dark-3x.png
│           ├── branding-dark-4x.png
│           ├── dark-1x.png
│           ├── dark-2x.png
│           ├── dark-3x.png
│           ├── dark-4x.png
│           ├── light-1x.png
│           ├── light-2x.png
│           ├── light-3x.png
│           └── light-4x.png
└── windows/
    ├── CMakeLists.txt
    ├── flutter/
    │   ├── CMakeLists.txt
    │   ├── generated_plugin_registrant.cc
    │   ├── generated_plugin_registrant.h
    │   └── generated_plugins.cmake
    └── runner/
        ├── CMakeLists.txt
        ├── Runner.rc
        ├── flutter_window.cpp
        ├── flutter_window.h
        ├── main.cpp
        ├── resource.h
        ├── resources/
        │   └── app_icon.ico
        ├── runner.exe.manifest
        ├── utils.cpp
        ├── utils.h
        ├── win32_window.cpp
        └── win32_window.h
```
<!-- END_STRUCTURE -->