---
UID: 202312051939
title: 
tags:
  - todo
created: 2023-12-05
topic: 
ranking: 
target: 
author: yanyi
---

status::  #00_Status/01_Ongoing 

## 文件分类
Legacy Version 1 2022-10 : [[Templator 新建笔记 Version 1|Templator 新建笔记 Version 1]]
Current Version 2023-11: [[Templator 新建笔记 Version 2]]
![[Templator 新建笔记 Version 2]]

## Quick Add
see [quick add documentation](https://quickadd.obsidian.guide/docs/Choices/MultiChoice)
我设置的快捷键：option⌥ + command⌘ + A
功能：调出一个菜单，实现快捷指令

![[../../../90-Attachment/Screenshot 2023-12-06 at 11.22.12.png]]


生成便签，悬浮大纲和收拢侧边栏都是Blue Topaz的作者提供的。
我自己设置的是“Add” 和 “Log”两个指令

### Add
说明：这一功能利用了Obsidian自带的Templates插件**在当前文件中**根据指定的模版键入文字
例子：
- 鼠标放在文档最前边，加入实现准备好的yaml header模版
- 更新读书笔记的时候，在最下边一行加入今天的日期和填写页码等的地方
- 在Folder file 和Tag page里新增Dataview代码块来列出相应的文件夹/标签下存放的所有笔记（这样就不用记dataview的语法了）

实现方法：
1. 在Templates的设定中，指定所有模版存放的文件夹
2. 模版新建和修改在Templates文件夹中进行
3. 在Quick Add 中新建一个Macro指令，调动Templates: Insert from templates命令

模版文件夹目前包含以下内容：
```dataview
LIST From "88-Template/Templates"
```

### Log
说明：使用Quick add插件中的“**Capture**”功能在**已经建好的某个文件**中根据指定的模版键入文字
例子：
- 同时在做3个项目，对其中项目C的代码进行了修改。希望在项目C的log文件中更新对改修改的说明
- 懒得去翻Archery_log的位置，想要在其中留出更新今天训练成果的位置。

实现方法：
1. 在Capture to file name那里填写希望填入的文件的路径或者tag，如果同一个tag下有多个文件的话，quick add会弹出文件列表以供选择。比如说，我现在有4个同时进行的project，

![[../../../90-Attachment/Pasted image 20231206112256.png]]



## Zotero + Obsidian Workflow

a wonderfully useful workflow example [here](https://bagerbach.com/blog/how-i-read-research-papers-with-obsidian-and-zotero)






