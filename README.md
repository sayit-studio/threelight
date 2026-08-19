# 三光米提案簡報｜GitHub Pages 版本

此資料夾已整理為可直接部署的靜態網站：

- `index.html`：網站首頁
- `lumirice-assets/`：網站實際使用的 WebP 圖片
- `.nojekyll`：讓 GitHub Pages 直接依照靜態檔案發布

## 發布方式

1. 將此資料夾內的全部檔案上傳到 GitHub 儲存庫根目錄。
2. 前往儲存庫的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**。
4. 選擇 `main` 分支及 `/ (root)`，按下 **Save**。
5. 等待 GitHub Pages 完成發布，即可將公開網址提供給客戶。

所有圖片均使用相對路徑，因此可部署在專案型 GitHub Pages 網址下，不依賴本機檔案路徑。
