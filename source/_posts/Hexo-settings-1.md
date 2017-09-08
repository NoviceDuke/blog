---
title: 設定 Settings（一）
categories:
- Hexo
tags:
- Hexo
- Github
---
## Instroduction

已經能產生基本的部落格架構了，接下來當然是不要在本機上自爽了，利用`Gitgub.io`的靜態網頁，把`Hexo`編譯後的html，部署上去。

----

![螢幕快照 2017-09-08 上午8.09.04.png](resources/C720110B44AB842116965FBBF38F6CE3.png =1253x874)

## main_config
這是指專案下的設定檔
可以設定作者、語系、部署位置等相關設定
講解幾個比較重要的

### Url
這是顯示`Hexo`的路徑，如果你的專案名稱是用`xxx.github.io`，可以忽略不修改。但如果是跟我一樣是用專案的方式去產生，那麼就要在`_config.yml`設定子名稱
```sh
  url: https://github.com/作者/專案名稱
  root:/專案名稱/
```
> 修改URL的時候，也可以利用本地執行`hexo server`來觀察設定是否成功
> `xxx.github.io` 是`Github` 官方幫各帳號預設的靜態網頁
--- 