# Minecraft Voxel Edition (Cross-Platform Online)

Точная браузерная 3D-копия Minecraft с собственным воксельным движком (Three.js), 16x16 пиксельными текстурами, системой крафта и кроссплатформенным мультиплеером в реальном времени (WebSocket + WebRTC P2P PeerJS для работы на GitHub Pages).

## Как включить ссылку GitHub Pages (если открывается 404 или требуется настройка):
В репозитории уже лежит готовая собранная игра в папке `/docs`!
1. Откройте на GitHub вкладку **Settings** -> **Pages**.
2. В разделе **Build and deployment** -> **Source** выберите **Deploy from a branch** (вместо GitHub Actions).
3. Выберите ветку **`main`** и папку **`/docs`**, затем нажмите **Save**.
4. Через 30 секунд ваша игра будет доступна по ссылке GitHub Pages!

## Запуск локально с сервером
```bash
npm install
npm run dev
```
