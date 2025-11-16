# 114-1 師大科技系程式語言
授課教師：蔡芸琤老師

姓名：蔡欣育
系級：117科技系二年級

課程筆記區、作業連結區、專題連結區
Markdown 語法說明：https://markdown.tw/

-[HW1日常支出速算與分攤](https://github.com/41371112h/114-1/blob/main/HW1_%E6%97%A5%E5%B8%B8%E6%94%AF%E5%87%BA%E9%80%9F%E7%AE%97%E8%88%87%E5%88%86%E6%94%A4.ipynb)  
-[HW2成績一本通](https://github.com/41371112h/114-1/blob/e662ce25b740a55bc9d371f6ced808faa61ccb94/HW2%E6%88%90%E7%B8%BE%E4%B8%80%E6%9C%AC%E9%80%9A.ipynb)  
-[HW3待辦清單與番茄鐘紀錄](https://github.com/41371112h/114-1/blob/fac9959d1361165264ca14bb96322f23975b9349/HW3_%E5%BE%85%E8%BE%A6%E6%B8%85%E5%96%AE%E8%88%87%E7%95%AA%E8%8C%84%E9%90%98%E7%B4%80%E9%8C%84.ipynb)  
[csv檔](https://github.com/41371112h/114-1/blob/638f79450b0414578476172464a5dc916045767e/tasks_20251026_173648.csv)
[json檔](https://github.com/41371112h/114-1/blob/638f79450b0414578476172464a5dc916045767e/tasks_20251026_173648.json)  
-[HW4文字資料小分析](https://github.com/41371112h/114-1/blob/ac20966deedd300c0c53f286af732e0cb806403b/HW4%E6%96%87%E5%AD%97%E8%B3%87%E6%96%99%E5%B0%8F%E5%88%86%E6%9E%90.ipynb)  
-[HW5中山商圈美食・景點指南地圖](https://github.com/41371112h/114-1/blob/18d25476de7f62a8a33b8ffde6b91547c3c551bd/HW5%E4%B8%AD%E5%B1%B1%E5%95%86%E5%9C%88%E7%BE%8E%E9%A3%9F%E3%83%BB%E6%99%AF%E9%BB%9E%E6%8C%87%E5%8D%97%E5%9C%B0%E5%9C%96.ipynb) 

作業6
--
[試算表課程整學期紀錄程式](試算表回傳.ipynb)  
-[HW6學習小秘書](HW6學習小秘書.ipynb)  
1️⃣ 資料擷取（Data Fetching）——從 Google Sheet 自動讀取整學期課表

透過 gspread 連接 Google 試算表

自動讀取你建立好的「整學期紀錄」分頁

作為所有 AI 判斷與摘要的資料來源  
2️⃣ AI 行前提醒生成 ——Gemini 自動撰寫每堂課前的小提醒

使用 Gemini（gemini-2.5-flash）模型

針對課程名稱、時間、教室自動產生 1–2 句行前提醒

語氣：友善、有重點、40 字以內  
3️⃣ 資料同步 / 自動化紀錄 ——自動建立週摘要分頁

使用者在 Gradio 介面選取某天

系統自動找出該週所有課程

產生「本週的 AI 行前提醒週報」

若勾選「回寫」，會自動：

在 Google Sheet 建立新分頁（例：週摘要_2025-09-01）

將該週課程＋AI 提醒寫入表格
<img width="839" height="175" alt="image" src="https://github.com/user-attachments/assets/4cd5e17f-2d73-42a7-85ab-679867dc9ecf" />


