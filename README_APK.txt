WOLF WOLF DOG v0.1 — PROJETO PREPARADO PARA APK

Este pacote é um projeto Capacitor pronto para empacotar a versão web do jogo como aplicativo Android.

IMPORTANTE:
- Este ZIP NÃO é o APK pronto.
- O APK precisa ser compilado com Android SDK/Gradle.
- O jogo continua usando Phaser via CDN, portanto a primeira abertura precisa de internet.
- Para gerar APK no celular, use um ambiente Android/Linux que consiga instalar Node.js, npm e Android SDK.

Fluxo:
1. Extraia o ZIP.
2. Abra um terminal na pasta.
3. Instale as dependências:
   npm install
4. Gere a pasta Android:
   npx cap add android
5. Sincronize:
   npx cap sync android
6. Compile um APK debug:
   cd android
   ./gradlew assembleDebug

O APK de debug normalmente ficará em:
android/app/build/outputs/apk/debug/app-debug.apk

Se o ambiente não tiver Java/Android SDK/Gradle, primeiro será necessário configurar essas ferramentas.
