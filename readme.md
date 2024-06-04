# Bookmarks Chromium Extension

由於 Chromium 的主介面沒有書籤按鈕，因此設計了這個擴充功能，只要將圖示按鈕固定在主介面的工具列，就能一鍵按出 chrome://bookmarks 頁面。

基於 Chromium 的 Chrome 也適用！至於 Opera、Vivaldi、Edge 的主介面本來就有書籤按鈕，不需要使用本擴充功能。

本擴充功能程式碼不到 10 行，程式精簡，不用擔心會拖累性能或危害系統，你不妨檢視看看原始碼，以便安心使用。

## 如何使用

  * 按「擴充功能」圖示。
  * 按「管理擴充功能」選項。
  * 開啟「開發人員模式」。
  * 按「載入未封裝項目」。
  * 在檔案對話視窗中，切換到 Bookmarks 資料夾，然後按「選擇資料夾」，即可安裝本擴充功能。
  * 按「擴充功能」圖示，將 Bookmarks 固定，即可在主介面的工具列直接按圖示開啟 chrome://bookmarks 書籤。

## 補充

如果你希望開啟書籤頁面時，能預設停留在「其他書籤」，可以用純文字編輯器開啟 background.js，將 chrome://bookmarks 改為 chrome://bookmarks/?id=2。