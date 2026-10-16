# House Hunter Public OTA Data Repository

此倉庫為 [台灣房產獵人 (House Hunter)](https://github.com/brighttw/house-hunter) 之公開 OTA 種子資料發布倉庫。

由主倉庫 GitHub Actions 每日定時自動更新並推送，提供 Android App 端以 GitHub Raw 快速非阻塞增量同步：

- `assets/seed_db/initial_rates.json`：全台灣最新銀行房貸基準利率、新青安方案與成數
- `assets/seed_db/lvr_community_prices.json`：內政部實價登錄社區與行政區行情
- `assets/seed_db/incidents_seed.json`：司法院裁判書非自然身故/事故公開索引
- `assets/seed_db/incidents_fts.db`：SQLite FTS5 離線全文檢索庫
