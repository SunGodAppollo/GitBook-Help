# GitBook报错处理

>一,建议处理的Gitbook的Bug
```
Error: ENOENT: no such file or directory, stat ‘C:***demo_book\_book\gitbook\gitbook-plugin-fontsettings\fontsettings.js’
```
这是Vesion：3.2.3的一个 BUG
解决办法 : 打开 用户\ .gitbook\versions\3.2.3\lib\output\website\copyPluginAssets.js
将所有的 confirm: true 更改为 confirm: false
