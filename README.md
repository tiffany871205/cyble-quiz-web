# Cyble 題庫網頁

## 本機啟動

```bash
cd ~/Desktop/未命名檔案夾/cyble-knowledge/quiz-web
python3 -m http.server 8081
```

開啟 http://localhost:8081 。不要直接雙擊 `index.html`，瀏覽器可能禁止從 `file://` 讀取 JSON。

## 功能

- 247 題：73 個核心知識點各延伸三種問法，另有 28 題獨立深入實務題。
- 題庫搜尋、分類與題型篩選。
- 四選一模擬考、答案解析、錯題複習、成績紀錄、學習資料匯出與匯入。
- 紀錄僅存在本機瀏覽器 localStorage，與 Bitsight 題庫分開。

## 來源與限制

內容依據 Cyble 官方網站、Cyble Vision 2025.08 操作手冊及 2026.08 品牌管理／暗網情資簡報整理。官網資料是產品能力的公開說明；個別功能、監控頻率、下架 SLA 與授權需依客戶合約確認。題目為自編練習，不是官方認證考題。某些題目為同一知識點的不同問法，不能視為 247 個獨立功能。

Notion 完整貼上版：`../Cyble_完整知識與題庫_Notion貼上版.md`。

## 這一版新增的資料來源

- [Cyble Vision 官方產品頁](https://cyble.com/products/cyble-vision/)：產品模組與 Detect／Validate／Closure。
- [Cyble FAQ](https://cyble.com/faqs/)：EASM、STIX/TAXII、API 與整合差異。
- [Cyble 品牌保護](https://cyble.com/solutions/brand-intelligence/)：網域、社群、App 與暗網監控。
- [Cyble Takedown](https://cyble.com/solutions/takedown-services/)：偵測、驗證與處理流程。
- 《Cyble Vision_操作手冊_v1.5_20260519》：儀表板、Website Watermarking、Ransomware Incidents 等。
- 《安泰銀行_偽冒偵測及下架服務專案_Cyble 品牌偽冒偵測模組操作手冊》：Takedown Tracker、Whitelist URLs、Report Incident 等。

**提醒**：手冊題的來源為上傳文件，不代表相同功能在所有租戶皆已啟用；部分題目為實務推論，並非逐字摘錄。
