# ANI — Phone-only APK Build

This project contains a GitHub Actions workflow for building the Android APK in the cloud, so a PC/Android Studio is not required.

## Build from an Android phone

1. Create/sign in to a GitHub account.
2. Create a new repository named `ANI-Talking-Cartoon`.
3. Upload the contents of this project into the repository. Upload the project files/folders, not just the ZIP file.
4. Open **Actions**.
5. Select **Build ANI APK**.
6. Tap **Run workflow**.
7. Wait for the workflow to finish successfully.
8. Open the completed run.
9. Under **Artifacts**, download `ANI-debug-apk`.
10. Extract the downloaded ZIP and install `app-debug.apk`.

## Important
The current ANI project uses the existing local demo reply engine. A real ChatGPT/OpenAI-powered conversation requires a secure backend/API integration. Do not put a private API key directly inside the Android APK.
