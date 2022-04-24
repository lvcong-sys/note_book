# Themleaf（[相关博客](https://www.yiibai.com/thymeleaf)）

* themleaf整合Spring boot
* themleaf的基本使用
* 在使用themleaf所遇到的问题

  * th:href的携参问题：含有三种方式，详情见[相关博客](https://blog.csdn.net/enkidu66/article/details/107097070?ops_request_misc=&request_id=&biz_id=102&utm_term=th:href%E5%B8%A6%E5%8F%82&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-0-107097070.nonecase&spm=1018.2226.3001.4187)
  * 携带多参数：[相关博客](http://www.yayihouse.com/yayishuwu/chapter/1989)
  * 拼接url地址：[相关博客](https://blog.csdn.net/qq_39566715/article/details/102883824?ops_request_misc=&request_id=&biz_id=102&utm_term=themleaf%20th:href%E6%8B%BC%E6%8E%A5%E5%9C%B0%E5%9D%80&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-3-102883824.first_rank_v2_pc_rank_v29&spm=1018.2226.3001.4187)


* 异步请求与局部刷新
  * 异步请求：使用Ajax框架，传递JSON数据。[相关博客](https://blog.csdn.net/oppo5630/article/details/52093898?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163913338916780265414878%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163913338916780265414878&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-52093898.first_rank_v2_pc_rank_v29&utm_term=Springboot%E4%B8%AD%E4%BD%BF%E7%94%A8ajax&spm=1018.2226.3001.4187)

  * 局部刷新：jsp已经被抛弃，在thymeleaf模板引擎中的标签方言。([thymeleaf学习]([Thymeleaf一篇就够了_bigsai-CSDN博客](https://blog.csdn.net/qq_40693171/article/details/107008457?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163837060816780264081854%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163837060816780264081854&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-107008457.first_rank_v2_pc_rank_v29&utm_term=Thymeleaf&spm=1018.2226.3001.4187)))

    * 使用<mark>th:fragment="table_refresh"</mark>属性对局部刷新的部分进行标记

    * 使用<mark>$('#table_refresh').load("/refresh/local")</mark>传递要显示的数据
