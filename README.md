# Multi-Timbre Keyboard

多音色鍵盤：24 種樂器、每種樂器獨立設定（音高、A4 基準音、音色、音量、響度、殘響、起音、釋放）、延音與抖音開關。

整個網站只有一個檔案 `index.html`，沒有任何外部相依，直接放上 GitHub Pages 即可。

## 發布到 GitHub Pages

1. 登入 GitHub，點右上角 `+` → `New repository`。
2. Repository name 自訂（例如 `keyboard`），選 `Public`，按 `Create repository`。
3. 在新的 repository 頁面點 `uploading an existing file`（或 `Add file` → `Upload files`）。
4. 上傳 `index.html`（`README.md` 可有可無），按 `Commit changes`。
5. 到 `Settings` → `Pages`，在 `Build and deployment` 的 `Source` 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`，按 `Save`。
6. 等 1 到 2 分鐘，頁面上方會出現網址：`https://你的帳號.github.io/keyboard/`

## 更新網站

回到 repository，點 `index.html` → 右上角鉛筆圖示或 `Add file` → `Upload files`，用新的 `index.html` 覆蓋，按 `Commit changes`，約 1 分鐘後網站就會更新。

## 注意

- 設定（各樂器參數、選到的樂器）會存在使用者自己瀏覽器的 localStorage，換裝置不會同步。
- 手機或平板第一次打開若沒有聲音，先按一下 `REFRESH SOUND`。
- iPad：用 Safari 開啟後，分享 → `加入主畫面`，就能以全螢幕開啟。
