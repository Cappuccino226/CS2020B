#
```
最新版本： Java SE 14 (2020 年 3 月 17 日)
```
#
```
《好好學Java 從零基礎到項目實戰》附錄源碼
清華大學出版社出版　　　　作者：歐陽燊
https://github.com/aqi00/java
```
```
https://www.tutorialspoint.com/compile_java_online.php

https://www.jdoodle.com/online-java-compiler/
```
```
public class HelloWorld{

     public static void main(String []args){
        System.out.println("Hello World");
     }
}
```
```
$javac HelloWorld.java

$java -Xmx128M -Xms16M HelloWorld
Hello World
```

```
第1章 Java開發環境搭建 1
1.1 JDK的安裝和配置 1
1.1.1 Java的發展歷程 1
1.1.2 下載和安裝JDK 2
1.1.3 配置環境變數 4
1.2 IntelliJ IDEA的安裝與配置 5
1.2.1 安裝IntelliJ IDEA 6
1.2.2 配置IntelliJ IDEA 7
1.2.3 運行第一個Java程式 9
1.3 Java虛擬機器（JVM） 12
1.3.1 Java程式的運行機制 13
1.3.2 JVM的體系結構 13
1.3.3 JVM、JRE與JDK的區別 15
1.4 Java程式設計的基本概念 16
1.4.1 Java的代碼結構 16
1.4.2 Java的特殊官吏 19
1.4.3 Java的度量衡 22
1.5 小結 25


第2章 數學運算 26
2.1 數值變數 26
2.1.1 數值變數的類型 26
2.1.2 特殊數字的表達 28
2.1.3 強制類型轉換 30
2.2 算數運算 32
2.2.1 四則運算符 32
2.2.2 設定運算子 34
2.2.3 一元運算子 35
2.3 數學函數 37
2.3.1 取整函數 37
2.3.2 取亂數 38
2.3.3 科學計算函數 38
2.3.4 三角函數 39
2.4 實戰練習 39
2.4.1 利用牛頓反覆運算法求平方根 39
2.4.2 利用割圓術求解圓周率 42
2.5 小結 46 [1] 


第3章 邏輯控制 47
3.1 邏輯運算 47
3.1.1 布林類型及其運算 47
3.1.2 關係運算子 49
3.1.3 運算子的優先順序順序 50
3.1.4 按位元邏輯與短路邏輯 52
3.2 控制語句 53
3.2.1 條件分支 53
3.2.2 多路分支 54
3.2.3 while迴圈 56
3.2.4 for迴圈 58
3.3 陣列 59
3.3.1 一維陣列 60
3.3.2 二維陣列 62
3.3.3 冒號的幾種用法 64
3.3.4 陣列工具Arrays 67
3.4 實戰練習 71
3.4.1 求解“雞兔同籠”問題 71
3.4.2 求解“韓信點兵”問題 72
3.4.3 利用二分查找法定位元陣列元素 74 [2] 
3.5 小結 77


第4章 方法與包裝 78
4.1 方法定義 78
4.1.1 方法的組成形式 78
4.1.2 方法的輸入參數 80
4.1.3 方法的輸出參數 83
4.2 基本類型包裝 86
4.2.1 數數值型別包裝 86
4.2.2 包裝變數的運算 88
4.2.3 布林類型包裝 89
4.3 大數位類型 90
4.3.1 大整數BigInteger 90
4.3.2 大小數BigDecimal 91
4.4 實戰練習 93
4.4.1 通過方法遞迴實現階乘函數 93
4.4.2 利用牛頓反覆運算法求大數開方 95
4.4.3 利用大數位求更精確的圓周率 97
4.5 小結 100


第5章 字串與規則運算式 101
5.1 字元 101
5.1.1 字元類型 101
5.1.2 字元型與整型的相互轉化 102
5.1.3 字元包裝類型 104
5.2 字串 105
5.2.1 字串的賦值與轉換 105
5.2.2 字串的格式化 107
5.2.3 其他常見的字串方法 111
5.3 規則運算式 113
5.3.1 利用正則串分割字串 113
5.3.2 利用規則運算式校驗字串 117 [2] 
5.4 實戰練習 120
5.4.1 從地址串中解析收件人信息 120
5.4.2 校驗身份證號碼的合法性 124
5.5 小結 128


第6章 日期時間 129
6.1 日期工具Date 129
6.1.1 日期工具的用法 129
6.1.2 日期時間的格式化 131
6.2 日曆工具Calendar 134
6.2.1 日曆工具的用法 134
6.2.2 日曆工具的常見應用 136
6.3 Java 8的本地日期時間工具 139
6.3.1 本地日期LocalDate和本地時間LocalTime 139
6.3.2 本地日期時間與字串的互相轉換 142
6.4 實戰練習 144
6.4.1 從1582年問題淺談Date工具的局限 144
6.4.2 利用本地日期時間實現萬年曆 148
6.5 小結 150



第7章 類的三要素 151
7.1 類的封裝 151
7.1.1 類的成員定義 151
7.1.2 類的構造方法 156
7.1.3 this關鍵字的用法 157
7.2 類的繼承 159
7.2.1 類的簡單繼承 159
7.2.2 父類：關鍵字super的用法 161
7.2.3 幾種開放性修飾符 164
7.3 類的多態 165
7.3.1 多態的發生場景 165
7.3.2 對象的類型檢查 167
7.3.3 終態：關鍵字final的用法 169
7.4 實戰練習：定義銀行的帳戶類 171
7.5 小結 177


第8章 特殊的類 178
8.1 類的嵌套 178
8.1.1 內部類和嵌套類 178
8.1.2 靜態：關鍵字static的用法 181
8.1.3 枚舉類型 185
8.2 類的抽象 188
8.2.1 抽象類別 188
8.2.2 簡單介面 190
8.2.3 Java 8之後的擴展介面 193
8.2.4 匿名內部類 195
8.3 函數式程式設計 198
8.3.1 Lambda運算式 198
8.3.2 函數式介面的定義 200
8.3.3 雙冒號標記的方法引用 202
8.3.4 靜態方法引用和實例方法引用 206
8.4 實戰練習 210
8.4.1 實現建造者模式 210
8.4.2 實現單例模式 214
8.5 小結 218


第9章 容器與泛型 219
9.1 容器的種類 219
9.1.1 集合：HashSet和TreeSet 219
9.1.2 映射：HashMap和TreeMap 224
9.1.3 清單：ArrayList和LinkedList 226
9.2 泛型的規則 228
9.2.1 從泛型方法探究泛型的起源 229
9.2.2 泛型類的定義及其運用 232
9.2.3 Java 8新增的幾種泛型介面 234
9.3 容器的加工 240
9.3.1 容器與陣列互轉 240
9.3.2 容器工具Collections 242
9.3.3 Java 8新增的流式處理 243
9.4 實戰練習 246
9.4.1 利用泛型實現通用的二分查找演算法 246
9.4.2 借助容器實現兩種常見的排隊演算法 249
9.5 小結 253


第10章 類的進階用法 254
10.1 異常 254
10.1.1 常見的程式異常 254
10.1.2 記憶體溢出的兩種錯誤 257
10.1.3 異常的處理：扔出與捕捉 259
10.1.4 如何預防異常的產生 263
10.1.5 使用Optional規避空指針異常 265
10.2 反射 269
10.2.1 物件導向的後門——反射 269
10.2.2 利用反射技術操作私有屬性 271
10.2.3 利用反射技術操作私有方法 273
10.3 注解 275
10.3.1 如何使用系統自帶的注解 276
10.3.2 注解的基本單元——元注解 278
10.3.3 利用注解技術檢查空指針 279
10.4 小結 283



第11章 文件I/O處理 284
11.1 文件讀寫 284
11.1.1 檔與目錄的管理 284
11.1.2 字元流讀寫 286
11.1.3 緩衝區讀寫 290
11.1.4 隨機訪問檔的讀寫 293
11.2 I/O輸入輸出流 295
11.2.1 檔I/O位元組流 296
11.2.2 緩存I/O位元組流 297
11.2.3 物件序列化 299
11.2.4 I/O流處理簡單的資料壓縮 302
11.3 NIO檔程式設計 304
11.3.1 文件通道FileChannel 304
11.3.2 位元組緩存ByteBuffer 307
11.3.3 檔通道的性能優勢 309
11.3.4 路徑工具Paths和Files 311
11.4 實戰練習：檔的分割與合併 314
11.5 小結 317


圖形介面程式設計

第12章 AWT介面程式設計 318
12.1 AWT的窗口面板 318
12.1.1 框架Frame 318
12.1.2 按鈕Button 320
12.1.3 佈局Layout 322
12.2 AWT的文本控制項 324
12.2.1 標籤Label 324
12.2.2 輸入框TextField和TextArea 328
12.2.3 選擇框Checkbox 330
12.3 AWT的影像處理 332
12.3.1 自訂圖像視圖 332
12.3.2 繪圖工具Graphics 334
12.3.3 利用Graphics2D加工圖像 337
12.4 實戰練習：生成驗證碼圖片 341
12.5 小結 344



第13章 Swing介面程式設計 345
13.1 Swing的基礎介面 345
13.1.1 框架JFrame和按鈕JButton 345
13.1.2 標籤JLabel 347
13.1.3 利用標籤顯示圖像 349
13.2 Swing的簡單控制項 350
13.2.1 輸入框的種類 351
13.2.2 選擇框的種類 352
13.2.3 清單方塊的種類 355
13.3 Swing的高級控制項 359
13.3.1 表格JTable 359
13.3.2 基本對話方塊 361
13.3.3 文件對話方塊 364
13.4 實戰練習 368
13.4.1 簡單的登錄介面 368
13.4.2 將Java代碼匯出JAR包 371
13.5 小結 373



第14章 JavaFX介面程式設計 374
14.1 JavaFX的基本場景 374
14.1.1 JavaFX的初始配置 374
14.1.2 窗格Pane 377
14.1.3 按鈕Button和標籤Label 379
14.1.4 箱子HBox和VBox 382
14.2 JavaFX的常用控制項 385
14.2.1 輸入框的種類 385
14.2.2 選擇框的種類 388
14.2.3 清單與表格 393
14.2.4 對話方塊的種類 397
14.3 JavaFX的佈局設計 403
14.3.1 FXML佈局的基本格式 403
14.3.2 實現FXML對應的控制器 407
14.3.3 FXML佈局的伸展適配 409
14.4 實戰練習 412
14.4.1 房貸計算器（簡易版） 412
14.4.2 JavaFX匯出可執行程式 417
14.4.3 房貸計算器（完整版） 420
14.5 小結 424


第15章 多執行緒 425
15.1 執行緒的調度 425
15.1.1 執行緒的基本用法 425
15.1.2 任務Runnable 430
15.1.3 過程Callable 433
15.1.4 計時器與定時任務 435
15.2 併發的控制 437
15.2.1 同步：關鍵字synchronized的用法 437
15.2.2 通過加解鎖避免資源衝突 440
15.2.3 信號量Semaphore的請求與釋放 443
15.2.4 執行緒間的通信方式 447
15.3 執行緒池管理 451
15.3.1 普通執行緒池 451
15.3.2 計時器執行緒池 456
15.3.3 分治框架Fork/Join 459
15.4 實戰練習 463
15.4.1 碼錶計時器 463
15.4.2 打地鼠遊戲 467
15.5 小結 473


第16章 網路通信 474
16.1 網路交互的資料格式 474
16.1.1 URL位址的組成格式 474
16.1.2 JSON串的解析 477
16.1.3 XML報文的解析 482
16.2 HTTP介面訪問 486
16.2.1 GET方式的HTTP調用 486
16.2.2 POST方式的HTTP調用 492
16.2.3 Java 11新增的HttpClient 495
16.2.4 HttpClient實現下載與上傳 499
16.3 通訊端Socket通信 502
16.3.1 利用Socket傳輸文本 502
16.3.2 使用Socket傳輸檔 507
16.3.3 採用UDP協定的Socket通信 510
16.3.4 利用HttpServer搭建簡易伺服器 512
16.4 實戰練習 514
16.4.1 HTTP測試工具 515
16.4.2 讓Java程式輸出日誌檔 519
16.4.3 多人即時通信——仿QQ聊天 523
16.5 小結 534


第17章 資料庫操作 535
17.1 MySQL環境搭建 535
17.1.1 安裝MySQL資料庫 535
17.1.2 安裝MySQL工作臺 547
17.1.3 資料庫操縱語言SQL的用法 553
17.2 JDBC程式設計 557
17.2.1 JDBC的應用原理 557
17.2.2 通過JDBC管理資料庫 559
17.2.3 通過JDBC查詢資料記錄 562
17.2.4 預報告PreparedStatement 565
17.3 資料庫連接池 567
17.3.1 C3P0連接池 567
17.3.2 Druid連接池 569
17.4 實戰練習 572
17.4.1 代碼生成工具 572
17.4.2 讓Java程式讀取設定檔 578
17.4.3 詩歌管理系統——古詩三百首 581
17.5 小結 589

附錄A 服務端工程的使用說明 590
A.1 下載並安裝Tomcat 590
A.2 給IDEA安裝Tomcat外掛程式 591
A.3 添加Tomcat的運行配置 592
A.4 啟動Tomcat伺服器 595 [2]

```
