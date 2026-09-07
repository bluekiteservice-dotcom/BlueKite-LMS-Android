BLUE KITE LMS - ANDROID APK

This project opens the existing Google Apps Script LMS inside a native Android WebView.
The backend/database are unchanged.

Apps Script URL is configured in:
app/src/main/java/com/bluekite/lms/MainActivity.java

NO Android Studio is required if you build with GitHub Actions.
1. Create a GitHub repository.
2. Upload all files/folders from this project.
3. Open Actions -> Build BlueKite LMS APK -> Run workflow.
4. Download the generated artifact: BlueKite-LMS-debug-apk.
5. Extract the artifact and install app-debug.apk on Android.

For a production/release APK, use a signing key before distributing widely.
