KALC — Android Calculator
KALC is a Java-based Android calculator mini-project created during my Netcamp Android development course.
Features
- Whole-number addition, subtraction, multiplication, division, and modulo (%)
- Square (x²) operation
- Clear/reset the current calculation
- Text-to-speech reads the result aloud in English at a slower rate
- Vibration feedback when calculator buttons are tapped
- Dark interface with gray number keys and orange operation buttons
Built With
- Java 11
- Android Studio and Android SDK
- XML layouts
- Android TextToSpeech and Vibrator APIs
- Gradle
Run the Project
1. Clone or download this repository.
2. Open the project root in Android Studio and let Gradle sync.
3. Run it on an emulator or Android device running Android 7.0 (API 24) or higher.
To build a debug APK from the project root:gradlew.bat assembleDebug

On macOS or Linux, use:./gradlew assembleDebug
The debug APK is generated at app/build/outputs/apk/debug/app-debug.apk.Download the APK

After publishing a GitHub Release, download the installable APK from this repository’s Releases page.

Acknowledgments

Built as a mini-project during my Netcamp course, with guidance from Santu Purkait Sir. Special thanks to Manas Dwivedi for helping with the logic in selected parts of the code.


Possible Future Improvements
- Decimal input and improved input validation
- Standard operator precedence and division-by-zero handling
- Calculation history
