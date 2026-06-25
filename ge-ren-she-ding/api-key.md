# API Key

## 簡介

API Key 可讓使用者建立專屬的 API 金鑰，供外部系統呼叫 AI Studio 支援的開放 API。透過 API Key，外部程式、整合服務或第三方工具不需要使用帳號密碼登入，即可依照金鑰所綁定的使用者身分進行 API 呼叫。使用者可以在此建立新的 API Key，並開啟 API 文件查看可使用的 API 規格。

每一把 API Key 都會綁定到建立該金鑰的使用者，系統會依據該使用者的權限判斷可存取的 API 範圍。

<figure><img src="../.gitbook/assets/image (321).png" alt=""><figcaption></figcaption></figure>

## API Key 設定

開啟 API Key 視窗後，點擊生成按鈕即可生成一組金鑰。

<figure><img src="../.gitbook/assets/image (336).png" alt=""><figcaption></figcaption></figure>

> 注意 : API Key 建立後，完整金鑰內容只會顯示一次。基於安全性考量，系統不會再次顯示完整金鑰，也無法協助查回原始金鑰。若金鑰遺失，請刪除原金鑰後重新建立。\
> 每位使用者最多可建立 1 把 API Key，如需產生新的 API Key，請先刪除原先的 API Key 後再重新生成。

### 管理 API Key

建立 API Key 後，使用者可以查看自己建立的所有金鑰。為保護金鑰安全，清單中只會顯示遮罩後的金鑰格式，例如：

```
gak_abc*******xyz
```

停用或刪除 API Key 後，外部系統將無法再使用該金鑰進行 API 呼叫。若金鑰已設定到期日，系統會在到期後自動使該金鑰失效。

> 注意 : 請勿將 API Key 暴露於公開環境，例如前端程式碼、公開 Git 儲存庫或未受保護的文件中。若懷疑 API Key 已外洩，請立即停用或刪除該金鑰，並重新建立新的 API Key。

## API 文件

在 API 文件區塊中，使用者可點選 開啟 API 文件。API 文件會顯示可使用的 API 規格，並可透過 Swagger UI 查看 API 路徑、參數與測試請求。

## 使用紀錄

切換至使用紀錄分頁後，使用者可以查看 API Key 的使用紀錄。使用紀錄可協助使用者追蹤外部系統的呼叫狀況，並確認是否有異常請求。使用者也可以依日期區間查詢指定期間內的 API 呼叫紀錄。
