---
description: 分析 是用來檢視報表與資料分析結果的頁面。 使用者可在此頁面查看圖表、報表與相關分析內容，快速掌握資料狀況，提升查閱與判讀效率。
---

# 報告

## 簡介

報告提供 AI Studio 的使用狀況與營運分析報表，協助管理者追蹤平台中的 Token、Quota、任務執行與功能使用情形。使用者可以透過視覺化儀表板查看 Session、Memory、Workflow、RAG、Speech 等相關數據，作為成本分析、用量追蹤與營運管理的參考。

此頁面整合報表與資料視覺化工具，使用者可依權限查看已建立的 Dashboard、Chart 與 Dataset。

<figure><img src="../.gitbook/assets/image (410).png" alt=""><figcaption></figcaption></figure>

## Dashboard

**Dashboard** 用於集中呈現已建立的分析儀表板。每個 Dashboard 會包含一個或多個圖表，用於觀察特定主題的數據狀況。

常見 Dashboard 可包含以下分析主題：

* Agent 使用狀況
* Token 使用量與成本
* 使用者活動分析
* Knowledge Base 與 Agent 關聯
* 權限與存取狀況
* 任務執行與異常監控

在 Dashboard 清單中，使用者可以查看名稱、狀態、擁有者與最後修改時間。點選 Dashboard 名稱後，可進入該 Dashboard 查看詳細圖表內容。

## Chart

**Chart** 用於管理或建立報表圖表。建立圖表時，使用者需先選擇資料集，再選擇圖表類型。

系統支援多種圖表類型，例如：

* Area Chart
* Bar Chart
* Big Number
* Line Chart
* Pie Chart
* Table
* Heatmap
* Pivot Table
* Scatter Plot
* Treemap

不同圖表類型適合呈現不同資料。例如，趨勢資料可使用 Line Chart，比例資料可使用 Pie Chart，明細資料可使用 Table，關鍵數字則可使用 Big Number。

建立 Chart 的功能通常提供給具有報表管理權限的使用者。一般使用者可依權限查看既有圖表與 Dashboard。

## Dataset

**Dataset** 顯示可用於建立圖表與 Dashboard 的資料集。Dataset 是報表分析的資料來源，圖表會依據所選 Dataset 中的欄位與資料內容產生。

在 Dataset 清單中，使用者可以查看資料集名稱、類型、資料庫、Schema、擁有者與最後修改時間。

## 注意事項

Report 中可查看的 Dashboard、Chart 與 Dataset 會依使用者權限而有所不同。若無法看到特定報表或資料集，請確認是否具備對應的檢視或管理權限。

此頁面主要用於資料檢視與分析。若需要調整 Dashboard、Chart 或 Dataset，請確認是否具備報表管理權限，並依實際需求進行設定。
