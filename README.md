# 香港實時生活儀表板 - Android APK 專案

專為 Samsung Galaxy Tab S9 及 Android 平板設計的實時儀表板應用程式。

## 快速打包 APK 的 3 種方法：

### 方法 1：GitHub Actions 免費 1 鍵線上打包 (最推薦)
1. 將此專案上傳至您的 GitHub Repository。
2. 進入 Repository 的 `Actions` 標籤頁。
3. 點選 `Build Android APK` -> `Run workflow`。
4. 建置完成後即可直接下載 `HongKong_Dashboard_APK` (.apk 檔案)。

### 方法 2：Android Studio 本地編譯
1. 使用 Android Studio 開啟此專案目錄。
2. 點選頂部選單 `Build` -> `Build Bundle(s) / APK(s)` -> `Build APK(s)`。
3. 編譯完成後點擊 `locate` 即可取得 `app-debug.apk`。

### 方法 3：PWA / Web2APK / Bubblewrap
- 直接使用瀏覽器打開 `HongKong_Dashboard_TabS9.html`，點選「新增至主螢幕」即可全螢幕獨立運行（效果與 APK 完全一致）。
