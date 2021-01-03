# NKUST_SystemAnalysis


# 第8組 資安情報服務網站
- 組長 C107118208 黃閔弘 :mens:
- 組員 C107118201 詹翔驛 :secret:
- 組員 C107118235 胡懷剛 :baby_symbol:
- 組員 C107118238 柯承睿 :baby_symbol:


# 內容
## 本計畫主要目的在於: 提供使用者最新網路威脅情資 (Cyber Threat Intelligence)，分類出各項資訊安全類別讓使用者客製化想得知的情報，並提供漏洞回報服務功能。

近年來網路快速蓬勃發展，迅速且複雜的特性讓企業面臨嚴峻的網路威脅挑戰，網路罪犯者能針對特定的組織、產業和客戶進行網路攻擊。時至今日，資安攻防已是不對稱戰力之競爭，單一企業愈來愈難以對抗有組織、且專業分工的駭客集團。在新的網路戰場上，威脅來自於世界各地，企業應意識到若要面對全新的威脅需要有強大威脅情資 (Cyber Threat Intelligence) 收集能力，企業決策者可利用網路威脅情資做出符合目前外部威脅趨勢及最正確的資安決策指示。另外，產業間的威脅資訊分享機制能有效提供早期資安預警情資、聯防與資安防護改善的良性循環，以降低資安事件發生衝擊及企業營運被迫中斷之風險。


# 甘特圖
![甘特圖](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/甘特圖.png)

# PERT
![PERT](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/PERT.png)

# 功能性需求
- 獲得並提供資安防護資訊(儀表板,搜尋引擎)
- 客製化使用者想得知的資訊，透過email訂閱寄送最新訊息
- 提供漏洞回報表單

# 非功能性需求
- 使用性
- 可靠度
- 效能

# FDD
![FDD](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/系統架構圖.png)

# 需求分析
- 使用者可透過儀表板查看目前所提供的所有資料
- 使用者可透過搜尋引擎尋找亦搜尋的資料
- 使用者可以輸入信箱訂閱獲得客製化最新資訊
- 使用者可提供漏洞情報提供服務平台更多情報

# 使用案例圖
![使用案例圖](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/使用案例圖.png)

# 使用案例說明
| 使用案例名稱    | 搜尋引擎        |
| ------------- |:-------------:| 
| 行動者         | 使用者      | 
| 說明         | 描述使用搜尋引擎過程      | 
| 完成動作       | 1.選擇欲搜尋的分類向 <br/>2.輸入欲搜尋的關鍵字 <br/>3.搜尋|  
| 假設         | 無      | 


| 使用案例名稱    | 使用搜尋引擎        |
| ------------- |:-------------:| 
| 行動者         | 使用者      | 
| 說明         | 描述搜尋引擎使用過程      | 
| 完成動作       | 使用者輸入亦搜尋項目(漏洞種類,日期,是否修補....)      |  
| 假設         | 無      | 


| 使用案例名稱    | 訂閱客製化內容        |
| ------------- |:-------------:| 
| 行動者         | 使用者      | 
| 說明         | 描述訂閱客製化內容過程      | 
| 完成動作       | 使用者輸入欲獲得情報的Email並選取使用者想得知的資安情報     |  
| 假設         | 無      | 


# DFD
![DFD](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/DFD.png)


# DFD0
![DFD](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/DFD0.png)

# UML
![UML](https://raw.githubusercontent.com/minhonglolz/NKUST_SystemAnalysis/main/UML.PNG)

# 循序圖1
![循序圖1](https://raw.githubusercontent.com/minhonglolz/NKUST_SystemAnalysis/main/循序圖1.png)

# 循序圖2
![循序圖2](https://raw.githubusercontent.com/minhonglolz/NKUST_SystemAnalysis/main/循序圖2.png)

# 循序圖3
![循序圖3](https://raw.githubusercontent.com/minhonglolz/NKUST_SystemAnalysis/main/循序圖3.png)

# 活動圖1
![活動圖1](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/活動圖1.png)

# 活動圖2
![活動圖2](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/活動圖2.png)

# 活動圖3
![活動圖3](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/活動圖3.png)

# 分鏡圖1
![分鏡圖1](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/分鏡圖01.png)

# 分鏡圖2
![分鏡圖2](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/分鏡圖02.png)

# 搜尋引擎
| 欄位名稱    | 資料型態        | 驗證規則   |  功能   | 
| ------------- | ------------- |------------- |------------- |
| 使用這者搜尋       | String     | 存在檢查(existence check) 資料型態檢查(data type check) | 產出相關資料 |
| Type         | Select      | 存在檢查(existence check) 資料型態檢查(data type check) | 產出相關資料 |
| Platfrom         | Select      | 存在檢查(existence check) 資料型態檢查(data type check) | 產出相關資料 |
| Port         | Select      | 存在檢查(existence check) 資料型態檢查(data type check) | 產出相關資料 |
| Tag         | Select      | 存在檢查(existence check) 資料型態檢查(data type check) | 產出相關資料 |

# 圖表
| 欄位名稱    | 資料型態        | 驗證規則   |  功能   | 
| ------------- | ------------- |------------- |------------- |
| 圖表1         | Pie      | 存在檢查(existence check) 資料型態檢查(data type check) | 歷年漏洞總量圖表 |
| 圖表2         | Line      | 存在檢查(existence check) 資料型態檢查(data type check) | 漏洞成長比較表 |
| 圖表3         | Line      | 存在檢查(existence check) 資料型態檢查(data type check) | 歷年漏洞成長比較表 |

# ERD

## 搜尋ERD
![ERD1](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/ERD1.png)

## 訂閱ERD
![ERD2](https://github.com/minhonglolz/NKUST_SystemAnalysis/blob/main/ERD2.png)
