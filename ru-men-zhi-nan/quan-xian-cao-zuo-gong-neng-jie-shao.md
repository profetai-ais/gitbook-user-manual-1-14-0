---
description: 本頁將介紹Root權限與Object權限的操作方式。
---

# 權限操作功能介紹

## **Root 權限**

### **開啟位置**

Root 的權限設置會位於模組的右上角更多按鈕，點擊後即可開啟權限管理視窗。

<figure><img src="../.gitbook/assets/image (352).png" alt=""><figcaption></figcaption></figure>

### 頁面導覽

<figure><img src="../.gitbook/assets/image (349).png" alt=""><figcaption></figcaption></figure>

| 項目 | 操作名稱    | 說明                             |
| -- | ------- | ------------------------------ |
| 1  | 選擇使用者   | 搜尋名稱或帳號加入使用者                   |
| 2  | 選擇權限    | 選擇欲配置的清單權限                     |
| 3  | 已加入的使用者 | 檢視已加入的使用者資訊以及其權限設定，可調整權限或移除使用者 |

### **新增成員**

<figure><img src="../.gitbook/assets/image (351).png" alt=""><figcaption></figcaption></figure>

1. 輸入關鍵字搜尋欲加入的使用者
2. 設定加入權限
3. 點擊添加完成設定，權限設定會在對方刷新頁面後生效

### **調整成員權限**

<figure><img src="../.gitbook/assets/image (362).png" alt=""><figcaption></figcaption></figure>

1. 找到欲調整權限的目標使用者
2. 點擊右側下拉選單，調整權限

### **移除成員**

<figure><img src="../.gitbook/assets/image (363).png" alt=""><figcaption></figcaption></figure>

1. 找到欲移除的目標使用者
2. 點擊右側下拉選單，選擇移除

## Object 權限

不同功能中的 Object 權限可能採用不同的權限模式。常見模式包含角色型權限與存取權限兩種。

### **開啟位置**

權限設定位於模組的物件內， 點擊目標物件後，選擇內頁的權限分頁，即可檢視權限管理頁面，這裡已 Agent 模組為範例。

<figure><img src="../.gitbook/assets/image (353).png" alt=""><figcaption></figcaption></figure>

### 角色權限

角色權限會依照不同角色區分使用者可執行的操作。每個物件可設定 2 至 3 種權限角色，建立者可以透過「權限」授予其他使用者存取權限。具備較高權限的使用者通常可以管理物件設定、調整內容或維護授權對象；具備較低權限的使用者則可能只能查看或使用該物件。

常見情境包含：

* 可管理該物件
* 可編輯該物件
* 可檢視或使用該物件

> 請注意 : 實際角色名稱與可操作範圍會依功能設計而不同（角色定義請參考[模組權限介紹](quan-xian-gong-neng-jie-shao.md) )。

### 頁面導覽

<figure><img src="../.gitbook/assets/image (355).png" alt=""><figcaption></figcaption></figure>

| 項目 | 操作名稱 | 說明                            |
| -- | ---- | ----------------------------- |
| 1  | 編輯表格 | 允許使用者編輯表格的呈現方式                |
| 2  | 刷新   | 點擊後刷新列表                       |
| 3  | 內容篩選 | 進階篩選指定內容                      |
| 4  | 批次刪除 | 勾選項目後左上角的刪除按鈕便會顯示，可讓使用者刪除多個項目 |
| 5  | 搜尋欄位 | 搜尋 名稱                         |
| 6  | 邀請   | 邀請組織 / 成員                     |
| 7  | 動作   | 轉移您的角色或刪除選定的使用者               |

#### **新增成員**

<figure><img src="../.gitbook/assets/image (356).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (357).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (358).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (359).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (360).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (361).png" alt=""><figcaption></figcaption></figure>

1. 點擊「添加」開&#x555F;_&#x65B0;增成&#x54E1;_&#x5C0D;話方塊
2. 輸入框能搜尋組織或使用者
3. 選擇對應的權限
4. 這裡有兩種方式可以選擇組織/使用者
   * 點擊使用組織搜尋
   * 輸入關鍵字跳出對應的組織/使用者，可點選右邊的層級按鈕確認角色的層級
5. 選擇目標組織/使用者後，可點擊標籤打開檢視選單，檢視組織層級及角色內的所有使用者
6. 點擊「添加」按鈕，完成邀請

#### **調整成員權限**

<figure><img src="../.gitbook/assets/image (364).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (365).png" alt=""><figcaption></figcaption></figure>

1. 找到欲調整權限的目標組織/使用者，對其點擊編輯按鈕
2. 調整權限
3. 點擊儲存，完成設定

#### **轉移擁有者**

<figure><img src="../.gitbook/assets/image (366).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (367).png" alt=""><figcaption></figcaption></figure>

1. 找到欲轉移擁有權的目標使用者，對其點擊轉移權限按鈕
2. 確認轉移的使用者資訊
3. 點擊轉移，完成設定

> 注意 :&#x20;
>
> 1. 轉移擁有者功能僅能對使用者使用，您無法轉移擁有者給組織。
> 2. 轉移擁有者後，object 的擁有者與創建者將自動變更為新使用者，您的 object 權限仍會維持轉移前的設定。

#### **移除成員**

<figure><img src="../.gitbook/assets/image (368).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (369).png" alt=""><figcaption></figcaption></figure>

1. 找到欲移除的目標組織/使用者，對其點擊移除按鈕
2. 再次確認是否移除該對象，點擊移除按鈕

### 存取權限

存取權限可授予組織或個人使用者；若授予組織，則組織內所有使用者皆擁有該資料使用權限。這裡已知識庫的數據集作為範例。

{% hint style="info" %}
擁有存取權限設定的 object 在 AI Studio 內目前有**知識庫的數據集**，以及 **MCP 的 MCP 工具。**
{% endhint %}

#### **新增成員**

<figure><img src="../.gitbook/assets/image (371).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (373).png" alt=""><figcaption></figcaption></figure>

1. 點擊「知識設定選單」中的 _資料集存取權限_ 項目
2. 點擊 按鈕為數據集批次添加權限
3. 在「資料集」區域中選擇要設定權限的檔案
4. 在右側區域點擊「組織」標籤頁，勾選要授予權限的組織層級
5. 在右側區域點擊「使用者」標籤頁選擇要授予權限的使用者
6. 在「使用者選單」中搜尋要新增的使用者
7. 完成組織與使用者的變更後點擊「ok」按鈕保留設定

#### **移除成員**

<figure><img src="../.gitbook/assets/image (375).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (374).png" alt=""><figcaption></figcaption></figure>

1. 對要移除的數據集點擊編輯按鈕
2. 選擇要移除的組織或使用者，對其點擊移除按鈕
3. 點擊儲存，完成設定
