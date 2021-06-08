# 三. Version Control


# 1、Background
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210607235910708.png)
- Background Operations(后台操作)

- Changed on server conflicts(在服务器更改冲突)

检查本地修改的文件或您检出的文件是否已被其他人修改，请选择检查每 x 分钟选项。

# 2、Changelists
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608000224876.png)

**1.分别跟踪文本文件中更改的块**

对一个文件的更改放入单独的更改列表以单独提交它们

**2:尝试从非活动更改列表编辑文件时显示对话框**

IntelliJ IDEA 会在尝试从非活动更改列表修改文件时显示“解决更改列表冲突”对话框。

**3:突出显示具有更改列表冲突的文件**

如果选择此选项，IntelliJ IDEA 会在非活动更改列表中的文件顶部显示黄色条纹，当此类文件已被修改时。
它让您可以选择一种可能的方式来解决冲突：将文件移动到活动更改列表;切换更改列表;忽略冲突。
属于非活动更改列表的文件的名称在编辑器选项卡和项目视图中以红色字体显示。

**4:突出显示非活动更改列表中的文件**

如果选中此复选框，则属于非活动更改列表的文件的名称在编辑器选项卡和项目视图中以浅蓝色字体显示。
# 3、Commit
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608231955697.png)
1.
2. 清除初始提交信息
3. 强制非空提交
4. 显示未版本控制的文件
5. 将未提交的更改移动到另一个更改列表

- Commit message inspections(提交消息检查)


- Before Commit
  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608232529999.png)
1. 代码提交前格式化
2. 重新排列代码
3. 优化代入语句
4. 分析代码
5. 检查TODO
6. 清理
7. 更新版权配置

# 4、Confirmation
**一. When files are created**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608232818289.png)

当创建文件时执行:
- Add silently: 新创建的文件会自动添加到版本控制中

**二. When files are deleted**

![在这里插入图片描述](https://img-blog.csdnimg.cn/202106082331338.png)

- **Show options before:**:从版本控制中删除,在打开的对话框中选择它后,本地删除的文件也会从 VCS 中删除。
- **Remove silently**:从 VCS 中删除本地删除的所有文件，无需确认。
- **Do not remove**:本地删除的文件仍受版本控制。

**三.When empty changelist becomes inactive**

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021060823360539.png)

- **Show options before removing**:在移除已失去活动状态的空更改列表之前要求确认。
- **Remove silently**:IntelliJ IDEA 会自动删除变为非活动状态的空更改列表，默认更改列表除外。
- **Do not remove**:在失去活动状态时不会删除空的更改列表。

**四. Display options dialog when these commands are invoked**
调用这些命令时显示选项对话框

**Show "clear read-only Status" Dialog**:选中此复选框可让 IntelliJ IDEA 在编辑器中打开文件并尝试修改它时明确要求取消只读状态。
**Restore workspace on branch switching**:如果您希望在切换到该分支时恢复您的工作区，即一组打开的文件、当前运行配置和与某个分支关联的断点,请勾选此选项
# 5、File Status Colors
文件在vcs控制中的各种颜色状态
# 6、Issue Navigation
issue导航
# 7、Shelf(暂时搁置代码以切换其他分支)
**Remove successfully applied files from the shelf**
- 清除此复选框以使 IntelliJ IDEA 仍会在Shelf选项卡中显示已取消搁置的更改，以便您可以在必要时再次应用它们。

- 选中此复选框后，更改在取消搁置后不会显示在搁架选项卡中。
  效果如下:
  ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608235431650.png)![在这里插入图片描述](https://img-blog.csdnimg.cn/20210608235439730.png)
  即使你再shelf再删除一次也会出现在recently deleted

**Shevle base revisions of files under distributed version control systems**:
- 选中此复选框可自动搁置 Git 或 Mercurial 版本控制下的文件的搁置

**Change Shelves Location**: 切换git搁置文件的存放位置

# 8、Git
# 9、GitHub
# 10、Mercurial
# 11、Perforce
# 12、Subversion



<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">
