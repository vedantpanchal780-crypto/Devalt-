# DevVault APK

1. Create a new GitHub repository and upload everything in this folder
   (keep the `.github/workflows/build.yml` path and the `www/` folder).
2. Open the **Actions** tab. The build starts on every push; you can also run
   "Build Android APK" manually with **Run workflow**.
3. When it finishes (about 5-8 minutes), open the run and download the
   **DevVault-apk** artifact. Unzip it and install `app-debug.apk` on your phone
   (allow "install unknown apps").

To change the app, edit `www/index.html` and push again.
