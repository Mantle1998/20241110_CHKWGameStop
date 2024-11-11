# CHKWGameStop

11/10 

//新增
1. SaInfo.java
(1) Bean => getter/setter

2. SaInfoController.java
(1) @GetMapping("/saInfo") => sa資料總覽
(2) @GetMapping("/saInfo/json") => 顯示json回傳值

3. SaInfoRepository.java
(1) DAO => 繼承自 Spring Data JPA 提供的 JpaRepository 介面

4. SaHeader.html
(1) 新增 => 未完成
(2) 查詢 => searchSaInfo() 已完成 
(3) 編輯 => 未完成
(4) 讀取 => loadSaInfo() 已完成

//修改

5. application.properties
(1) 新增Thymeleaf setting 
