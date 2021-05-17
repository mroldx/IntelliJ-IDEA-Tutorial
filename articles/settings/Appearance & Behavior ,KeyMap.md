# 一、Appearance & Behavior(外观与行为)
##  1. Appearance(外观)
### 1.设置IDEA主题与字体
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515190606434.png)
勾选Sync with OS 会同步系统更改

勾选Use custom font 选择代码字体,Size选择字号

### 2.Accessibility(无障碍)
辅助功能
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515192031907.png)
- Support screen readers:  为IntelliJ IDEA启用屏幕阅读器支持。
- User contrast scrollbars: 	使编辑器滚动条更加可见。
- Adjust color for red-green vision deficiecy: 调整UI颜色，以更好地感知色盲和弱视的颜色。**在这种情况下，代码片段（例如通常以红色突出显示的错误或通常为绿色的字符串）将改变颜色（红色将变为橙色，绿色将变为蓝色）。测试运行器中进度条的颜色也将进行调整，以便可以轻松识别。**
### 3. UI Options(界面设置)
用户界面选项
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515192642964.png)

#### 1.Show tree indent guides(显示树状缩进级别的垂直线)
在树状视图中（例如在“项目”工具窗口中）显示标记缩进级别的垂直线。这些行可以帮助您更好地了解项目中组件的层次结构。

**开启前效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515193332668.png)
**开启后效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515193245976.png)
#### 2. Smooth scrcolling(平滑移动)
作用: 开启后用鼠标中键在代码区上下滑动更流畅(个人感觉),这个因人而异
#### 3. Use smaller indents in trees(在树状菜单中使用更小的缩进)
在树状菜单中使用更小的缩进量

**开启前效果**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515195821984.png)

**开启后效果**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515195800561.png)

#### 4.Drag-n-Drop with Alt pressed only(仅按下Alt即可进行拖放)
避免意外移动文件，编辑器选项卡，工具窗口按钮和其他UI组件。启用后，按住该Alt键才可移动内容。
默认情况下，此选项是禁用的，您可以移动所有内容而无需任何额外的键。
#### 5. Enable mnemonics in menu(在菜单上启用快捷键)
按下划线执行菜单操作的热键
效果不明
#### 6. Merge main menu with window title(合并IDEA主菜单到window标题)
将IDEA主菜单合并到window栏,光文字的确不好进
开启前效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515204525981.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

开启后效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515204429844.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

#### 7. Enable mnemonics in controls(在控件中启用助记符)
带下划线的热键，您可以按这些热键来使用对话框中的控件
效果不明
#### 8. Always show full path in window header(始终在窗口标题中显示完整路径)
始终在窗口标题中显示完整路径
开启前效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515201017839.png)
开启后效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515201115721.png)
#### 9.  Display icons in menu items(在菜单项中显示图标)
在主菜单和上下文菜单中，在项目左侧显示图标。

#### 10 调整IDEA背景图片
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051520502041.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

### 4. Antialiasing(抗锯齿)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051521475031.png)

IDE:  	选择要应用于IDE的哪种抗锯齿模式（包括菜单，工具窗口等）
- Subpixel(子像素): 用于LCD显示器，并利用彩色LCD上的每个像素都由红色，绿色和蓝色子像素组成
- Greyscale(灰度): 建议此选项用于非LCD显示器或垂直放置的显示器。它在像素级别处理文本。
- No antialiasing(无抗锯齿):此选项可用于高分辨率的显示，其中非抗锯齿的字体渲染速度更快，并且外观可能更好。

Editor: 选择要应用于编辑器的抗锯齿模式：
- Subpixel(子像素): 用于LCD显示器，并利用彩色LCD上的每个像素都由红色，绿色和蓝色子像素组成
- Greyscale(灰度): 建议此选项用于非LCD显示器或垂直放置的显示器。它在像素级别处理文本。
- No antialiasing(无抗锯齿):此选项可用于高分辨率的显示，其中非抗锯齿的字体渲染速度更快，并且外观可能更好。

### 5. Tool Windows(工具栏设置)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515215552375.png)
#### 1.Show tool window bars(显示窗口工具栏)
在主窗口的边缘周围显示工具窗口栏
**开启前效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515220007664.png)

**开启后效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515220023763.png)

#### 2. Show tool window numbers(工具栏显示数字)
**开启前效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515220250930.png)

**开启后效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051522004670.png)
并且可以按Alt键加数字键快捷打开菜单
比如:git菜单  可以如图所示按 alt+9即可打开

#### 3. Side-by-side layout on the left(左侧并排布局)
被附连到顶部和底部边缘中的两列，而不是堆叠在彼此的顶部上显示垂直工具窗口。

比如同时打开三个工具窗口:Project,Faverites,编辑区

**开启前效果:**   
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515220944115.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
**开启后效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051522100929.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)


#### 4. Side-by-side layou on the right(右侧并排布局)
同上反过来
#### 5. Widescreen tool window layout(宽屏工具窗口布局)
通过限制水平工具窗口的宽度来最大化垂直工具窗口的高度。

**开启前效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515221527201.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)


**开启后效果:**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515221503391.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)


### 6. Presetation Mode(演示模式)
选择演示模式的字体大小。更改字体大小后，退出并进入演示模式。


##  2. Menus and Toolbars(菜单和工具栏管理)
自定义菜单和工具栏，使其仅包含所需的操作，对其进行重新组合并配置其图标。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515185050956.png)

- 在可用菜单和工具栏列表中，展开要自定义的节点，然后选择所需的项目。

-  单击+按钮以在所选项目下添加动作或分隔符。

- 单击-按钮以删除所选的项目。

- 单击编辑图标按钮以添加或更改所选操作的图标。您只能将PNG或SVG文件用作图标。

- 单击上移按钮或下移按钮向上或向下移动所选项目。

- 单击恢复按钮以将所选操作或所有操作恢复为默认设置。

## 3. System Settings(系统设置)

### 1. Passwords(密码管理)
主要是IntelliJ IDEA来为版本控制存储库，数据库和其他受保护的资源保存您的密码
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515173152351.png)
- In KeePass: 用来指定KeePass密码数据库文件c.kdbx的位置
  Protect master password using PGP Key:使用pgp来加密数据库的密码

- Do not save,forget passwords after restart: 不保存任何密码,重启后需要重新配置


### 2. HTTP Proxy(IDEA代理配置)
指定IntelliJ IDEA用于访问Internet的代理设置。HTTP代理适用于HTTP和HTTPS。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515180334762.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
- No proxy 无需代理
- Auto-detect proxy settings:自动检查代理配置
- 	Manual proxy configuration:手动指定代理设置。

### 3. Data Sharing(数据共享)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515172312493.png)
**选中这个发送使用情况统计信息复选框后,将会允许JetBrains收集你使用IntelliJ IDEA时最常使用的功能和操作的统计信息。**

### 4. Data Formats(设置  IDEA日期格式)
设置  IDEA日期格式
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021051518361310.png)
### 5. Updates(IDEA更新设置)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210515184037175.png)
Check IDE updates for
- stable releases:已发行的稳定版本
- early access program:  早期发行版本
Check for plugin updates: 检查插件更新

Show whats new  in the editor after an ide update:i当IDEA更新后,在编辑器中显示新功能

### 6. Android SDK
配置安卓sdk

## 4.File Colors(文件颜色)
使用此页面可以设置不同的背景颜色，以区分特定范围的项目文件。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516163656195.png)
### 1.Enable file color(启用文件颜色)
### 2.Use in editor tabs(在编辑器标签中使用)
### 3. Use in project view(在项目视图中使用)
例如，在“在文件中查找”对话框中Ctrl+Shift+F
开启前效果
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516163941318.png)
开启后效果:
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516164019272.png)
## 5. Scopes(IDEA操作作用域)
定义各种IntelliJ IDEA操作的范围，例如“查找用法”或“代码检查”。
## 6. Notifications(通知事项)
可以启用和禁用有关某些事件的通知,发生的事件的信息。更改其显示方式，并有选择地启用其日志记录。

## 7. Quick Lists(快捷菜单)
一组自定义的弹出。可以将其视为自定义菜单或工具栏，您可以为其指定快捷方式以进行快速访问。您可以根据需要创建任意数量的快速列表。快速列表中的每个动作均由0到9之间的数字标识。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516170035828.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
1.单击添加按钮或Alt+Insert按左窗格以创建新的快速列表。
2.将此快捷方式分配一个kyeMap ,在“设置/首选项”对话框中Ctrl+Alt+S，选择“键盘映射”。
3.在编辑器中，通过关联的快捷方式访问快速列表。
4.如果您不记得该快捷方式，则可以按其名称搜索快速列表。按Shift两次，然后输入快速列表的名称。
## 8. Path Variables(环境变量)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516170523533.png)


# 二、KeyMap(快捷键设置)
## 1.修改IDEA快捷键类型
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516170759461.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)
## 2.给指定菜单或操作设置快捷键
1.选中需要设置的菜单
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516171032241.png)
2. 右击出现设置菜单
   ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516171117263.png)
   依次为: 添加键盘,添加鼠标,添加缩写,取消快捷操作,重置
   选择添加键盘
   ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210516171307502.png)
   点击此文本框,按下你想要的快捷键点击确定即可

# 总结
[相关系列(idea2021.1使用教程)](https://blog.csdn.net/qq_41316955/category_11063150.html)
