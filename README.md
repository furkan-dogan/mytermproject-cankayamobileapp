<h1>📱 CankayaMobileApp</h1>
Our project is Mobile Application for Cankaya University. We aim to add QR Attendance, QR id check for school busses, and online course evaluation questionnaire features to our application.

# Advisor
* [Prof. Dr. Ahmet COŞAR](http://www.cankaya.edu.tr/akademik_birimler/cv/Prof.Dr.AhmetCO%C5%9EAR.html)

----

# Local development
These instructions should get you set up ready to work on CankayaMobileApp 🙌

## Getting Started
# Setting up the development environment (Windows)
You can watch install video -> https://www.youtube.com/watch?v=6tEV6H07Fd8

1. Download and Install Android Studio, Node.js, Java SE Development Kit 11.0.18
2. Open Android Studio, then find and clik SDK Manager
3. Choose 'Android SDK Platform 30', 'Source for Android 30', 'Intel x86 Atom_64 System Image' and 'Google APIs Intel x86 Atom_64 System Image' on Android 11.0(R) in SDK Platforms.
4. Choose 30.0.0 version in SDK Tools, then uncheck 'Show Package Details' and check 'Android Emulator' and 'Android SDK Platform Tools', then Apply.
5.In windows search bar, search 'Advanced System Settings' and click. Then, click 'Environment Variables'. 
6. In system variables, click new and add 'Android SDK Locations' with new name 'ANDROID_HOME'.
7. In system variables, click 'Path' -> 'Edit' -> 'New' then, add end of Android SDK Locations' 'platform-tools'. As an example: "%LOCALAPPDATA\Android\Sdk\platform-tools".
8. Go to "Program Files/Java" then, rename the latest file to "jdk". Then choose and copy "jdk" file path name.
9. In system variables, click new and paste it with new name 'JAVA_HOME'.
10. Open Android Studio -> New Project -> Empty Activity -> Change Language to 'Java' and Change minimum SDK to 'API 30'.
11. Open settings on Android Studio. Choose 'Build, execution, deployment'->'Build Toold'->'Gradle'. Change 'Gradle JDK' to 'Android Studio java home'.
12. Create device from Android studio. Choose emulator you like. Then click 'x86 images', then Choose Target -> 'Android 11.0 (Google APIs)' then Finish. 


You can use any IDE (like WebStorm, Visual Studio Code etc.) or code editing tool for developing on any platform. Use your favorite!
