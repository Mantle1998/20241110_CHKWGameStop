# 2024/11/10 CHKWGameStop

//新增
1. SaInfo.java
(1) Bean => getter/setter

2. SaInfoController.java
(1) @GetMapping("/saInfo") => sa資料總覽
(2) @GetMapping("/saInfo/json") => 顯示json回傳值

3. SaInfoRepository.java
(1) DAO => 繼承自 Spring Data JPA 提供的 JpaRepository 介面

4. saInfo.html
(1) 新增 => 未完成
(2) 查詢 => searchSaInfo() 已完成 
(3) 編輯 => 未完成
(4) 讀取 => loadSaInfo() 已完成

5. saHeader.html
管理員功能
(1) CHKWGameStop
(2) 管理員資料總覽
(3) 會員資料總覽
(4) 商品總覽
(5) 文章總覽
(6) 訂單總覽
(7) 評論總覽
(8) 客服表單總覽
(9) FAQ文章總覽


//修改

6. application.properties
(1) 新增Thymeleaf setting 
