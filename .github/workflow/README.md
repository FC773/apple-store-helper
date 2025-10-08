# Apple Store Helper GitHub Actions

這是一個範例 GitHub Actions，用來自動監控台灣 Apple Store iPhone 17 Pro 宇宙橙 256GB 補貨。
當檢測到有貨時，會透過 Bark 推播通知你。

## 使用方法

1. Fork 或建立自己的 GitHub Repository，並上傳整個資料夾。
2. 修改 stock-check.yml 中的 BARK_URL，貼上你的 Bark 推播網址。
3. 前往 GitHub Actions，啟用工作流程。
4. GitHub Actions 會每 10 分鐘自動檢查庫存。