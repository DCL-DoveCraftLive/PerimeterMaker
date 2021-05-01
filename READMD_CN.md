[English](README.md) | **中文**
# 注意
这个插件并非我原创的  
而是魔改原本的[PerimeterMaker](https://github.com/Ivan-1F/MCDReforged-Plugins/tree/master/PerimeterMaker)  
我修复了这个插件在制造空置域过程中会让水流出来变成一个巨大的水域的特性  

---

在创造/镜像服中快速制造空置域，逐层操作，防止卡顿

## 注意事项

由于需要修改fill上限，所以需要[Carpet Mod](https://github.com/gnembon/fabric-carpet)的支持

## 安装

将`PerimeterMake.py`文件放入`/plugins`文件夹

## 使用

 - `!!perimeter help` 显示帮助信息
 - `!!perimeter make <length> <width>` 以当前位置为中心清理一个空置域
 - `!!perimeter commit` 在使用make后使用，确认操作
 - `!!perimeter abort` 在任何时候中断操作

## 可修改常量

### DELAY

默认值：`DELAY = 1`

每修改一层后的延迟，按照服务器性能决定
