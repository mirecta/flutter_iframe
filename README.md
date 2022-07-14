# test

Show how to flutter app can work in iframe and how can rest of webpage comunicate with it
 - Flutter parse url parameters from iframe uri
 - Flutter can send messages to parent window
 - Parent window send messages to flutter app 
 
## Getting Started

Build by 
```
flutter build web --dart-define=FLUTTER_WEB_CANVASKIT_URL="canvaskit/"
```

then copy files to document root
```
mkdir document_root
cp -r build/web/assets document_root/
cp -r build/web/canvaskit document_root/
cp -r build/web/icons document_root/
cp build/web/favicon.png  build/web/flutter.js  build/web/flutter_service_worker.js build/web/main.dart.js  build/web/manifest.json document_root/
cp build/web/index.html document_root/index2.html
cp html/index.html document_root/
```

Done
