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
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210610225640986.png)

**1: 选择GIt的可执行路径,勾选复现框为仅为当前项目设置此路径;如果要为不同的项目使用不同的路径，并且不希望全局应用此设置，请选择此选项。**

**2:启用暂存区**:使用暂存区允许您轻松地单独提交对同一文件的更改（包括重叠更改），并查看哪些更改已经暂存

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210610230333346.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

**3:在挑选时自动提交**(挑选樱桃 ):当您挑选一个特定的文件提交时，将显示“**提交更改**”对话框。**如果选择了**在挑选时自动提交选项，则在单击挑选按钮时会静默提交选定的提交樱桃选择按钮，而**不会显示“提交更改”对话框**。

4:在选择提交推送到**受保护分支时**添加“cherry-picked from <hash>”后缀:默认不加

**5.如果即将提交 CRLF(换行) 行分隔符，则发出警告**

**6.在分离的 HEAD 中或在 rebase 期间提交时发出警告**

**7,	如果启用此选项**，IntelliJ IDEA **将检查是否存在尚未提取到本地存储库的待处理传入提交**，并将在分支弹出窗口中标记此类分支。
- 选择您希望 IntelliJ IDEA 如何查询远程以检查传入的提交：

- Auto：如果使用 HTTP 或 Git 协议访问远程，IntelliJ IDEA 将在后台检查更新。如果使用 SSH，则不会执行此检查，以免意外弹出外部身份验证应用程序。

- always：即使使用 SSH 访问远程，IntelliJ IDEA 也会在后台检查更新。

- never：IntelliJ IDEA 不会查询远程提交的传入提交，并且分支弹出窗口中将显示警告，允许您手动运行检查。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210610233650604.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMzE2OTU1,size_16,color_FFFFFF,t_70)

**1.更新方式**
- merge:相当于运行git fetch然后git merge, 或git pull --no-rebase。
- rebase:相当于运行git fetch然后git rebase, or git pull --rebase（所有本地提交都将放在更新的上游头之上）。

**2.	选择您希望在执行项目更新时如何处理未提交的更改：**
- Stash：本地更改将保存到git stash。如果您需要在 IntelliJ IDEA 之外应用带有隐藏更改的补丁，这将非常有用，因为它们是由 Git 本身生成的。

- 搁置：IntelliJ IDEA 会将本地更改放到搁置中。搁置由 IntelliJ IDEA 完成，搁置更改生成的补丁通常应用在 IntelliJ IDEA 中。

**3:如果当前分支的push被拒绝，则自动更新当前分支:**
- 如果您希望在push从当前分支到其跟踪分支的操作​​被拒绝时自动更新当前分支，请选中此复选框。

- 如果取消选择此选项，当推送分支被拒绝时，IntelliJ IDEA 将显示推送拒绝对话框，因为您的本地存储库和远程存储不同步。

- 请注意以下事项：

- 如果您之前从未见过Push Rejected对话框并且您最初启用了该复选框，IntelliJ IDEA 将通过merge操作静默更新冲突的本地分支。

- 如果您已经遇到Push Rejected对话框并选择了记住更新方法选择...选项，IntelliJ IDEA 会保存您的最后一个选择，rebase或者merge将应用它以静默方式更新冲突的本地分支。

- 因此，要更改“记住”设置，清除复选框，访问拒绝推送对话框，选择推送时自动更新...拒绝选项，然后调用另一个更新策略。

**4.为提交和推送显示推送对话框**:如果您希望在单击Commit Changes 对话框中的Commit和 Push后**显示Push 对话框**，请选择此选项。否则，您的更改将自动推送到受影响的存储库。

**5.仅在提交到受保护分支时显示推送对话框**:如果当您在“提交更改”对话框中单击“提交”和“推送”时，您**只希望在推送到受保护分支时显示“推送更改”对话框**，请选择此选项。否则，您的更改将**自动推送**到受影响的存储库。

**6.受保护的分支**:	如果您想禁用对某些分支强制推送更改的功能，请在此处列出它们

**7.使用凭证**:您将能够在Git 登录对话框中使用凭证帮助程序进行身份验证。

**8.按路径过滤更新项目信息**:如果你不想要得到的所有更改项目信息更新信息标签，当你执行更新，您可以通过过滤特定的路径列表。
# 9、GitHub
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210615225550226.png)
此页面指定您的 GitHub 远程存储帐户，如果您还没有，请创建一个 GitHub 帐户。

您可以指定多个帐户并为每个项目设置默认帐户。因此，您不必在每次需要连接到 GitHub 时指定要使用的帐户.

**Clone git repositories using ssh**:	如果要通过安全 SSH 网络协议从 GitHub 传输数据，请选择此选项。
**Connection timeout**:指定等待建立连接的时间段。


# 10、Mercurial(版本控制)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210615225844408.png)
使用此页面指定要应用于 Mercurial 版本控制下的项目目录的版本控制设置。


# 11、Perforce
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210615230028537.png)
使用此页面指定要应用于 Perforce 控制下的项目目录的版本控制设置


# 12、Subversion
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210615230109517.png)
使用此页面指定要应用于受 Subversion 控制的项目目录的设置



<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">
