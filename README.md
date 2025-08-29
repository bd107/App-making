HelloWorld - simple Android Java app (debug APK workflow)

How to use (mobile-only):
1. Create a new public GitHub repository (or use an existing one).
2. Upload the files from this archive preserving paths (GitHub web/mobile "Create new file" accepts full path).
3. Commit all files to the main branch.
4. Go to the repository Actions tab, open "Android Debug APK" workflow and run it (or push to main).
5. After successful build download the artifact named debug-apk and install the APK on your phone.

Note: This workflow builds a debug APK (auto-signed). For production you need a release key (keystore).
