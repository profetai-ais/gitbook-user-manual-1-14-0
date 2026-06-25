---
description: 使用者在 AI Studio 中可見的功能與操作取決於帳號所屬的角色。
---

# AI Studio 角色與權限說明

## **AI Studio 中的功能角色類型**

系統預設三種功能角色類型：

* **AI Studio 管理員：** 可瀏覽平台內的全部的功能選單，並能賦予其他使用者知識庫與助手功能的進階操作權限。
* **AI Studio 協作者：** 可瀏覽平台內的知識庫、能力、分析、模板與 Agent 功能選單，建立適用於不同領域與場景的文件知識庫及 Agent。
* **AI Studio 使用者：** 為企業內的一般使用者，可瀏覽平台內的知識庫、模板與 Agent 功能選單。

### **角色比較**

<table data-full-width="false"><thead><tr><th>功能模組第一層</th><th>功能模組第二層</th><th>AI Studio 管理員</th><th>AI Studio 協作者</th><th>AI Studio 使用者</th></tr></thead><tbody><tr><td><strong>工作空間</strong></td><td></td><td>O</td><td>O</td><td>O</td></tr><tr><td><strong>Agent</strong></td><td></td><td>O</td><td>O</td><td>O</td></tr><tr><td><strong>知識庫</strong></td><td></td><td>O</td><td>O</td><td>O</td></tr><tr><td><strong>能力</strong></td><td>技能</td><td>O</td><td>O</td><td>X</td></tr><tr><td></td><td>MCP</td><td>O</td><td>O</td><td>X</td></tr><tr><td><strong>模板</strong></td><td>工作流程</td><td>O</td><td>O</td><td>O</td></tr><tr><td></td><td>提示詞</td><td>O</td><td>O</td><td>O</td></tr><tr><td><strong>分析</strong></td><td>報告</td><td>O</td><td>O (僅自己)</td><td>O (僅自己)</td></tr><tr><td></td><td>工作管理</td><td>O</td><td>X</td><td>X</td></tr><tr><td></td><td>稽核日誌</td><td>O</td><td>X</td><td>X</td></tr><tr><td><strong>系統設定</strong></td><td>模型</td><td>O</td><td>X</td><td>X</td></tr><tr><td></td><td>配額</td><td>O</td><td>X</td><td>X</td></tr><tr><td></td><td>配置</td><td>O</td><td>X</td><td>X</td></tr><tr><td></td><td>密鑰管理</td><td>O</td><td>X</td><td>X</td></tr><tr><td></td><td>標籤管理</td><td>O</td><td>X</td><td>X</td></tr></tbody></table>

> 注意： 分析內的報告為所有角色都可進入，但只有 AI Studio 管理員可檢視所有帳號的使用紀錄。

## 權限同步

登入後，系統會自動將清單權限補上 AIS 帳號當下的權限，例如: 帳號為 AIS 協作者，登入後自動補上 Agent、知識庫、能力(技能、MCP)、 模板(工作流程、提示詞) 的清單協作者權限。

此功能只會在登入時觸發同步當前沒有權限的部分，不會影響現有的清單權限，如果該帳號在 AIS 的權限有異動，不會觸發自動同步權限功能。
