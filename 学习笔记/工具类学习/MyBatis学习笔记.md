# MyBatis学习笔记

* mybatis是一款jdbc的映射框架，封装了与数据库连接的方法，所以在进行数据库查询时只要在xml中进行简单的数据库配置。

* 在使用查询时先在实体类对应的映射文件中设置实体与数据库字段之间的映射关系。例如：![](C:\Users\Kobe\AppData\Roaming\marktext\images\2021-12-24-17-30-52-image.png)
  
  如此会将所查询的数据自动封装到对应的实体类中，不进行设置则需在查询语句中进行声明，加大了代码的冗余。使用逆向工程的话会进行自动设置。

* 多表查询
  
  * 根据数据表之间的联系，合理地对实体类添加属性。如：![](C:\Users\Kobe\AppData\Roaming\marktext\images\2021-12-24-17-30-11-image.png)
  
  * 在映射文件中添加![](C:\Users\Kobe\AppData\Roaming\marktext\images\2021-12-24-19-08-12-image.png)

* 代码优化。[相关博客]([MyBatis 多表联合查询及优化_紫羽风的博客-CSDN博客_mybatis多表关联查询](https://blog.csdn.net/happylee6688/article/details/45967763?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163945097616780261954469%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163945097616780261954469&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~baidu_landing_v2~default-5-45967763.first_rank_v2_pc_rank_v29&utm_term=mybatis%E5%A4%9A%E8%A1%A8%E5%85%B3%E8%81%94%E6%9F%A5%E8%AF%A2&spm=1018.2226.3001.4187)) 

* 有关映射的相关工具：[BeanSearch](https://searcher.ejlchina.com/)

* Mybatis通用分页插件：[Mybatis-PageHelper](https://github.com/pagehelper/Mybatis-PageHelper)

* 
