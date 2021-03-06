---
title: 更新内容
tags: 更新说明,小书匠
category: 小书匠/帮助手册
slug: storywriter/upgrade_log
grammar_mindmap: true
renderNumberedHeading: true
grammar_code: true
grammar_decorate: true
grammar_mathjax: true
---

<div style="text-align:center;">
<div style="border:2px solid green;border-radius:5px;margin:.5em auto;padding:0 .5em;width:fit-content;font-size:2em;display:inline-block;font-family: SlideTownsoul">


**==<i class="fas fa-award fa-2x fa-fw"></i>[杨杰 个人博客](http://soft.xiaoshujiang.com/blog/story-writer/2021-essay-contest)<i class="fas fa-award fa-2x fa-fw"></i>==**

</div>
</div>

[toc!?direction=lr]

# 小书匠收费

## 收费与不收费的区别

### 收费

#### 收费项目
1. pdf 定制化导出(pdf封面，水印，加密等)
2. 支持在线更新，优先使用新功能
3. 配置数据同步
4. 自定义数据中心
5. [更多...](http://soft.xiaoshujiang.com/blog/story-writer/vip-feature)

#### 收费价格

1. 详细价格可以查看该[地址](http://soft.xiaoshujiang.com/price/)
 
### 不收费

1. 免费又实用的功能太多了，不知道重点写什么好，自己到 http://soft.xiaoshujiang.com/feature.html 这里看吧.....

## 其他

http://soft.xiaoshujiang.com/price.html

[小书匠价格及邀请活动奖励调整说明](http://soft.xiaoshujiang.com/blog/price_change_plan)

[小书匠 2021 征文奖励会员说明](http://soft.xiaoshujiang.com/blog/story-writer/2021-essay-contest)

___

# 升级日志


> # <i class="fas fa-exclamation-triangle"></i>注
> 如果您从较老版本的小书匠升级，内置数据库会有不兼容问题，建议在升级前进行数据导出备份，或者数据库文件备份，防止升级失败。
> 
> **数据库文件路径**
> 
> ``` 
> Windows: %LOCALAPPDATA%/storywriter/ 
> Mac: ~/Library/Application
> Support/storywriter/ Linux: ~/.config/storywriter 
> ```

<!-- {#newestUpdate}-->

<div style="text-align:center;">
<div style="border:2px solid green;border-radius:5px;margin:.5em auto;padding:0 .5em;width:fit-content;font-size:2em;display:inline-block;font-family: SlideTownsoul">


**==<i class="fas fa-award fa-2x fa-fw"></i>[小书匠 2021 征文奖励会员活动](http://soft.xiaoshujiang.com/blog/story-writer/2021-essay-contest)<i class="fas fa-award fa-2x fa-fw"></i>==**

</div>
</div>
## 8.5.8

### 8.5.8 新功能

1. 数学公式提示添加详细说明及预览（[视频介绍](http://soft.xiaoshujiang.com/blog/story-writer/mathjax-showhint)）

### 8.5.8 修改

1. 调整数学公式编号对齐
2. 修复数学公式 tag 标签在导出印象笔记时，图片被缩小的问题
3. 调整新建模板内容
4. 删除导出 html 文件里内嵌的 fontawesome css 引用

<!--{#newestUpdateEnd}-->


## 8.5.7

### 8.5.7 新功能

1. 添加数学公式添加自动提示功能


### 8.5.7 修改

1. 改进 CodeMirror goGroupRight/Left命令(即 <kbd>ctrl+right/left</kbd>) 的中文定位（[视频介绍](http://soft.xiaoshujiang.com/blog/story-writer/editor-for-chinese-enhancer)）
2. 修复浮动编辑器部份快捷键事件外溢问题


## 8.5.6

### 8.5.6 新功能

1. 浮动编辑器提供多标签切换功能

### 8.5.6 修改

1. 修复代码块行高亮范围出错的问题


## 8.5.5

### 8.5.5 修改

1. 超链接粘贴优化
2. 修复换下一页后，浮动编辑器无法及时更新文章内容的问题
3. 优化底层数据处理，解决 #1466 问题


## 8.5.4

### 8.5.4 新功能

1. 支持 gif 图片剪切板复制

### 8.5.4 修改

1. 日历样式调整
2. CodeMirror 编辑器下，调整粘贴超链接操作
3. 调整代办清单样式
4. 修复 html 转 markdown 时，粘贴 html 出错问题


## 8.5.3

### 8.5.3 新功能

1. 添加一个随机发现新主题功能
2. 添加一个中国红主题


## 8.5.2

### 8.5.2 修改

1. CodeMirror 编辑器 vim 下光标样式调整
2. 全文搜索时, 英文搜索词进行特殊处理，英文大小写不需要区分
3. 浮动编辑器状态切换样式调整
4. 编辑器主题样式调整


## 8.5.1

### 8.5.1 修改

1. 修复 tls 问题 #1464
2. 调整 CodeMirror 编辑器下 vim 按键 b, w, e 对中文定位的行为


## 8.5.0

### 8.5.0 新功能

1. 系统过滤器对免费用户开放 [查看教程](http://soft.xiaoshujiang.com/docs/tutorial/filter/)
2. 联网状态下，客户端添加随机谚语功能（会员用户可以在设置里禁止掉）


### 8.5.0 修改

1. 默认开启数学公式语法
2. 修复浮动编辑器窗口大小调整后，内容排版错误的问题
3. 修复 window 下，客户端最小字体无效问题
4. 修复元数据改动后，预览效果没有及时生效的问题
5. 第三方默认存储控制按钮样式调整
6. 表格预览样式调整
7. 解决复制到微信公众号，图片太小时，无法正确上传图片的问题
8. 带编号公式在微信公众号中的显示效果调整
9. 图床迁移时，提供进度显示效果
10. `关于`页面调整
11. 代码块快捷键有时会失效的问题 #1463


# 其他

[小书匠更新手册](storywriter/upgrade_log)
[小书匠语法手册](storywriter/grammar)
[小书匠使用手册](storywriter/tutorial)
