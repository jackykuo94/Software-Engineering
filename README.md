# 使用 ChatGPT 製作使用者註冊頁面的心得與步驟 
## 11224227郭秉恆 11224211李崇勛

在這次的練習中，我們利用 ChatGPT 來協助建立一個簡單的使用者註冊系統，整體過程讓我深刻體會到人工智慧在程式開發上的輔助能力。過去若要從零開始撰寫 HTML、PHP、以及資料庫連線的程式碼，需要查閱大量教學與文件，但透過 ChatGPT，我只需要清楚描述需求，它便能自動生成完整的網站結構、範例程式碼，甚至連 Docker 環境的設定檔都能一步到位，大幅節省開發時間。

## 使用步驟如下： 

提出需求：我先在 ChatGPT 中打入文章中的要求並請它幫我建立一個使用者註冊頁面，AI 立即生成 HTML 與 PHP 範例，接著我請 GPT 幫我整理成 ZIP 檔並成功進入註冊網頁。
<img width="1167" height="550" alt="螢幕擷取畫面 2025-11-02 002643" src="https://github.com/user-attachments/assets/3b090c7d-b2b7-4606-9a76-294dfb81e72a" />
幫我整理成的ZIP檔案，包含註冊網站。
![messageImage_1762015369041](https://github.com/user-attachments/assets/29406443-f668-4908-b010-95fe39f3780a)

使用者註冊頁面內容。
<img width="1913" height="1079" alt="螢幕擷取畫面 2025-11-01 233449" src="https://github.com/user-attachments/assets/6fc45964-2972-436d-be16-2c990028fcf1" />



輸入使用者名稱、電子郵件帳號及密碼後成功註冊。
<img width="1920" height="1080" alt="螢幕擷取畫面 (15)" src="https://github.com/user-attachments/assets/1d992c97-73d1-491b-ae84-fb696b11013b" />


擴充功能：接著我要求它增加資料庫連線與表單提交功能，並提供 MySQL 資料表的建立語法。

建立執行環境：ChatGPT 進一步協助生成 docker-compose.yml，讓我可以用 Docker 快速啟動 PHP + MySQL 環境。
<img width="1919" height="1079" alt="螢幕擷取畫面 2025-11-01 230521" src="https://github.com/user-attachments/assets/41d99d9c-d21d-413a-9ce0-a9e207290873" />

實際運行：我將檔案下載後，執行 docker-compose up -d，在瀏覽器中成功開啟註冊頁面並完成資料儲存。
<img width="1919" height="1079" alt="螢幕擷取畫面 2025-11-01 232349" src="https://github.com/user-attachments/assets/24d04a3d-3b90-4f4d-8506-d72cdee3a37d" />

## 遇到問題:

途中遇到的問題也請 GPT 協助解決，提供它錯誤代碼、回報遇到的問題等等，它就會一步步幫我解決。
![messageImage_1762015206031](https://github.com/user-attachments/assets/522a6a34-96f0-429a-b14a-6db1c67a1afc)
![messageImage_1762015313550](https://github.com/user-attachments/assets/815776a6-cf89-484f-8366-a8927a080991)

但有時候請GPT幫忙生成ZIP檔，它會給我一張ZIP圖片。
![messageImage_1762015114360](https://github.com/user-attachments/assets/9035c597-9cf9-40bd-8168-85bb7a806770)


## 心得反思:
透過這次實作，我學到與 AI 合作的關鍵在於給出明確、具體的指令。ChatGPT 不僅能產出可用的程式碼，更能協助我理解每個步驟的邏輯，也能幫我解決遇到的問題並提供解決步驟。我發現用 ChatGPT 來建立用戶註冊介面，其實是件非常輕鬆又有效率的事。若自己做註冊頁面時，可能會卡在一些小地方，但這次我只要把需求講清楚，ChatGPT 就能一步一步告訴我如何解決。
而只要我描述一下想要的風格，ChatGPT 就能幫我做出一段直接能用的 HTML、CSS，甚至還會幫我微調版面，讓整體看起來更一致。它能生成一段清楚實用的程式碼，並說明每一步的作用。過程就像有個很懂程式又很有耐心的學霸鄭秉居同學在旁邊教我。
最方便的是，只要我臨時改需求，，ChatGPT 都能立刻重寫或調整，不需要我自己慢慢摸索。這讓整個開發過程變得更順、更快，也讓我對於前後端的流程有更清楚的理解。
未來我會繼續用 ChatGPT 來輔助開發，因為它真的能讓我省下很多時間，也讓寫程式變得更簡單。
