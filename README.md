# plot_tif_lotmean

## 文件01: 01_cul_tif_latmean.ipynb
用于数据预处理，计算tif数据的纬度均值并存为xlsx文件。
1. 计算每个像素的纬度。
2. 计算tif数据在这些纬度均值和方差。
3. 将DataFrame导出为Excel文件。

## 文件02: 02_plot_by_latmean.ipynb
展示不同变量在不同纬度上的分布情况，每个变量以0为分界线存在两种颜色。
1. 从Excel文件加载三个变量文件，分别为file_var1, file_var2, file_var3。
2. 提取每个变量的纬度和均值数据。
3. 创建散点图，显示三个变量的纬度和均值关系。
   - 对于var1和var2，使用下x轴来显示数据点。
   - var3使用顶部的x轴。

## 示例
![GitHub Logo](/example.png)
