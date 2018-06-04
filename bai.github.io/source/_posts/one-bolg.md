---
title: 使用方式
date: 2018-06-03 21:42:55
categories:
    -Hexo使用
tags:
    -博客编写
description: 第一次使用markdown的方式写博客,记录一下语法的使用
---

<div id="music163player">
    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=28815250&auto=1&height=66"></iframe>
  </div>

常用命令

``` base
hexo new "postName" #新建文章
hexo generate #生成静态页面至public目录
hexo clean #清除缓存
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本

缩写
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
组合命令
hexo s -g #生成并本地预览
hexo d -g #生成并上传
```

``` base
title:  # 这是标题
categories:  # 这里写的分类会自动汇集到 categories 页面上，分类可以多级
- 实用技术 # 一级分类
- 个人博客 # 二级分类
tags:   # 这里写的标签会自动汇集到 tags 页面上
- 实用 # 可配置多个标签，注意格式
- 个人博客
description: #博客的详细介绍
```

表格

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

``` base
创建表格和其他文字留出一行空格
| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |
```

[超链接](https://hexo.io/)
``` bash
[超链接](https://hexo.io/)
```
# 一级标题(最大字号)
## 二级标题(比一级标题小一号)
### 三级标题(比二级标题小一号)
#### 四级标题(比三级标题小一号)
##### 五级标题(比四级标题小一号)
###### 六级标题(比五级标题小一号)
``` bash
# 一级标题(最大字号)
## 二级标题(比一级标题小一号)
### 三级标题(比二级标题小一号)
#### 四级标题(比三级标题小一号)
##### 五级标题(比四级标题小一号)
###### 六级标题(比五级标题小一号)
```


代码高亮
``` java
public static void main(String[] args) {  }

```

`文本突出`

``` base
 `文本突出`
```

分割线

---

``` base
---
```

图片插入

![风景](http://img06.tooopen.com/images/20180603/tooopen_sy_241631515411.jpg)
``` base
![风景](http://img06.tooopen.com/images/20180603/tooopen_sy_241631515411.jpg)
```

