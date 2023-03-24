---
layout: post
title: Quadcopter Drone
author: [Richard Kuo]
category: [Lecture]
tags: [jekyll, ai]
---

創新應用之四軸無人機

---
## Content
* **專題題目** (Project Name & Objectives)
* **應用與功能說明** (Key Features)
* **設計考量與所需相關技術** (Design considerations)
* **系統方塊圖** (System Block Diagrams)
* **概念驗證** (Proof of Concept)
* **成果展示** (Demostation)

---
## 太陽能板巡檢無人機
類別: 四軸無人機 <br>

目的: To-Be-Discussed <br>

---
### 應用功能說明
1. AI視覺辨識
2. 自動導航

---
### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式: 四軸飛行
2. 供電方式: 鋰電池

**所需相關技術：**<br>
1. AI視覺辨識微控制器模組 (AMB82-mini)

---
### 系統方塊圖
TBD

---
### 概念驗證
1. AI視覺辨識: [AMB82-mini](https://www.ruten.com.tw/item/show?22308071996883)

---
### 開發進度與展示
**AI視覺辨識**<br>
驗證[AMB82-mini](https://www.ruten.com.tw/item/show?22308071996883)<br>

* **F450 組裝指南**<br>
<iframe width="498" height="280" src="https://www.youtube.com/embed/cg1-L9EYe1U" title="F450 安裝指南" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


---
## 參考資料:

### 無人機投放砲彈
[台製無人機現蹤烏克蘭！投「6枚迫擊砲」毀俄軍　傳波蘭採購800架](https://www.ettoday.net/news/20220824/2323312.htm)<br>
![](https://cdn2.ettoday.net/images/6529/d6529313.jpg)
波蘭科技媒體《WP tech》則於18日報導稱，橙森國際所出產的800架「Revolver 860」已先出售給波蘭，再由波蘭政府轉手捐給烏克蘭軍隊

---
### 無人機群飛展演
[無人機群飛展演「重質不求量」　臺灣希望創新強化內容設計](https://www.digitimes.com.tw/iot/article.asp?cat=158&ct=o&id=0000645108_AN22VZY6LMRV1G96ZWGO7)
臺灣希望創新公司(Taiwan Drone 100)屢以群飛展演驚艷四座，執行長李志清指出，群飛技術著重精確定位及通訊技術，即時定位誤差可控制在10~15公分之內。2021年團隊在國際群飛競賽「1000架以下」組別奪得首獎。

![](https://img.digitimes.com/newsimg/2022/0920/645108-1-zwgo7.jpg)
臺灣希望創新公司執行長李志清(左)及技術長蔡博智

為提升定位精準度，團隊運用的是Real-time Kinematic (RTK)定位系統，每台無人機皆須裝設RTK接收器，地面則設有天線基地台。RTK接收器的成本曾經相當昂貴，一台要價新台幣40萬，不過近期基本款已降到4,000~5,000元左右。<br>
以展演用到的通訊技術而言，基地台得持續上傳修正訊號到每台無人機，才能持續將定位誤差維持在10~15公分左右，資料傳輸則用到4G LTE、5G、或工業級的Wi-Fi系統。同時，無人機也會回傳資料給操控電腦，地面的操控人員須隨時監控飛機的定位、路徑、電量等狀況，若有異常則須讓機台返航或降落。此外，團隊也開發出雲端監控平台，以利即時和遠端監控。<br>
<table>
<tr>
<td><img src="https://img.digitimes.com/newsimg/2022/0920/645108-2-zwgo7.jpg"></td>
<td><img src="https://img.digitimes.com/newsimg/2022/0920/645108-3-zwgo7.jpg"></td>
</tr>
</table>

---
### 無人機植樹
[日植4萬棵樹！AirSeed改良無人機種樹系統](https://www.digitimes.com.tw/iot/article.asp?cat=158&cat1=20&cat3=41&id=0000643512_6346LNFW0ZGASC3MD221U)<br>
![](https://img.digitimes.com/newsimg/2022/0913/643512-1-d221u.jpg)

---
### 無人機收水果
[Tevel Aerobotics](https://www.tevel-tech.com/)<br>
<iframe width="1031" height="580" src="https://www.youtube.com/embed/xzOf4-WaXzE" title="First Commercial Pilot of Tevel Aerobotics & Rivoira Group" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
### 無人機物流
[中華郵政於尖石鄉試辦遙控無人機物流服務](https://www.digitimes.com.tw/iot/article.asp?cat=158&cat1=20&cat2=&id=643497)<br>
中華郵政首度使用25公斤以上的無人機於新竹縣尖石鄉進行物流投遞試飛<br>
![](https://img.digitimes.com/newsimg/2022/0830/643497-1-6qh5r.jpg)

---
### 無人機外送
[可省70%外送人力成本　高軟無人送餐10月「上門」](https://www.digitimes.com.tw/iot/article.asp?cat=158&cat1=20&cat2=&id=643409)<br>
統一集團攜手中光電智能機器人，展開全新的無人機外送模式<br>
![](https://img.digitimes.com/newsimg/2022/0829/643409-1-8vil4.jpg)
7-Eleven串聯Foodomo外送平台，積極投入兩大無人外送測試計畫。一是攜手工研院，參與AMR無人智慧物流技術送餐服務行列，推動在地首創自主移動機器人直送門口(door to door)的無人外送服務；二是整合集團旗下四大品牌資源，攜手中光電智能機器人，展開全新的無人機外送模式。<br>

工研院南分院執行長曹芳海與統一超商協理吳輝振26日在高雄「2022 Meet Greater South亞灣創新×新創大南方」簽署合作備忘錄，雙方瞄準無人送餐市場，運用AMR無人智慧物流技術，打造全台首創可室外、室內配送、自動呼叫並搭乘電梯的無人送餐物流服務。<br>

---
### 城市無人機物流
[日將開放大城市無人機物流　爭取制定國際標準](https://www.digitimes.com.tw/iot/article.asp?cat=158&cat1=20&cat2=&id=642820)<br>
![](https://img.digitimes.com/newsimg/2022/0825/642820-1-so8o0.jpg)
日本從2012年引進美國軍方的的無人機，就開始研究以無人機當基地台的無人機無線通訊網技術，並分配920MHz與169MHz無線電波頻段，供無人機航管控制及影像轉播等用途應用<br>
據日經報導，2022年6月起，在日本重量超過0.1公斤的無人機，都要申請類似車牌的ID編號，確定無人機使用者身分，防範惡意使用者。<br>

---
### 中光電智能機器人
[Teledyne FLIR攜手中光電智能機器人 無人機4Q22美國銷售](https://www.digitimes.com.tw/iot/article.asp?cat=158&cat1=20&cat3=16&id=0000645052_LFD1QPLQ4FM3RU3Z8O7SJ)<br>
SIRAS無人機具備IP54防塵防水等級設計、31分鐘飛行時間、前雷達防撞系統，可1分鐘內快速起飛，長距離圖傳雙頻無線電(2.4/5.8 GHz)遙控器，電池熱插拔，可確保任務不中斷，同時為提高數據安全性，操作者不需建立在線帳戶即可立即飛行，圖像可全部儲存在SD卡，提高使用便利性及避免潛在資料外洩等風險功能。<br>
![](https://img.digitimes.com/newsimg/2022/0915/645052-1-8o7sj.jpg)

---
### 無人機監控水質
[環保署推無人機監控水質 更省時、省錢、低污染 2020/10/21](https://news.ltn.com.tw/news/life/breakingnews/3328102)<br>
![](https://img.ltn.com.tw/Upload/news/600/2020/10/21/3328102_2_1.jpg)

---
### 農業無人機
[佐翼科技](https://www.droxotech.com/) [以航太領域的無人機技術為傳統農工業打穩轉型的第一哩路](https://www.gvm.com.tw/article/85865)<br>
農業用智能無人機<br>
![](https://www.droxotech.com/uploads/1/2/9/5/129575120/1090615-droxo-web-01_orig.jpg)
特殊空拍應用專案<br>
![](https://www.droxotech.com/uploads/1/2/9/5/129575120/0615-droxo-web-orig_orig.jpg)
<table>
<tr>
<td>農用植保機 DX10-N1</td>
<td>農用植保機 DX20-E1</td>
</tr>
<tr>
<td><img src="https://www.droxotech.com/uploads/1/2/9/5/129575120/1100527-droxo-web-01_orig.jpg"></td>
<td><img src="https://www.droxotech.com/uploads/1/2/9/5/129575120/1100527-droxo-web-02_orig.jpg"></td>
</tr>
</table>

---
### 風機檢測
[金屬中心無停轉風機之無人機(UAV)巡檢系統 勇奪科技界奧斯卡2020 R&D100大獎](https://www.mirdc.org.tw/NewsView0.aspx?Cond=2203&Source=0)<br>
此外該技術具備「高空穩定性」，可於15kg~25kg的荷載下，7級陣風中穩定飛行。同時可於5分鐘以內完成單一風機檢測任務，風機檢測時間縮短，更能有效擴展到大規模巡檢。<br>
<iframe width="1031" height="580" src="https://www.youtube.com/embed/vW6TbXJ-cpw" title="無停轉風機無人機巡檢系統技術" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
### 全自動風機葉片表面瑕疵檢測
[開發AI檢測風機葉片瑕疵 要比人工更準更快](https://www.windtaiwan.com/ArticleView.aspx?ID=ART00632)<br>
![](https://www.windtaiwan.com/Upload/20220517/perceptual-robotics-and-the-university-of-bristol-announce-results-of-innovate-uk-data-analysis-project-image-11-1536x866.jpg?ID=ART00632)

---
### 工業巡檢
Flyability ELIOS2 工業巡檢無人機
![](https://i0.wp.com/www.esentra.com.tw/wp-content/uploads/2019/05/3e4899693c35ca47c8c6c6f27f159515-450x450.jpg)
Flyability ELIOS 3 無人機-局限空間檢查/數位建模
![](https://i0.wp.com/www.esentra.com.tw/wp-content/uploads/2022/05/24165f504bca70bac19d038be3ff5ead-450x450.jpg)

<iframe width="765" height="430" src="https://www.youtube.com/embed/JWkf8qMOcB4" title="風力發電機  Flyability室內無人機檢查" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<br />
<br />

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

