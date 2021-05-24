# 三、Editor(编辑器)
## 1. General
### Auto Import
- Java
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210518233737912.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
  1.选择是否要让IDE显示“类”和/或“静态”方法和字段的弹出窗口。默认情况下，两个选项都被选中。
  2.在粘贴上插入导入
  Always：将自动为粘贴的代码块中找到的所有缺少的类，方法和字段添加import语句。
  询问：将提示您选择要导入的类，方法和字段。
  从不：不会添加任何导入语句 。
  3 如果只有一个导入源，此选项将启用自动插入导入语句。
  4 如果启用此选项，则在编辑器中工作时，IntelliJ IDEA会删除未使用的导入，添加丢失的导入，并以无提示的方式组织导入语句。

###  2.Appearance
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051823460496.png)
**1.选中此复选框可使插入符号以指定的周期（以毫秒为单位）闪烁。**
2.
**3. 选中此复选框可在编辑器的右边缘显示一条细的垂直线。**
**4. 选中此复选框可在编辑器左边显示行号。**
**5. 选中此复选框可在类中各方法上下显示细线，以将方法彼此分开并将方法与字段声明分开。**
**6. 选择此复选框可使IntelliJ IDEA显示空格**
- 前导：选中此复选框可在代码行之前添加空格。
- 内部：选中此复选框可在代码行内显示空格。
- 尾随：选中此复选框可在代码行后显示空格。

**7.选中此复选框可在方法中显示一条竖线**
开启前效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210518235609525.png)
开启后效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210518235627180.png)
**8. 每当IntelliJ IDEA检测到可以修改或改进您的代码时，编辑器中的当前行上都会出现一个灯泡图标：意向动作图标用于快速操作和快速修复,类似于代码自动提示**
**9. 选择此复选框以启用镜头模式。效果如下**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210519000101508.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
**10. 渲染Javadocs﻿ 渲染的注释更易于阅读，并且不会在代码中添加多余的标签。**
**11. 选中此复选框可显示以不同颜色突出显示的标签的层次结构。如果启用此选项，则可以定义以下选项**：
- 要突出显示的级别：指定要突出显示的层次结构的深度。
-  不透明度：指定突出显示的亮度

**12.如果选中此复选框，则颜色值的背景将显示颜色预览：**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210519001052267.png)

###  3.Breadcrumbs(面包屑)
选中此复选框后，将在编辑器中显示从当前文档的根元素到插入符号的代码元素的路径：![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051900230530.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051900235490.png)




### 4.Code Completion
###  5.Code Folding(代码折叠)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524222233619.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

###  6.Console(控制台)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524222555427.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
- Use soft wraps in console:如果选中此复选框，则在控制台中使用自动换行（或自动换行）。
- Console commands history size:指定将在控制台历史记录中包含多少个控制台命令
- Override console cycle buffer size:在控制台缓冲区大小超过指定值时删除旧消息
- default Encoding:默认字符编码
- fold console lines that contain:
-



###  7.Editor Tabs
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524223830519.png)

###  8.Gutter Icons(栅格图标)
图标位于左侧的编辑器中。它们调用一些基本操作以及其他特定于框架和技术的功能。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524224347163.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
要显示或隐藏装订线中的图标，请选中或清除其旁边的复选框。如果要禁用所有图标，请清除可用图标列表上方的显示装图标复选框。



###  9. Postfix Completion(后缀完成)
使您可以在刚刚键入的表达式周围添加模板代码。当您在一个点后键入其缩写词（后缀）并按扩展键（Tab默认情况下），或者在代码完成弹出窗口中选择缩写词时，模板将展开。例如，.if应用于表达式的后缀将其用if语句包装起来。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524230101797.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
### 10. Smart Keys(智能键)
- HTML/CSS
- JSON
- YAML
- JavaScript
- SQL

## 2. Code Editing(代码编辑)
- Highlight on Caret Movement
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524231601381.png)
- Refactorings(重构)

- Error Highlighting(错误突出显示)

- Quick Documentation(快速文档)
- Editor Tooltips(编辑器工具提示)
  可以指定工具提示出现的延迟。
## 3. Font(字体)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210524232045846.png)

## 4. Color Scheme(配色方案)

## 5. Code Style(代码风格)

## 6. Inspections

## 7. File and Code Templates
## 8. File Encodings
## 9. Live Templates
## 10. File Types
## 11. Android Layout Editor
## 12. Copyright
## 13. Inlay Hints
## 14. Duplicates
## 15. Emmet
## 16. GUI Designer
## 17. Intentions
## 18. Language Injections
## 19. Proofreading
## 20. Reader Mode
## 21. TextMate Bundles
## 22. TODO