# Universal Rocket Delta-V Calculator / 通用火箭dV计算器

A simple rocket delta-V calculator made with Excel, using Tsiolkovsky rocket equation. 

It is suitable for 1 to 4-stage rockets with or without boosters, calculating the dV when the rocket expended or any stage of it reused. 

使用 Excel 制作的一个火箭速度增量 (delta-V, dV) 计算器，原理为简单的齐奥尔科夫斯基火箭方程。

可以计算 1 至 4 级火箭的 dV，有无助推均可，且允许回收火箭的任意一级或多级。

[![en](https://img.shields.io/badge/Language-en-dodgerblue.svg)](#user-guide)
[![en](https://img.shields.io/badge/Language-zh--cn-red.svg)](#使用说明)

## User Guide

### Files

All files essential are Excel workbooks. The reason for not using code is that code needs to be ran manually each time a parameter is adjusted, so does saving and arranging the result. (Actually this calculator was written in Python before, but I converted it into a workbook afterwards.) 

- [Universal_dV_calculator.xlsx](\Universal_dV_calculator.xlsx): An Excel workbook that contains a teplate for dV calculation and 70+ rockets' calculation result. 

    The template can be copied to any place to use, and there's a full instruction in that worksheet. 

    The listed rockets consist of Chinese and other countries' operational, under development and retired rockets, as well as little-known ones such as SSTOs, rockets of Chinese private enterprises, and creations by my web pals.

- [Rocket_gadget.xlsx](\Rocket_gadget.xlsx): Another workbook composed of multiple gadgets. For example: dividing something by 9.8, calculating mass ratio using dry mass and fuel mass, etc. 
    
    There're some tools that are more complex, such as estimating the unused fuel at stage 1 seperation for reusing it (not accurate but useful), and optimizing the second stage mass of a 2-stage rocket. 
    
    I also added some tools for SSTO, nuclear thermal engine and space elevator, which is not precise at all and just for fun.

- [Reference](\Reference): (Useless for English users) Some Chinese rockets' essays or screenshots that contain useful data. As for data of other countries' rockets, it can be found in the URLs listed in those workbooks. 

- [通用dV计算器.xlsx](\通用dV计算器.xlsx) and [火箭小工具.xlsx](\火箭小工具.xlsx): Those workbooks above, but in Chinese.

### Notes

- Please read **Notes in the template worksheet** carefully, which contains most of the things.

- The workbooks are not suitable for Excel dark mode. (But they can still be used.)

- There're some Chinese sentenses that I do not have time to translate, which are not necessary.

- Things that are simplified during calculation:

    - Stage 1 dV is calculated using vacuum Isp 

    - Boosters shall be all the same

    - No fairing mass

    - Expendable dV is calculated in the case that there's 0% fuel left at separation time (Actually there shall be 1% or so)

    - Throttling does not affect Isp (Actually it did)

    - Throttling is considered at a fixed percentage all the time (Affects rocket dV with boosters but not much)

- This calculator is not able to calculate the payload with a fixed dV, but you can change the payload manually to reach that dV. 

- Sorry for the bad translation!

## 使用说明

文件均为 Excel 表格。主要是代码的话每次还需要点击运行，并且整理输出结果。其实以前就是用的 Python，但最后花大时间改成 Excel 了。

### 文件

- [通用dV计算器.xlsx](\通用dV计算器.xlsx)：用来算 dV 的表格，里面有一个模板，以及套用模板的 70 多种火箭。模板可以整体复制到别的地方用，里面有说明。火箭列表里有国内外的现役、退役和 PPT 火箭，以及一些冷门火箭如国内民营火箭、论文火箭、SSTO，以及吧友自创的。

- [火箭小工具.xlsx](\火箭小工具.xlsx)：辅助计算的小工具合集。如：除以 9.8，算干质比。更高级的有：算回收时一级额外剩下的燃料的（不准，但很有用），优化二级火箭级间比的。我甚至加了算 SSTO、核推和太空电梯的，就更不准了，图一乐。

- [Reference](\Reference)：参考文献。国内一堆老火箭数据和新火箭 PPT。有的论文给我换成截图了，否则太大了。国外的数据都用的网页链接，大多需要梯，不过能上 github 还用担心么。

- [Universal_dV_calculator.xlsx](\Universal_dV_calculator.xlsx) 和 [Rocket_gadget.xlsx](\Rocket_gadget.xlsx)：英文版的那俩表格。

### 注意事项

- 请仔细阅读**模板里的注意事项**，大多数都在里面。

- 表格不适用于 Excel 暗色模式（但是还能用吧）

- 表格的中文用的还是宋体，可能有点太难看了。如果想改，可以全选整个工作簿然后换成微软雅黑（先用 Shift 和左键全选底部一栏的所有工作表，再在任一工作表里全选，最后将字体改成微软雅黑，注意光改字体，我怕有别的改坏了。）

- 计算中简化的部分：

    - 1 级 dV 用了真空比冲计算

    - 助推只能是全都一模一样的（不能同时捆两种）

    - 没算整流罩质量

    - 全抛 dV 默认燃料耗尽（实际上会有 1% 剩余吧）

    - 节流不影响比冲（实际上影响）

    - 节流时按照一直以相同比例节流来计算（影响带助推的 dV，不过不多）

- 本计算器没法通过给定 dV 来算运力，不过可以手动调整运力到适当的 dV。





