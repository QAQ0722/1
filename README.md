# 火星車 V4.22

本專案包含避障模擬器與實車地圖。實車地圖下方可直接按「清除地圖」。

## 發布到 GitHub Pages

1. 將本資料夾中的 `index.html`、`.nojekyll` 和 `README.md` 上傳到 GitHub 儲存庫的 `main` 分支根目錄。
2. 在儲存庫開啟 **Settings → Pages**，選擇 **Deploy from a branch**。
3. 選擇 **main** 和 **/(root)**，按 **Save**。發布完成後，從 Pages 設定頁開啟網站。

## 接實車

用支援 Web Serial 的桌面 Chrome 或 Edge 開啟網頁，插上 Arduino 的 USB，按實車區的序列埠連線按鈕，選擇板子的序列埠。離線時也可以下載 `index.html` 後直接開啟。
