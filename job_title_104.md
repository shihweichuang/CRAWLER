# 104 職缺清單

<br>

## 使用需求

爬取指定關鍵字的職缺清單及相關資訊。

<br>

## 爬取頁面

### 1. <a href="https://www.104.com.tw/jobs/search/?jobsource=index_s&keyword=APP%E9%96%8B%E7%99%BC%E5%B7%A5%E7%A8%8B%E5%B8%AB&mode=s&page=1">104人力銀行-職缺搜尋</a>

抓取資訊：所有職缺的URL。

<img src="https://i.imgur.com/O4gb7hQ.png" alt="104人力銀行-職缺搜尋" width="80%">

### 2. <a href="https://www.104.com.tw/job/8ewdf?jobsource=hotjob_chr_exp">104人力銀行-職缺頁面</a>

抓取資訊：職缺名稱、公司名稱、需求人數、到職日期、更新日期、工作內容、工作待遇、職務類別、工作性質、工作時間、工作地點、學歷要求、科系要求、工作經驗、語文條件、擅長工具、工作技能、其他條件。

<img src="https://i.imgur.com/GAZZrPb.png" alt="104人力銀行-職缺頁面" width="80%">

<br>

## 資料庫儲存

資料來源 (source)、關鍵字 (keyword)、貼文ID (post_id)、職缺名稱 (title)、公司名稱 (company)、需求人數 (require_amount)、到職日期 (on_board_date)、更新日期 (update_date)

<img src="https://i.imgur.com/GVm3V0A.png" alt="表格-1/5" width="80%">

職缺描述 (description)、工作待遇 (salary)

<img src="https://i.imgur.com/zWmgbA8.png" alt="表格-2/5" width="80%">

職務類別 (title_category)、工作性質 (employment_status)、工作時間 (work_time)、工作地點 (place)

<img src="https://i.imgur.com/oSzFuR7.png" alt="表格-3/5" width="80%">

學歷要求 (edu)、科系要求 (dept)、工作經驗 (experience)、外語能力 (language)、電腦專長 (tools)、工作技能 (ability)

<img src="https://i.imgur.com/3d78Ur7.png" alt="表格-4/5" width="80%">

附加條件 (additional)、爬取日期 (created_at)

<img src="https://i.imgur.com/GiHXgok.png" alt="表格-5/5" width="80%">

<br>

## 範例

### 範例1

<img src="https://i.imgur.com/o2qwXzW.jpeg" alt="範例1" width="70%">
<img src="https://i.imgur.com/saRnYhn.jpeg" alt="範例1" width="50%">
<img src="https://i.imgur.com/wMcddsM.jpeg" alt="範例1" width="60%">

<img src="https://i.imgur.com/nGpeY93.jpeg" alt="範例1" width="70%">
<img src="https://i.imgur.com/anIZwOq.jpeg" alt="範例1" width="65%">

<img src="https://i.imgur.com/VuAyUu6.jpeg" alt="範例1" width="70%">
<img src="https://i.imgur.com/wqUYA6y.jpeg" alt="範例1" width="38%">

<img src="https://i.imgur.com/jtf7LFA.jpeg" alt="範例2" width="70%">
<img src="https://i.imgur.com/6cQvZIm.jpeg" alt="範例2" width="70%">

### 範例2

<img src="https://i.imgur.com/KurPFBm.png" alt="範例2" width="70%">
<img src="https://i.imgur.com/xJ5hX4M.png" alt="範例2" width="70%">
<img src="https://i.imgur.com/5OeBTRL.png" alt="範例2" width="60%">

<img src="https://i.imgur.com/CwKYKBM.png" alt="範例2" width="70%">
<img src="https://i.imgur.com/DDh2kXk.png" alt="範例2" width="65%">

<img src="https://i.imgur.com/MGJajOI.png" alt="範例2" width="70%">
<img src="https://i.imgur.com/FShNpY1.png" alt="範例2" width="35%">

<img src="https://i.imgur.com/njabOFv.png" alt="範例2" width="70%">
<img src="https://i.imgur.com/qXh6LeN.png" alt="範例2" width="75%">
