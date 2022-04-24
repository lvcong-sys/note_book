# 爬虫练习

## scrapy框架认识

*   scrapy的安装

*   创建scrapy项目

*   问题发现

    > TypeError: write() argument must be str, not bytes

    查看问题代码

    ```python
    html = response.body
    filename = "index.html"
    file = open(filename, "w")
    file.write(html)
    file.close()
    ```

    解决方法：将file = open(filename, "w")中的w改成wb就行了

    深究：为何“html = response.body”获取的数据是bytes类型
