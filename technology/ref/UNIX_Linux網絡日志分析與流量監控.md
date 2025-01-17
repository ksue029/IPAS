#
```
UNIX/Linux網絡日志分析與流量監控
作者： 李晨光
出版社：機械工業出版社
出版日期：2015/01/01

```

```
第一篇 日志分析基礎
第1章 網絡日志獲取與分析
1.1 網絡環境日志分類
1.1.1 UNIX/Linux系統日志
1.1.2 Windows日志
1.1.3 Windows系統日志
1.1.4 網絡設備日志
1.1.5 應用系統的日志
1.2 Web日志分析
1.2.1 訪問日志記錄過程
1.2.2 Apache訪問日志的作用
1.2.3 訪問日志的位置
1.2.4 訪問日志格式分析
1.2.5 HTTP返回狀態代碼
1.2.6 記錄Apache虛擬機日志
1.2.7 Web日志統計舉例
1.2.8 Apache錯誤日志分析
1.2.9 日志輪詢
1.2.10 清空日志的技巧
1.2.11 其他Linux平台Apache日志位置
1.2.12 Nginx日志
1.2.13 Tomcat日志
1.2.14 常用Apache日志分析工具
1.3 FTP服務器日志解析
1.3.1 分析vsftpd.log和xferlog
1.3.2 中文對Vsftp日志的影響
1.3.3 用Logparser分析FTP日志
1.4 用LogParser分析Windows系統日志
1.4.1 LogParser概述
1.4.2 LogParser結構
1.4.3 安裝LogParser
1.4.4 LogParser應用舉例
1.4.5 圖形化分析輸出
1.5 Squid服務日志分析
1.5.1 Squid日志分類
1.5.2 典型Squid訪問日志分析
1.5.3 Squid時間戳轉換
1.5.4 Squid日志位置
1.5.5 圖形化日志分析工具
1.5.6 其他UNIX/Linux平台的Squid位置
1.6 NFS服務日志分析
1.6.1 Linux的NFS日志
1.6.2 Solaris的NFS服務器日志
1.7 iptables日志分析
1.8 Samba日志審計
1.8.1 Samba默認提供的日志
1.8.2 Samba審計
1.9 DNS日志分析
1.9.1 DNS日志的位置
1.9.2 DNS日志的級別
1.9.3 DNS查詢請求日志實例解釋
1.9.4 DNS分析工具dnstop
1.10 DHCP服務器日志
1.11 郵件服務器日志
1.11.1 Sendmail
1.11.2 Postfix
1.12 Linux下雙機系統日志
1.12.1 Heartbeat的日志
1.12.2 備用節點上的日志信息
1.12.3 日志分割
1.13 其他UNIX系統日志分析GUI工具
1.13.1 用SMC分析系統日志
1.13.2 Mac OS X的GUI日志查詢工具
1.14 可視化日志分析工具
1.14.1 彩色日志工具ccze
1.14.2 動態日志查看工具logstalgia
1.14.3 三維日志顯示工具gource
1.14.4 用AWStats監控網站流量


第2章 UNIX/Linux系統取證
2.1 常見IP追蹤方法
2.1.1 IP追蹤工具和技術
2.1.2 DoS/DDoS 攻擊源追蹤思路
2.2 重要信息收集
2.2.1 收集正在運行的進程
2.2.2 查看系統調用
2.2.3 收集/proc系統中的信息
2.2.4 UNIX文件存儲與刪除
2.2.5 硬盤證據的收集方法
2.2.6 從映像的文件系統上收集證據
2.2.7 用ddrescue恢復數據
2.2.8 查看詳細信息
2.2.9 收集隱藏目錄和文件
2.2.10 檢查可執行文件
2.3 常用搜索工具
2.3.1 特殊文件處理
2.3.2 The Coroner』s Toolkit（TCT工具箱）
2.3.3 Forensix工具集
2.4 集成取證工具箱介紹
2.4.1 用光盤系統取證
2.4.2 屏幕錄制取證方法
2.5 案例一：閃現Segmentation Fault為哪般
事件背景
互動問答
疑難解析
預防措施
2.6 案例二：誰動了我的膠片
事件背景
了解業務流程
公司內鬼所為？
取證分析
遺忘的Squid服務器
互動問答
疑點分析
誘捕入侵者
疑難解析
預防措施

第3章 建立日志分析系統
3.1 日志采集基礎
3.1.1 Syslog協議
3.1.2 Syslog日志記錄的事件
3.1.3 Syslog.conf配置文件詳解
3.1.4 Syslog操作
3.1.5 Syslog的安全漏洞
3.1.6 Rsyslog
3.1.7 Syslog-ng
3.2 時間同步
3.2.1 基本概念
3.2.2 識別日志中偽造的時間信息
3.2.3 時間同步方法
3.3 網絡設備日志分析與舉例
3.3.1 路由器日志分析
3.3.2 交換機日志分析
3.3.3 防火牆日志分析
3.3.4 實戰：通過日志發現ARP病毒
3.3.5 實戰：交換機環路故障解決案例
3.4 選擇日志管理系統的十大問題
3.5 利用日志管理工具更輕松
3.5.1 日志主機系統的部署
3.5.2 日志分析與監控
3.5.3 利用Eventlog Analyzer分析網絡日志
3.5.4 分析防火牆日志
3.6 用Sawmill搭建日志平台
3.6.1 系統簡介
3.6.2 部署注意事項
3.6.3 安裝舉例
3.6.4 監測網絡入侵
3.7 使用Splunk分析日志
3.7.1 Splunk簡介
3.7.2 Splunk安裝
3.7.3 設置自動運行
3.7.4 系統配置
3.7.5 設置日志分析目錄


第二篇 日志分析實戰
第4章 DNS系統故障分析
4.1 案例三：邂逅DNS故障
事件背景
查看防火牆日志
外部防火牆
內部防火牆（NAT）
互動問答
取證分析
問題解答
預防措施
4.2 DNS漏洞掃描方法
4.2.1 DNS掃描的關鍵技術
4.2.2 檢查工具
4.3 DNS Flood Detector讓DNS更安全
4.3.1 Linux下DNS面臨的威脅
4.3.2 BIND漏洞
4.3.3 DNS管理
4.3.4 應對DNS Flood攻擊
4.3.5 DNS Flood Detector保安全


第5章 DoS防御分析
5.1 案例四：網站遭遇DoS攻擊
事件背景
交互問答
事件推理
針對措施
疑難解答
案例總結
DoS擴展知識
5.2 案例五：「太囧」防火牆
事件背景
路由器部分日志文件
防火牆日志文件
互動問答
調查分析
答疑解惑
預防措施


第6章 UNIX后門與溢出案例分析
6.1 如何防范rootkit攻擊
6.1.1 認識rootkit
6.1.2 rootkit的類型
6.2 防范rootkit的工具
6.2.1 使用chkrootkit工具
6.2.2 Rootkit Hunter工具
6.3 安裝LIDS
6.3.1 LIDS的主要功能
6.3.2 配置LIDS
6.3.3 使用Lidsadm工具
6.3.4 使用LIDS保護系統
6.4 安裝與配置AIDE
6.4.1 在Solaris中安裝AIDE
6.4.2 用AIDE加固OSSIM平台
6.4.3 Tripwire
6.5 案例六：圍堵Solaris后門
入侵背景
分析腳本文件bd
分析腳本doc
分析腳本文件ps
分析腳本update（一個嗅探器）
分析腳本milk
發現need.tar被植入系統
問題
答疑解惑
預防措施
6.6 案例七：遭遇溢出攻擊
事件背景
分析日志
網絡入侵檢測系統日志（取樣）
發現系統賬號問題
問題
案例解碼
分析解答
預防措施
6.7 案例八：真假root賬號
事件背景
恢復root密碼
取證分析
互動問答
問題解答
預防措施
6.8 案例九：為rootkit把脈
事件背景
可疑的/etc/xinetd.conf記錄
互動問答
事件分析
疑難解答
預防措施
第7章 UNIX系統防范案例
7.1 案例十：當網頁遭遇篡改之后
事件背景
日志獲取
互動問答
入侵事件剖析
疑難解答
防護措施
Web漏洞掃描工具——Nikto
7.2 案例十一：UNIX下捉蟲記
事件背景
取證分析
互動問答
入侵解析
Sadmind/IIS蠕蟲分析
Unicode攻擊逆向分析
問題解答
預防措施
7.3 案例十二：泄露的裁員名單
事件背景
取證分析
互動問答
答疑解惑
預防措施


第8章 SQL注入防護案例分析
8.1 案例十三：后台數據庫遭遇SQL注入
案例背景
互動問答
分析過程
疑難解答
預防與補救措施
8.2 案例十四：大意的程序員之SQL注入
事件背景
互動問答
分析取證
總結
答疑解惑
總結
預防措施
8.3 利用OSSIM監測SQL注入
8.3.1 SQL注入攻擊的正則表達式規則
8.3.2 用OSSIM檢測SQL注入
8.3.3 OSSIM系統中的Snort規則
8.4 LAMP網站的SQL 注入預防
8.4.1 服務器端的安全配置
8.4.2 PHP代碼的安全配置
8.4.3 PHP代碼的安全編寫
8.5 通過日志檢測預防SQL注入
8.5.1 通過Web訪問日志發現SQL攻擊
8.5.2 用Visual Log Parser分析日志


第9章 遠程連接安全案例
9.1 案例十五：修補SSH服務器漏洞
事件背景
SSH被攻擊的日志舉例
加固SSH服務器
通過OSSIM實現SSH登錄失敗告警功能
預防措施
9.2 案例十六：無辜的「跳板」
事件背景
交互問答
案情分析
疑難解答
預防措施


第10章 Snort系統部署及應用案例
10.1 Snort安裝與使用
10.1.1 准備工作
10.1.2 深入了解Snort
10.1.3 安裝Snort 程序
10.1.4 維護Snort
10.1.5 Snort的不足
10.2 Snort日志分析
10.2.1 基於文本的格式
10.2.2 典型攻擊日志舉例
10.2.3 Snort探針部署
10.2.4 日志分析工具
10.3 Snort 規則詳解
10.3.1 Snort 規則分析
10.3.2 編寫Snort規則
10.4 基於OSSIM平台的WIDS系統
10.4.1 安裝無線網卡
10.4.2 設置OSSIM無線傳感器
10.5 案例研究十七：IDS系統遭遇IP碎片攻擊
事件背景
故障處理
數據包解碼
疑難問題
問題解答
防范策略
Snort與Iptables聯動
測試效果
IP碎片攻擊的預防措施
評估NIDS工具
IDS系統與網絡嗅探器的區別
總結
10.6 案例十八：智取不速之客
事件背景
互動問答
取證分析
疑難解答
預防措施
案例啟示


第11章 WLAN案例分析
11.1 WLAN安全漏洞與威脅
11.1.1 WLAN主要安全漏洞
11.1.2 WLAN面對的安全威脅
11.2 案例十九：無線網遭受的攻擊
事件背景
AP的日志
尋找非法AP接入點
互動問答
將幾段事件還原
疑點解析
預防措施
11.2.1 WIFI上網日志的收集
11.2.2 用開源NAC阻止非法網絡訪問
11.2.3 企業中BYOD的隱患
11.3 案例二十：無線會場的「不速之客」
事件背景
取證分析


第12章 數據加密與解密案例
12.1 GPG概述
12.1.1 創建密鑰
12.1.2 導入和簽訂密鑰
12.1.3 加密和解密
12.1.4 簽訂和驗證
12.2 案例二十一：「神秘」的加密指紋
事件背景
疑難問題
案情解碼
中間人攻擊
MITM通常采用的手段
一種ARP欺騙的預防措施
分析攻擊過程
答疑解惑
預防措施


第三篇 網絡流量與日志監控
第13章 網絡流量監控
13.1 網絡監聽關鍵技術
13.1.1 網絡監聽
13.1.2 SNMP協議的不足
13.1.3 監聽關鍵技術
13.1.4 NetFlow與sFlow的區別
13.1.5 協議和應用識別
13.1.6 網絡數據流采集技術
13.1.7 SPAN的局限
13.2 用Netflow分析網絡異常流量
13.2.1 NetFlow的Cache管理
13.2.2 NetFlow的輸出格式
13.2.3 NetFlow的抽樣機制
13.2.4 NetFlow的性能影響
13.2.5 NetFlow在蠕蟲病毒監測中的應用
13.3 VMware ESXi服務器監控
13.4 應用層數據包解碼
13.4.1 概述
13.4.2 系統架構
13.4.3 Xplico的數據獲取方法
13.4.4 Xplico部署
13.4.5 應用Xplico
13.4.6 深入分析Xplico
13.5 網絡嗅探器的檢測及預防
13.5.1 嗅探器的檢測
13.5.2 網絡嗅探的預防


第14章 OSSIM綜合應用
14.1 OSSIM的產生
14.1.1 概況
14.1.2 從SIM到OSSIM
14.1.3 安全信息和事件管理（SIEM）
14.2 OSSIM架構與原理
14.2.1 OSSIM架構
14.2.2 Agent事件類型
14.2.3 RRD繪圖引擎
14.2.4 OSSIM工作流程分析
14.3 部署OSSIM
14.3.1 准備工作
14.3.2 OSSIM服務器的選擇
14.3.3 分布式OSSIM系統探針布署
14.3.4 OSSIM 系統安裝步驟
14.4 OSSIM安裝后續工作
14.4.1 時間同步問題
14.4.2 系統升級
14.4.3 防火牆設置
14.4.4 訪問數據庫
14.4.5 OSSIM數據庫分析工具
14.4.6 同步OpenVAS插件
14.4.7 安裝遠程管理工具
14.4.8 安裝X-Windows
14.5 使用OSSIM系統
14.5.1 熟悉主界面
14.5.2 SIEM事件控制台
14.6 風險評估方法
14.6.1 風險評估三要素
14.6.2 OSSIM系統風險度量
14.7 OSSIM關聯分析技術
14.7.1 關聯分析
14.7.2 OSSIM的通用關聯檢測規則
14.8 OSSIM日志管理平台
14.8.1 OSSIM日志處理流程
14.8.2 Snare
14.8.3 通過WMI收集Windows日志
14.8.4 配置OSSIM
14.8.5 Snare與WMI的區別
14.9 OSSIM系統中的IDS應用
14.9.1 HIDS/NIDS
14.9.2 OSSEC HIDS Agent安裝
14.9.3 在ESXi中安裝OSSEC
14.9.4 OSSEC代理監控的局限
14.10 OSSIM流量監控工具應用
14.10.1 流量過濾
14.10.2 Ntop監控
14.10.3 流量分析
14.10.4 Ntop故障排除
14.10.5 網絡天氣圖
14.10.6 設置Netflow
14.10.7 Nagios監視
14.10.8 與第三方監控軟件集成
14.11 OSSIM應用資產管理
14.11.1 OCS Inventory NG 架構
14.11.2 OCS安裝與使用
14.12 OSSIM在蠕蟲預防中的應用
14.13 監測shellcode
14.14 OSSIM在漏洞掃描中的應用
14.14.1 漏洞評估方法
14.14.2 漏洞庫
14.14.3 采用OpenVAS掃描
14.14.4 分布式漏洞掃描
14.14.5 Metasploit的滲透測試
14.14.6 在Metasploit中加載Nessus
14.15 常見OSSIM應用問答
```
