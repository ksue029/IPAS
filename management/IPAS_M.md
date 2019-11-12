#
```
主題一:資訊安全管理概念:
1_1_資訊安全目標_機密性、完整性與可用性
1_2_資訊安全管理系統

主題二:資產與風險管理
2_1_資產分類分級與盤點
2_2_風險評鑑與風險處理

主題三:存取控制與身分認證
3_1_存取控制與特權管理
3_2_身分認證

主題四:事故管理與營運持續
4_1_事件與事故管理
4_2_備援與營運持續

主題五:法規遵循與資訊倫理
5_1_隱私保護與智慧財產權
5_2_資訊倫理、法規遵循與稽核
```

# 主題一:資訊安全管理概念:

## 1_1_資訊安全目標_機密性、完整性與可用性

### CIA機密性、完整性與可用性
```
機密性 (Confidentiality)

完整性(Integrity)

可用性(Availability)
```


### 保護資訊C.I.A.不同的技術與方法
```
• 機密性保護
– 加解密技術
– 存取控制

• 完整性保護
– 雜湊函數
– 數位簽章
– 存取控制

• 可用性保護
– 容量規劃
– 備份
– 容錯、備援及負載平衡
– 存取控制

• 法規的遵循
```
## 1_2_資訊安全管理系統 ISMS

## ISMS

## ISO 27001

### ISO 27000
```
已發布的標準
ISO/IEC 27000 — 資訊安全管理系統 - 綜述及詞彙
ISO/IEC 27001 — 資訊安全管理系統 - 要求
ISO/IEC 27002 — 資訊安全管理實踐準則
ISO/IEC 27003 — 資訊安全管理系統實施指導
ISO/IEC 27004 — 資訊安全管理系統 - 測評

ꝍ ISO/IEC 27005 — 資訊安全風險管理

ISO/IEC 27006 — 針對審查及認證資訊安全管理系統的實體之要求
ISO/IEC 27007 — 資訊安全管理系統審查指導 （本標準專注於管理系統）
ISO/IEC TR 27008 — 資訊安全管理系統審查者指導 （本標準專注於資訊安全控制）
ISO/IEC 27010 — 對於跨領域，跨組織間通訊的資訊科技，保安技巧及資訊安全管理
ISO/IEC 27011 — 對於電信組織根據ISO/IEC 27002標準的資訊安全管理指導
ISO/IEC 27013 — ISO/IEC 20000-1 和 ISO/IEC 27001 整合實施的指導
ISO/IEC TR 27015 — 對於金融服務的資訊安全管理指導
ISO/IEC 27031 — 對於配備資訊及通訊技術的業務連續性的知道
ISO/IEC 27032 — 網路保安的指導（本質上講的是如何做一個「網際網路上的好鄰居」）
ISO/IEC 27033-1 — 網路保安的綜述及概念
ISO/IEC 27033-2 — 設計和實施網路保安的指導
ISO/IEC 27033-3:2010 — 網路情況的參考 - 威脅，設計應對方式及管控
ISO/IEC 27034 — 應用程式保安的指導
ISO/IEC 27035 — 保安事件管理
ISO/IEC 27037 — 鑑別，收集並且（或者）獲得並儲存電子證物的指導
ISO 27799 — 健保業實施ISO/IEC 27002的資訊安全管理
```

```
仍然在制定中的標準
ISO/IEC 27014 — 資訊安全統治框架

ꝍ ISO/IEC 27017 — 雲端系統的資訊安全管理
ꝍ ISO/IEC 27018 — 雲端系統的資料保護

ISO/IEC 27033 — 資訊科技網路保安
ISO/IEC 27036 — 供應關係的保安指導
ISO/IEC 27038 — 數位檔案編譯的規格
ISO/IEC 27039 — 入侵發現及保護系統
ISO/IEC 27040 — 貯存保安指導
ISO/IEC 27041 — 確保數位證據調查方式
ISO/IEC 27042 — 分析和解釋數位證據
ISO/IEC 27043 — 數位證據的調查原理和工序
```
### 重要資安概念
```
邊界與分類(Boundary and classification)

職務區隔(Segregation of duties, SOD)
  https://en.wikipedia.org/wiki/Separation_of_duties
  
縱深防禦(Layered defense, defense in depth)
  https://en.wikipedia.org/wiki/Defence_in_depth
  
單一脆弱點(Single point of failure, SPOF)
  https://en.wikipedia.org/wiki/Single_point_of_failure
  
阿奇里斯腱(Achilles heel)

木桶理論(Bucket principle）
   https://www.linkedin.com/pulse/20140817185525-243637-the-bucket-principle
   
僅知原則(Need to know)
   https://en.wikipedia.org/wiki/Need_to_know
```
### 重要字辭
```
機密性 (Confidentiality)

完整性(Integrity)

可用性(Availability)

可靠度(Reliability)

有效性(Effectiveness)

可歸責性(Accountability)

不可否認性(Non-repudiation)

ISO 27001/ISMS(資訊安全管理系統)

PDCA(Plan、Do、Check、Action)

政策(Policy)

矯正措施(CAPA)

控制項(Control Item)

風險管理(Risk Management)

教育訓練/意識(Training/Awareness)

量測/績效(Measurement / Performance)

```

# 主題二:資產與風險管理

## 2_1_資產分類分級與盤點

### 資訊資產項目分類
```
•實體資產
– 所有電腦設備、通信與網路設備及相關週邊設備等

• 軟體資產
– 自行或委外開發之軟體、套裝軟體、公用程式等

• 電子化資訊資產
– 電子儲存之文件、系統資料、組態設定檔、稽核紀錄檔等

• 書面文件
– 書面管理文件與紀錄、系統相關文件等

• 服務
– 通訊、網路、照明、電力等

• 人員
– 正式職員、約聘人員、廠商駐點人員及工讀生等
```

### 資訊資產蒐集與管理
```
[1]蒐集資訊資產清冊
– 硬體、軟體、資料、紙本、人員
[2]分類群組
– 將資訊資產進行分類
[3]實作控管
– 依不同分類群組進行不同管控
[4]管理機制 
```
## 2_2_風險評鑑與風險處理

### 風險
```
威脅(Threat)利用資產(Asset)的脆弱性(Vulnerability)
造成衝擊(Impact)的可能性(Likelihood)
```

### 風險評鑑(Assessment)
```
風險識別(identification)

風險分析(analysis)

風險評估(Evaluation)

```

### 風險處理
```
選擇控制

有效追蹤

降低(reduce)

避免(Avoid)

接受(Accept)

移轉(Transfer)

```

### 重要字辭
```
資產弱點
– 資訊資產本身存在之特性，可被威脅利用而使得資訊資產遭受破壞。

• 風險識別與分析
– 可利用弱點，因而對資訊資產造成破壞的外在因素。
– 各類弱點會因為不同威脅的發生而產生風險，故需考量威脅發生之重大性。

• 可接受風險
– 由資訊安全組織依所面臨之風險及所願意投入之資源，而決定風險可接受水準，以作為控管機制設計執行者

• 殘餘風險管理（接受風險、移轉風險、降低風險、規避風險）
– 當控管規範或機制增加或強化後，應重新評估風險權值，並重複執行辨認及降低風險步驟，直到降至風險可接受水準為止。

```
# 主題三:存取控制與身分認證

## 3_1_存取控制與特權管理

### 定義
```
主體(Subject)

物件(Object)

存取(Access)

存取規則(Access Rule)

信賴路徑(Trusted Path)
```

### 類型
```
實體類控制(Physical Controls)

技術類控制(Technical Controls)

管理類控制(Administrative Controls)

```

### 功能
```
防禦性(Preventive)

偵測性(Detective)

矯正性(Corrective)

嚇阻性(Deterrent)

復原性(Recovery)

補償性(Compensation)

```

### 管理
```
身分識別(Identification)

身分鑑別(Authentication)

授權(Authorization)

可歸責性(Accountability)

```

### 授權原則
```
業務需知原則/ 僅知(Need to know)

最低權限原則(Least privilege)

職務區隔(SOD)

特殊權限管理

```
## 3_2_身分認證

### 因素
```
所知之事，你知(Something you know)

所持之物，你有(Something you have)

所具之形，你是(Something you are)

```
# 主題四:事故管理與營運持續

## 4_1_事件與事故管理

## 4_2_備援與營運持續

# 主題五:法規遵循與資訊倫理

## 5_1_隱私保護與智慧財產權

## 5_2_資訊倫理、法規遵循與稽核

