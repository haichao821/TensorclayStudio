# TensorClay 专注土的本构理论研究的单元试验计算软件

Tensorclay是一款简单的用于研究土的本构理论的单元试验计算软件，可以模拟排水和不排水三轴试验。主要特点为可以同步对比土的三轴压缩试验结果和模型计算结果。

目前，我们开放共享Tensorclay的执行文件，后期将逐步补充经典的土的本构模型，实现更多的单元试验类型和不同加载条件，如温度和基质吸力控制等。

Tensorclay仍处于快速迭代开发过程，程序界面和功能可能在不同版本之间会存在差异，欢迎提出宝贵建议。

版权所有：lihaichao，中国民航大学交通科学与工程学院


# TensorClay 版本更新说明

## Tensorclay-R2026V05S01版本更新

```
.
├── CHECKSUM_v1.1.0.txt
├── Tensorclay Matrix Report.pdf
├── Tensorclay-cli-mac
├── Tensorclay-cli.exe
├── 土三轴压缩试验结果案例
│   ├── C5_G01.sdb
│   ├── C5_G02.sdb
│   └── C5_G03.sdb
└── 土三轴压缩试验结果案例.json
```

在当前版本中我们提供Tensorclay在Windows和MacOS系统的执行文件，需要在终端中打开，建议将终端设置为浅色主题以达到最佳的视觉效果。

该版本包含的文档如上所示，由执行文件、三轴试验数据集和项目文件组成。其中项目文件中的DATA路径需要根据个人情况进行调整。

如果在使用过程中出现什么问题，欢迎在我们的交流群中进行讨论。


## Tensorclay-R2026V05S02版本更新 - 2026年5月25日

### Tensorclay-R2026V05S02版本文件列表如下
```
.
├── C5_G01.sdb
├── C5_G02.sdb
├── C5_G03.sdb
├── CHECKSUM_v1.1.0.txt
├── Tensorclay-mac-R2026V05S02
├── Tensorclay-R2026V05S02.exe
├── TensorClay本构模型参数配置界面.png
├── TensorClay典型案例-Gnuplot绘图模式.json
├── TensorClay专业绘图模式配置界面.png
├── workspace_plot_260525_001_render.pdf
├── workspace_plot_260525_001_render.plt
├── workspace_plot_260525_002_render.pdf
├── workspace_plot_260525_002_render.plt
├── workspace_plot_260525_003_render.pdf
├── workspace_plot_260525_003_render.plt
├── workspace_plot_260525_004_render.pdf
└── workspace_plot_260525_004_render.plt

1 directory, 17 files
```

### Tensorclay-R2026V05S02版本重要改进

- 正式实现专业绘图能力，点击 TensorClay 工作区左侧的功能按钮，可以切换到画图模式，简单配置既可以创建多个子图的 plt 脚本，点击最下面的Gnuplot按钮将生成pdf文件。💡需要安装 Gnuplot 数据处理软件，可在其官网自行下载；
- 修改了 TensorClay 界面布局并调整了部分配色；
- 调整了三轴试验结果导入模式，提供TensorClay典型案例-Gnuplot绘图模式.json文件作为典型案例；

### Tensorclay-R2026V05S02版本简要说明

TensorClay 的目标始终是打通本构模型二次开发、多应力路径加载、试验数据导入、参数自动反演、专业作图等环节，成为开放共享的岩土本构理论张量计算工具。希望这个版本能让大家喜欢。

