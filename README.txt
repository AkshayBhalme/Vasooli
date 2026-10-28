1. GitHub: New repository -> name: vasuli -> Create.
2. "uploading an existing file" -> drag ALL files/folders from this zip (www, package.json, capacitor.config.json, .github) -> Commit.
3. If the .github folder did not upload: Add file -> Create new file -> name: .github/workflows/build.yml -> paste build.yml contents -> Commit.
4. Actions tab -> "Build APK" -> wait ~10 min (green tick) -> open run -> Artifacts -> vasuli-apk -> download, unzip, install app-debug.apk on the phone.
5. To change the app: edit www/index.html on GitHub (pencil icon) -> Commit -> new APK builds automatically.
