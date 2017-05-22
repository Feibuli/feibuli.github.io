---
layout: post
title: "Angular实战Demo"
date: 2016-11-20 
tag: 前端分享 
---  
## todomvc案例

### todomvc 功能分析

1.显示数据列表

2.添加任务

3.删除任务
  — 使用了数组的splice

4.修改任务
  - 只是改变页面是否可以编辑的一个状态

5.切换是任务是否完成的状态

6.批量的切换任务是否完成的状态
  - 使用了ng-change事件

7.清除已完成任务
  - 尽量不要在循环中添加或删除数组元素。

7.1 控制清除已完成任务按钮的显示与否 

8.显示未完成的任务数
  - 是给ng-bind指定一个方法,方法最终会返回一个具体的值,
  - ng-bind 会把这个值渲染到页面。

9.切换不同状态任务的显示与否

### todomvc code
   [点击这里下载](https://github.com/Feibuli/Angular)
