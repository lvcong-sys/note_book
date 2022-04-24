# Spring boot使用

#### 作为spring的PRO版本，spring boot强大的注解功能令人神往

---

* spring boot的主要注解了解：[相关博客]([springboot的注解的作用说明（全）_fenlin88l的博客-CSDN博客_springboot实体类注解](https://blog.csdn.net/fenlin88l/article/details/89466723?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163912781516780255224079%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163912781516780255224079&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-89466723.first_rank_v2_pc_rank_v29&utm_term=springboot%E4%B8%AD%E7%9A%84%E6%B3%A8%E8%A7%A3&spm=1018.2226.3001.4187)) 

* 使用**Hibernate-Validator**进行参数校验。[相关博客1]([使用Hibernate-Validator优雅的校验参数_学习-CSDN博客_hibernate validator](https://blog.csdn.net/java_collect/article/details/85534054?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163937907016780357237123%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163937907016780357237123&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-85534054.first_rank_v2_pc_rank_v29&utm_term=hibernate-validator&spm=1018.2226.3001.4187)) 、[相关博客2]([Hibernate Validator 使用介绍 - 简书](https://www.jianshu.com/p/0bfe2318814f))、[相关博客3]([Hibernate-validator校验框架_飘飘怡然心-CSDN博客_validator.validate](https://blog.csdn.net/xgblog/article/details/52548659?ops_request_misc=&request_id=&biz_id=102&utm_term=validator&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-6-52548659.first_rank_v2_pc_rank_v29&spm=1018.2226.3001.4449))、[相关博客4]([SpringBoot使用Validation校验参数_JustryDeng-CSDN博客_validation](https://blog.csdn.net/justry_deng/article/details/86571671?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163938568816780274163273%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163938568816780274163273&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~sobaiduend~default-2-86571671.pc_v2_rank_blog_default&utm_term=Validation&spm=1018.2226.3001.4450)) 

* Spring中的Model对象。参考[1]([SpringMVC中的Model对象_Yang_Hui_Liang的博客-CSDN博客_springmvc的model](https://blog.csdn.net/Yang_Hui_Liang/article/details/87931555?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.highlightwordscore&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-1.highlightwordscore))、[2]([SpringMVC框架中ModelAndView、Model、ModelMap的区别与使用_Java仗剑走天涯-CSDN博客_java modelmap](https://blog.csdn.net/baidu_37107022/article/details/77864971?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0.highlightwordscore&spm=1001.2101.3001.4242.1))

* spring boot中的class path：[相关博客](https://blog.csdn.net/qq_35772435/article/details/105251885?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164083766816780357275837%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164083766816780357275837&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-105251885.first_rank_v2_pc_rank_v29&utm_term=springboot%E4%B8%AD%E7%9A%84classpath&spm=1018.2226.3001.4187)

* 在使用Spring boot框架的情况下如何修改文件上传的限制
  * 当application是yml格式，其配置方式如下：![image-20220103001804176](https://s2.loli.net/2022/01/03/ZYfJ3lo7mBQz8Pd.png)
  * 当是properties：[相关博客](https://blog.csdn.net/cscscssjsp/article/details/84847965?ops_request_misc=&request_id=&biz_id=102&utm_term=springboot%20yml%E4%BF%AE%E6%94%B9%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E7%9A%84%E9%99%90%E5%BA%A6&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-2-84847965.first_rank_v2_pc_rank_v29&spm=1018.2226.3001.4187)

* 关于 

  > org.springframework.web.multipart.support.StandardMultipartHttpServletRequest$StandardMultipartFile' to required type 'java.io.File'; nested exception is java.lang.IllegalArgumentException: Cannot convert value of type报错反省：在spring boot中默认使用的MultipartFile

* spring boot上传文件：[相关博客](https://blog.csdn.net/gnail_oug/article/details/80324120?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164087938716780255243668%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164087938716780255243668&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-80324120.first_rank_v2_pc_rank_v29&utm_term=springboot%E4%B8%8A%E4%BC%A0%E6%96%87%E4%BB%B6&spm=1018.2226.3001.4187)

* dcm4che-core导包失败：[相关博客](https://blog.csdn.net/weixin_30905981/article/details/94910910?ops_request_misc=&request_id=&biz_id=102&utm_term=maven%E9%85%8D%E7%BD%AEDcm4Che&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-5-94910910.first_rank_v2_pc_rank_v29&spm=1018.2226.3001.4187)

* Spring boot中的热部署：

  
