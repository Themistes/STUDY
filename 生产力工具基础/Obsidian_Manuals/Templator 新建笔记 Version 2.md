---
UID: 202312011812
title: 
tags: todo
created: 2023-12-01
topic: 
ranking: 
target: 
author: yanyi
---

status::  #00_Status/01_Ongoing 

核心插件：Templator

1. 在Obsidian核心设置中找到Files & Links页面，将默认文件的新建位置设置为[[../../../03-OtherInbox/03-OtherInbox|03-OtherInbox]]
2. 在Templator插件设置中找到Folder Templates的选项，新建一个规则，将规则适用的文件夹设置为03-OtherInbox: 
	- ![[../../../90-Attachment/Screenshot 2023-12-01 at 17.30.42.png]]
3. 编写新规则中的Template [[tp-笔记收集箱]]
	- 笔记收集箱虽然是一个.md文件，但它其实是一个纯粹的规则程序。
	- 它的作用是使得obsidian能够弹出一个下拉窗口，从Study Work 人物模版 双链中选择需要创建的笔记类型，选择后，新建的笔记会套用指定的文件模版。
	- 这些模版既有obsidian的弹窗程序，也包含输入到新文件的内容。如果要更改yaml heading的具体内容和增加段落分割的话，需要在有"tp-"前缀的模版文件中修改。
			- [[../../../88-Template/tp/tp-study_v2|tp-study_v2]] : 在11-Study/110-Inbox文件夹中新建
			- [[../../../88-Template/tp/tp-work_v2|tp-work_v2]] : 在12-Work/120-Inbox文件夹中新建
			- [[../../../88-Template/tp/tp-人物模板|tp-人物模板]]
			- [[../../../88-Template/tp/tp-双链模板|tp-双链模板]]：在80-Links文件夹中新建




