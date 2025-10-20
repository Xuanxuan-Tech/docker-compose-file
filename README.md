
# 🚀 應用程式與配置清單

以下是目前已收錄的 Docker Compose 配置檔案列表：

| 應用程式/服務 | 配置檔案名稱 | 主要功能標籤 |
| :--- | :--- | :--- |
| **Odoo** | `docker-compose.odoo.yml` | ERP 系統 / 商業應用 |
| **ELK Stack** | `docker-compose.elk.yml` | 日誌與搜索分析 / 監控 |
| **Grafana** | `docker-compose.grafana.yml` | 數據視覺化 / 儀表板 |
| **Metabase** | `docker-compose.metabase.yml` | 商業智慧 (BI) / 數據探索 |
| **n8n** | `docker-compose.n8n.yml` | 工作流自動化 / 連接器 |
| **Redash** | `docker-compose.redash.yml` | 數據儀表板 / 查詢工具 |

---

## 🛠️ 快速啟動指南

要啟動任何一個服務，請確保您已安裝 Docker 和 Docker Compose (v2.x 或更高版本)。

使用 `-f` 參數指定您要啟動的配置檔案：

```bash
# 範例：啟動 Odoo 服務
docker compose -f docker-compose.odoo.yml up -d 

# 範例：啟動 Grafana 服務
docker compose -f docker-compose.grafana.yml up -d
