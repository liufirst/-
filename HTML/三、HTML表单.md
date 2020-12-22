# 三、HTML的表单
## 3.1 表格
### 介绍
* table用于定义一个表格，类似于frame面板
* tr标签用于创建表格内的行，需要书写在table标签内
* td标签是单元格，需要书写在tr标签内
### 属性
![](https://pic.downk.cc/item/5fe0dc5c3ffa7d37b3ccfe1d.png)

  ![](https://pic.downk.cc/item/5fe0dd0c3ffa7d37b3cd6750.png)

  ## 3.2表头单元格标签th
  * 表头一般作用于第一行或者第一列，作用是文本加粗并居中
  * 只需要用标头标签```<th> </th>```替换td标签就可

  ## 3.4表格标题标签caption
  * 只能存在于table标签之内，并且需要紧随table标签
  ** 
```
<table>
    <caption>小说排行榜</caption>
</table>
  ```
## 3.5合并单元格
1.先确定是跨行还是跨列合并
* rowspan 跨行合并
* colspan 跨列合并  

2.根据先上后下 先左后右的原则找到目标单元格，写上合并方式和合并的单元格数量。如下： 
```<td colspan="3"></td>```
3.删除多余的单元格
