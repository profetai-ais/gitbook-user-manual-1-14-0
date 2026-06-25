---
description: 「配置」模組主要用於管理系統的預設行為設定，包含 GPT 預設配置與 default system prompt 等相關項目。
---

# 配置

## 翻譯

控制多國語系翻譯與其他相關翻譯的設定。

<figure><img src="../.gitbook/assets/image (412).png" alt=""><figcaption></figcaption></figure>

## **相關問題**

相關問題功能使用 LLM 已回覆內容生成相關問題，讓使用者點擊就可執行問答。管理人員可以變更相關問題的生成設定。

<figure><img src="../.gitbook/assets/image (274).png" alt=""><figcaption></figcaption></figure>

## 生成標題

用於根據使用者輸入內容自動產生標題。系統會先辨識輸入語言，再生成簡短且具主題性的標題。

<figure><img src="../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>

## **記憶設定**

### **記憶語言模型**

用於設定位於畫面右上角頭像中的 Personalization 相關內容所使用的語言模型，可依實際使用情境選擇適合的語言，例如英文或中文。

<figure><img src="../.gitbook/assets/image (416).png" alt=""><figcaption></figcaption></figure>

### **記憶向量模型**

用於設定位於畫面右上角頭像中的 Personalization ，將 Memory 內容向量化並寫入資料庫時所使用的 embedding 模型。

<figure><img src="../.gitbook/assets/image (415).png" alt=""><figcaption></figcaption></figure>

### 使用者記憶工具

用於設定 AI 如何判斷、儲存、更新或刪除使用者記憶，協助系統在符合安全規則的前提下保留可長期使用的偏好與資訊。

<figure><img src="../.gitbook/assets/image (417).png" alt=""><figcaption></figcaption></figure>

### Agent 記憶擷取

用於設定 AI 如何從對話中擷取可重複使用的任務執行經驗，協助 Agent 保留已驗證的流程、規則與操作方式。

<figure><img src="../.gitbook/assets/image (418).png" alt=""><figcaption></figcaption></figure>

## 語音設定

用於工作空間使用語音轉文字的功能時所需要轉譯的規則與限制條件。

<figure><img src="../.gitbook/assets/image (419).png" alt=""><figcaption></figcaption></figure>

## **技能掃描設定**

用於控制上傳技能時是否啟用掃描機制。啟用後，系統會於技能上傳時進行掃描；停用後，則不會於上傳時執行掃描。

<figure><img src="../.gitbook/assets/image (420).png" alt=""><figcaption></figcaption></figure>

## 指令改寫設定

指令改寫設定可將使用者輸入的原始指令，自動整理成更清楚、具結構且可執行的提示詞。系統會在保留原意的前提下，移除模糊與重複內容，補足必要的格式、語氣、長度或語言限制，並將多步驟需求整理為明確的行動指令，讓後續模型能更準確地理解並執行任務。

<figure><img src="../.gitbook/assets/image (421).png" alt=""><figcaption></figcaption></figure>

## Canvas 設定

**Canvas 設定**可判斷使用者需求是否需要啟用畫布相關功能，並依照請求內容自動分派至合適的處理流程。當需求涉及圖表、流程圖、關係圖、互動式 UI 或網頁應用說明時，系統會優先交由畫布設計功能處理；若包含 HTML 生成需求，也會透過指定流程轉交程式編輯功能執行。若需求不屬於視覺化或網頁應用範圍，則維持一般回應流程，避免不必要地啟用畫布功能。

<figure><img src="../.gitbook/assets/image (422).png" alt=""><figcaption></figcaption></figure>

## 日誌分析

日誌分析用於設定 AI 分析日誌時的判斷方式與輸出格式，協助系統根據錯誤、趨勢、可用性與效能等資訊評估整體健康狀態。

<figure><img src="../.gitbook/assets/image (423).png" alt=""><figcaption></figcaption></figure>

## AI Cron 設定

用於設定 AI 如何將自然語言的排程描述轉換為 Spring CronExpression，協助使用者快速產生可用的排程規則。

<figure><img src="../.gitbook/assets/image (424).png" alt=""><figcaption></figcaption></figure>

## 預設模型

用於設定模型清單內模型的排序，排序會依照使用者能調用的權限依序顯示。

<figure><img src="../.gitbook/assets/image (425).png" alt=""><figcaption></figcaption></figure>
