# Hexo-Pure-Theme

官方链接：https://github.com/cofess/hexo-theme-pure

v 1.0
> update_at:2020/2/9

1.除去文章底部的copyright
在`themes\pure\layout\_partial\post`下编辑copyright.ejs
删除copyright部分。
2.解决tags页面没有标签的问题
打开source/tags目录下index.md文件修改为：
```
title: 加油喔！
date: 2020-01-15 11:46:10
type: "tags"
layout: "tags"
```
这里的layout要注意添加。