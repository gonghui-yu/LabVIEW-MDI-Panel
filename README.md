# LabVIEW-MDI-Panel
# 简介
MDI是多文档界面（Multi-document Interface）,可以在主窗口中创建嵌入多个同类型的子窗口，并以多种方式排列显示。

本项目基于Windows user32.dll API开发，只能在32位LabVIEW上运行。

本项目基于LabVIEW的Actor Framework框架，可以同时将多个Actor Core界面插入.net panel容器中排列显示。

# 项目介绍
项目主要包含一个主窗口管理基类Actor（[MDI] Parent）和一个子窗口基类Actor（[MDI] Child）。MDI相关逻辑代码均在这两个基类Actor中完成，使用时只需要创建对应Actor继承基类即可。