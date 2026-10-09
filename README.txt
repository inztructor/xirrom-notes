FlipNote APK builder (no Android Studio needed)

1. Create a free account at github.com and make a new repository (any name).
2. In the repository: Add file > Upload files. Drag in everything from this folder
   (www, package.json, capacitor.config.json, .github). Commit.
   If the hidden ".github" folder does not upload, use Add file > Create new file,
   type  .github/workflows/build.yml  as the name, and paste in the contents of build.yml.
3. Open the Actions tab. The "Build APK" run starts by itself (or click Run workflow).
4. When it turns green (about 5-10 minutes), open the run and download "FlipNote-apk" under Artifacts.
5. Unzip it, copy app-debug.apk to your phone and install it (allow "install unknown apps").

To update the app later: replace www/index.html in the repository and commit. A new APK is built.
