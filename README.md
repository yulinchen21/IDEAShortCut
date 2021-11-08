# IDEAShortCut
IDEA shortcut for Mac


# IDEA 常用快捷键 For Mac

## Part 1 Editing shortcut

| 快捷键                   | 描述                                         |
| ------------------------ | -------------------------------------------- |
| Control + Space          | 基本的代码补全                               |
| Control + Shift + Space  | 智能代码补全（过滤方法列表和变量的预期类型） |
| Command + Shift + Enter  | 自动代码结束                                 |
| Command + P              | 显示方法的参数信息                           |
| Control + J              | 快速查看文档                                 |
| Shift + F1               | 查看外部文档                                 |
| Command + 光标处于代码上 | 查看代码简要信息                             |
| Command + F1             | 在错误或警告处显示具体描述信息               |
| Control + O              | 覆盖方法 重写父类的方法                      |
| Control + I              | 实现方法 实现接口中的方法                    |
| Command + /              | 注释/取消注释与行注释                        |
| Command + Option + I     | 注释/取消注释与块注释                        |
| Option + 方向键上        | 连续扩大选中代码块                           |
| Option + 方向键下        | 连续缩小选中代码块                           |
| Control + Shift + Q      | 显示上下文信息                               |
| Option + Enter           | 显示意向动作和快速修改代码                   |
| Command + Option + L     | 格式化代码                                   |
| Control + Option + O     | 优化 import                                  |
| Command + X              | 剪切当前行或者选定的块到剪切板               |
| Command + C              | 复制当前行或选定的块到剪切板                 |
| Command + V              | 从剪切板粘贴                                 |
| Command + Shift + V      | 从最近的缓冲区粘贴                           |
| Command + D              | 复制当前行或者选定的块                       |
| Command + Delete         | 删除当前光标所在行                           |
| Control + Shift + J      | 智能地将代码拼接成一行                       |
| Command +Enter           | 智能地拆分拼接的行                           |
| Command + 加号           | 展开代码块                                   |
| Command + 减号           | 折叠代码块                                   |
| Command + Shift + 加号   | 展开所有代码块                               |
| Command + Shift + 减号   | 折叠所有代码块                               |
| Command + W              | 关闭活动的编辑器选项卡                       |



## Part 2 Search / Replace

| 快捷键              | 描述                   |
| ------------------- | ---------------------- |
| Double Shift        | 查询任何东西           |
| Command + F         | 文件内查找             |
| Command + G         | 在查找模式下，向下查找 |
| Command + Shift + G | 查找模式下，向上查找   |
| Command + R         | 在当前文件内替换       |
| Command + Shift + F | 全局查找（根据路径）   |
| Command + Shift + R | 全局替换（根据路径）   |
| Command + Shift + S | 查询结构               |
| Command + Shift + M | 替换结构               |



## Part 3 Usage Search

| 快捷键                     | 描述                             |
| -------------------------- | -------------------------------- |
| Option + F7 / Command + F7 | 在文件中查找用法/ 在类中查找用法 |
| Command + Shift + F7       | 在文件中突出显示的用法           |
| Command + Option + F7      | 显示用法                         |



## Part 4 Compile and Run

| 快捷键                                    | 描述                       |
| ----------------------------------------- | -------------------------- |
| Command + F9                              | 编译 Project               |
| Command + Shift + F9                      | 编译选择的模块、包或者模块 |
| Control + Option + R                      | 弹出 Run 的可选菜单        |
| Control + Option + D                      | 弹出 Debug 的可选择菜单    |
| Control + R                               | 运行                       |
| Control + D                               | 调试                       |
| Control + Shift + R ，Control + Shift + D | 从编辑器运行上下文配置     |

## Part 5 Debugging

| 快捷键                 | 描述                                                         |
| ---------------------- | ------------------------------------------------------------ |
| F8                     | 进入下一步，如果当前行断点是一个方法，则不进入当前方法体内   |
| F7                     | 进入下一步，如果当前行断电是一个方法，则进入当前方法体内，如果该方法体还有方法则不会进入该内嵌方法中 |
| Shift + F7             | 智能跳入                                                     |
| Shift + F8             | 跳出                                                         |
| Option + F9            | 运行到光标处，如果光标前有其他断点会进入到该断点             |
| Option + F8            | 计算表达式，可以更改变量值使其生效                           |
| Command   + Option + R | 恢复程序运行，如果该断点下面代码还有断点则停在下一个断点上   |
| Command + F8           | 切换断点（若光标当前行有断点则取消断点，没有则加上断点）     |
| Command + Shift + F8   | 查看断点信息                                                 |

## Part 6 Navigation

| 快捷键                                  | 描述                                                         |
| --------------------------------------- | ------------------------------------------------------------ |
| Command + O                             | 查找类文件                                                   |
| Command + Shift + O                     | 前往指定的变量或者方法                                       |
| Control + 方向键左 / Control + 方向键右 | 左右切换打开的编辑页                                         |
| F12                                     | 返回到前一个工具窗口                                         |
| Esc                                     | 从工具窗口进入代码文件窗口                                   |
| Shift + Esc                             | 隐藏当前或者最后一个活动的窗口，且光标进入代码文件窗口       |
| Command + Shift + F4                    | 关闭活动 run/message/find/.../tab                            |
| Command + L                             | 在当前文件跳转到某一行的指定处                               |
| Command + E                             | 显示最近打开的文件记录列表                                   |
| Option + 方向键左/方向键右              | 光标跳转到当前单词/ 中文句的左/右侧开头位置                  |
| Command + Option + 方向键左/右          | 退回/前进到上一个操作的地方                                  |
| Command + Shift + Delete                | 跳转到最后一个编辑的地方                                     |
| Command + B 或者 Command + 鼠标点击     | 进入光标所在的方法/变量的接口或者是定义处                    |
| Command + Option + B                    | 跳转到实现处，在某个调用的方法上使用会跳到具体的实现处，可以跳过接口 |
| Option + Space，Command + Y             | 快速打开光标所在方法、类的定义                               |
| Control + Shift + B                     | 跳转到类型声明处                                             |
| Command + U                             | 前往当前光标所在的父类方法/接口定义                          |
| Control + 方向键下/ 方向键上            | 当前光标跳转到当前文件的前一个/后一个方法名位置              |
| `Command + ]` / `Command +[`            | 移动光标到当前所在代码的花括号的开始/结束位置                |
| Command + F12                           | 弹出当前文件结构层，可以在弹出的层上直接输入进行筛选（可以用户搜索类中的方法） |
| Control + H                             | 显示当前类的层次结构                                         |
| Command + Shift + H                     | 显示方法层次结构                                             |
| Control + Option + H                    | 显示调用层次结构                                             |
| F2 / Shift + F2                         | 跳转到下一个/ 上一个突出错误或者警告俄位置                   |
| F4/ Command + 方向键下                  | 编辑/ 查看代码源                                             |
| Option + Home                           | 显示到当前文件的导航条                                       |
| F3                                      | 选中文件/文件夹/代码行，添加/取消书签                        |
| Option + F3                             | 选中文件/ 文件夹/ 代码行，使用助记符添加/ 取消书签           |
| Control + Number                        | 定位到对应数值的书签位置                                     |
| Command + F3                            | 显示所有书签                                                 |

## Part 7 Refactoring

| 快捷键               | 描述                               |
| -------------------- | ---------------------------------- |
| F5                   | 复制文件到指定目录                 |
| F6                   | 移动文件到指定目录                 |
| Command + Delete     | 在文件上为安全删除文件，弹出确认框 |
| Shift + F6           | 重命名文件                         |
| Command + F6         | 更改签名                           |
| Command + Option + N | 一致性                             |
| Command + Option + M | 将选中代码提取为方法               |
| Command + Option + V | 提取变量                           |
| Command + Option + F | 提取字段                           |
| Command + Option + C | 提取常量                           |
| Command + Option + P | 提取参数                           |

## Part 8 VCS/ Local History

| 快捷键             | 描述                       |
| ------------------ | -------------------------- |
| Command + K        | 提交代码到版本控制器       |
| Command + T        | 从版本控制器更新代码       |
| Option + Shift + C | 查看最近的变更记录         |
| Control + C        | 快速弹出版本控制器操作面板 |

## Part 9 Live Templates

| 快捷键               | 描述                                           |
| -------------------- | ---------------------------------------------- |
| Command + Option + J | 弹出模版选择窗口，将选定的代码使用动态模版包住 |
| Command + J          | 插入自定义动态代码模版                         |

## Part 10 General

| 快捷键                | 描述                           |
| --------------------- | ------------------------------ |
| Command + Number      | 打开相应编号的工具窗口         |
| Command + S           | 保存所有                       |
| Command + Option + Y  | 同步、刷新                     |
| Control + Command + F | 切换全屏模式                   |
| Command + Shift + F12 | 切换最大化编辑器               |
| Option + Shift + F    | 添加到收藏夹                   |
| Option + Shift + I    | 检查当前文件与当前的配置文件   |
| Command + `,`         | 打开IDEA 系统设置              |
| Command + `；`        | 打开项目结构对话框             |
| Shift + Command + A   | 查找动作                       |
| Control + Shift + Tab | 编辑窗口标签和工具窗口之间切换 |
