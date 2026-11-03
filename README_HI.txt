ULTIMATE STREET RACING 3D — ANDROID PROJECT

यह Android Studio का source project है। इसमें Stage 6 का आपका HTML गेम Android WebView में landscape/full-screen मोड में चलता है।

महत्वपूर्ण:
- यह ZIP APK नहीं है; यह APK बनाने के लिए project source है।
- APK बनाने के लिए Android Studio और Android SDK वाला कंप्यूटर चाहिए।
- गेम Three.js को jsDelivr CDN से लोड करता है, इसलिए पहली बार और गेम खेलते समय इंटरनेट जरूरी है।
- Android Studio में इस फ़ोल्डर को Open करें, Gradle Sync करें, फिर Build > Build APK(s) चुनें।
- गेम की मौजूदा सुविधाएँ Stage 6 HTML के अनुसार ही हैं; इसमें नए फीचर जोड़ने का दावा नहीं किया गया है।


GITHUB ACTIONS SE APK BUILD:
1. Project ke saare extracted files GitHub repository ke main branch mein upload karein.
2. .github/workflows/android.yml file bhi repository mein honi chahiye.
3. GitHub repository ke Actions tab mein "Build Android APK" workflow kholein.
4. "Run workflow" dabayein (ya main branch par push ke baad automatic run hoga).
5. Build complete hone par workflow run ke Artifacts section se APK download karein.
