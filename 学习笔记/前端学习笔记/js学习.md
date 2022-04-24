# JS学习

## 介绍

js与css相似

### js获取相对地址

[相关博客](https://blog.csdn.net/wen8792xing/article/details/51026606?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164144792616780255254562%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164144792616780255254562&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-51026606.first_rank_v2_pc_rank_v29&utm_term=js%E8%8E%B7%E5%8F%96%E7%BB%9D%E5%AF%B9%E8%B7%AF%E5%BE%84&spm=1018.2226.3001.4187)

```js
function  getPath(){
                     var pathName = document.location.pathname;
                     var index = pathName.substr(1).indexOf("/");
                    var result = pathName.substr(0,index+1);
                    return result;
                 }
```

