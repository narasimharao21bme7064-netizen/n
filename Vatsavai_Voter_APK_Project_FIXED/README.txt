OPTION A - GitHub (no installs):
1. github.com lo new repository create cheyyandi, ee folder lo anni files (.github folder tho saha) upload cheyyandi.
2. Actions tab -> "Build APK" -> Run workflow.
3. 3-5 min tarvata run open chesi "voter-app-apk" artifact download cheyyandi -> app-debug.apk.

OPTION B - Own computer (Node.js 18+, JDK 17, Android Studio):
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
APK: android/app/build/outputs/apk/debug/app-debug.apk
