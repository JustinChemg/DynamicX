如果你此时还只能看到代码画面而看不到渲染画面，可以去安装编辑markdown的软件（如：Typora，VSCode等），目前使用VSCode编写markdown是免费的， [这里有配置过程](https://www.jianshu.com/p/9c0f9b6c5936)，或者直接上网搜索`VSCode 配置 markdown`。

## 考核内容
- 按照`STM32_MinimumSystem.pdf`给出的原理图，自行新建Kicad工程并绘制原理图和PCB，部分`符号`无法在官方的符号库中找到，在`symbols.kicad_sym`文件中提供，需要大家自行导入Kicad。

- 需要按照`作业提交方法.md`中的说明，创建并提交到github仓库，可以查看[github提交模板](https://github.com/582864732/DynamicX_xxx)，其中有详细的说明。

## 考核要求

1. 完成原理图绘制
2. 完成PCB绘制

## 符号库的导入
在Kicad中选择`符号编辑器`，在工具栏中选择`文件-添加库`，在`添加到库表`中选择`工程`点击确定，然后再选择`symbols.kicad_sym`文件即可完成导入。

## 关于封装
在绘制完原理图之后，需要把每个符号都关联一个封装，具体关联的封装表在`footprints.csv`中给出，**一定要关联封装否则不能画PCB**。

**注意：** 关于References一列，只对应`STM32_MinimumSystem.pdf`中的位号，由于位号可以修改，所以请同学们**仔细查看**并关联封装.


## 关于报错和警告
正确绘制原理图和PCB是不会产生报错的，警告可以直接忽略。