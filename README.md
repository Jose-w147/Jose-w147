# AimColor Android Project (WebView)

Projeto Android minimal que carrega a página `aimcolor_mira.html` (WebView) com a mira/detector.

Build

- Abra o projeto no Android Studio e construa normalmente (compileSdk 33, targetSdk 33).
- Ou use Gradle no terminal: `./gradlew assembleDebug` para gerar `app-debug.apk`.

Observações

- O APK gerado aqui é debug. Para publicação, assine com sua chave release.
- A feature de "compartilhar tela" via getDisplayMedia pode não funcionar em WebView dependendo do dispositivo/versão do WebView.
