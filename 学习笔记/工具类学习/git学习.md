# Git学习

## 了解git:[相关博客](https://blog.csdn.net/df19900725/article/details/79578610?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164086185916780264096363%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164086185916780264096363&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~baidu_landing_v2~default-4-79578610.first_rank_v2_pc_rank_v29&utm_term=git%E7%AE%80%E4%BB%8B&spm=1018.2226.3001.4187)

* git是基于Linux开发出来的一款版本控制工具

* 其被使用在码云和GitHub等各大代码托管平台

## 在idea中使用git所遇到的问题

* 在提交代码是报错： **Push to origin/master was rejected**
  
  * 原因：远程代码与本地代码发生冲突
  
  * 解决：使用<mark>git push -u origin master -f</mark>对代码进行强制推送，即设置一下权限即可[相关博客](https://blog.csdn.net/mygodit/article/details/84869504?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163911422116780271523942%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163911422116780271523942&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-84869504.first_rank_v2_pc_rank_v29&utm_term=Push+to+origin%2Fmaster+was+rejected&spm=1018.2226.3001.4187)

报错<mark>error:Entry 'xxxxxx' not uptodate.Cannot merge.</mark>

* 原因

* 解决如下
  
  * ```git
    $ git pull 
    ...... 
    file your_file.rb not up to date, cannot merge. 
    
    $ git stash 
    $ git pull 
    $ git stash pop 
    或者
    there is another method to fix it as below
    
    xintan.chen@announce:~/ARM/m1-kernel$git checkout -f HEAD
    
    xintan.chen@announce:~/ARM/m1-kernel$git pull
    
    Already up-to-date.
    ```
    
    
