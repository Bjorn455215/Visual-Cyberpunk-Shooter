# CyberStrike AI Motion Experience

本實作專案基於電腦視覺 (AI) 的沉浸式體感射擊遊戲展示專案，透過電腦內建攝影機捕捉玩家動作，實現無需鍵盤滑鼠的直覺戰鬥體驗。

>  **說明**：本 Repo 僅提供示範影片與技術說明。核心原始碼不對外公開。

---

##  專案演示 (Demo Video)


https://github.com/user-attachments/assets/ab57bbb4-df6a-4f8b-83df-0442ac57966f


---

## 技術來源與專案背景

本專案之核心互動技術與 AI 串接框架，由本人過去開發的多個開源專案技術遷移並優化而來。若您對底層邏輯感興趣，可參考以下相關開源模組：

* **[Eye-Tracking](https://github.com/Bjorn455215/Python-Eye-Tracking)**: 負責眼睛追蹤邏輯部分之程式碼可參考此repo。
* **[Hand-Gesture](https://github.com/Bjorn455215/Gobang-project-5-5-for-testing-)**: 包含本專案所使用的手勢動作可參考此五子棋專案中的程式碼。

---

此外，本專案是基於**賽博朋克**的世界觀(Cyberpunk) 進行製作，**遊戲背景圖及敵人圖片皆利用Gemini生成圖片功能製作而成**，無版權問題

* **背景圖(4800 x 896)**
  <img width="9072" height="1792" alt="cyberpunk" src="https://github.com/user-attachments/assets/b43a39c0-8f75-41c0-a1cc-ab5124c4375e" />

* **敵人(337 x 770)**

  
  <img width="337" height="770" alt="maelstorm2" src="https://github.com/user-attachments/assets/c3cf3402-9dbc-4c0a-b427-292ce9d91e14" />

---

### 執行需求
* Windows 10/11 操作系統
* 標準 USB 攝像頭 (Webcam)
  
---

## 操作說明

| 互動類別 | 動作指令 (Action) | 遊戲功能 (Function) |
| :--- | :--- | :--- |
| **視覺控制** | 頭部向左/右偏移 | 捲動場景視角 |
| **戰鬥指令** | 右手拇指、食指捏合 | 開火射擊 (Fire) |
| **後勤補給** | 左手五指張開 | 重新裝彈 (Reload) |
| **系統指令** | 按下鍵盤 **`R`** 鍵 | 遊戲重置 (Reset) |

---

## 聲明

本專案葉面為個人作品成果展示，不提供原始碼。若有技術疑問或授權需求，歡迎透過email聯繫 bjorn455215@gmail.com
