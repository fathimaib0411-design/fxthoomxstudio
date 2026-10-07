# fxthoomxstudio (Android app)

A fictional UGC creator profile for a concept pitch, built into an installable Android APK
by GitHub Actions. All names, captions, comments and view counts are made up.

## Get the APK

1. Create a new repository on github.com. Public or private both work.
2. Upload everything in this folder to it (`www/`, `android-icons/`, `.github/`, `package.json`,
   `capacitor.config.json`, `.gitignore`, `README.md`) and commit to the `main` branch.
3. Open the **Actions** tab. "Build Android APK" starts by itself and takes about 5 to 8 minutes.
4. When it shows a green tick, open the **Releases** section on the right of the repo's main page
   and download `fxthoomxstudio.apk`. The same file is under the finished run's **Artifacts**.

## Install it

1. Send the APK to your Android phone, or open the Release page on the phone and download it there.
2. Tap the downloaded file. If asked, allow **Install unknown apps** for your browser or Files app.
3. If Google Play Protect warns about an unknown app, choose **Install anyway**. That warning appears
   for any APK that is not from the Play Store.

## Change it later

Edit `www/index.html` or the photos and videos in `www/assets/`, then commit.
A new APK is built and published as a new Release every time.

## Notes

- This is a debug-signed APK. It installs and runs normally on any Android phone.
- Publishing on Google Play needs a release-signed build and a Play developer account.
- iPhones cannot install APK files.
