WEALTH LAB - BUILD THE APK ON GITHUB (no computer needed)

1. On github.com create a repository (or use the one you made before). Public or private both work.
2. Tap Add file > Upload files and upload these two files: index.html and icons.zip (your logo). Commit.
3. Tap Add file > Create new file. In the name box type exactly:  .github/workflows/build-apk.yml
   Open build-apk.yml from this folder, copy everything, paste it into the big box, then Commit.
4. Open the Actions tab. Pick "Build Wealth Lab APK" and tap Run workflow if it did not start by itself. It takes about 5 to 10 minutes.
5. When it shows a green tick, open that run, scroll to Artifacts, download WealthLab-apk, extract it, and open app-debug.apk.
6. Android will ask to allow installs from your browser or Files app. Allow it. If Play Protect warns that the app is unrecognised, choose Install anyway.

If the run shows a red cross, open it, copy the error text, and send it to me.
