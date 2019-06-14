# 通过 ```gitbook build``` 生成的目录无法跳转的解决办法

 原因：

 解决办法：

 1. 在导出的文件夹目录下找到gitbook->theme.js文件

 ![p1](assets/imgs/QQ浏览器截图20190614220138.png)

 2.搜索  if(m)for(n.handler&&

 3.将 if(m) 替换为 if(false)

 4.保存后用浏览器重新打开index.html
