# Elemental Shadows - Android APK (ARAZULA Production)

STEP BY STEP (no Android Studio needed, a computer is easiest)

1. Go to github.com and sign up (free). Verify your email.
2. Click the "+" (top right) > "New repository". Name it elemental-shadows. Choose Public. Click "Create repository".
3. Unzip this project on your computer.
4. In your new repository click "uploading an existing file".
5. Open the unzipped folder and drag EVERYTHING inside it into the browser:
   the www folder, the .github folder, package.json, capacitor.config.json, README.md, build.yml.txt.
   (If you cannot see the .github folder, turn on "show hidden files", see step 5b.)
   Click "Commit changes".
5b. If .github did not upload: in the repository click "Add file" > "Create new file".
   In the name box type exactly:  .github/workflows/build.yml
   Open build.yml.txt, copy all its text, paste it into the big box, click "Commit changes".
6. Click the "Actions" tab. A job called "Build APK" starts by itself (about 5 minutes).
   If asked, click "I understand my workflows, go ahead and enable them".
   If it does not start: click "Build APK" on the left > "Run workflow" > "Run workflow".
7. When it shows a green check, click the run, scroll to "Artifacts" and download ElementalShadows-APK.
8. Unzip the download. Inside is app-debug.apk. Send it to your phone (USB, Google Drive, Telegram, email).
9. On the phone open app-debug.apk. If Android blocks it, tap Settings and turn on "Allow from this source" (Install unknown apps), then go back and tap Install.
10. Open Elemental Shadows. Rotate to landscape. The on-screen buttons are on by default:
    left pad = move/jump/crouch, right = LIGHT, HEAVY, ELEM, ULT, BLOCK, top right = pause.

Red X in Actions? Open the failed step and send me the error text.
