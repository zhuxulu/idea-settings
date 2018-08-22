# idea-settings
### Appearance & Behavior

#### Appearance

- theme: IntelliJ
- windows options: 勾选 show memory indicator, 显示内存
- windows options: 勾选 small label in editor tabs, 小标签栏
- System Settings: 取消勾选 Reopen last project on startup, 启动时不自动打开工程

### Keymap

- delete line 改为 Ctrl + D，删除行
- Duplicate line or Selection 改为 Ctrl + Y，重复行
- Main Menu - Code - Completion - Basic: 改为 Ctrl + 逗号，代码提示
- Main Menu - Navigate - File Structure: 改为 Ctrl + L，显示类变量和方法列表

### Editor

#### General

- Auto Import: 勾选 Add... 和 Optimize... 两个选项，自动优化导入包
- Appearance: 勾选 Show method separators, 显示方法分隔线
- Appearance: 勾选 Show whitespaces, 显示空格、tab

- Code Completion: Match case, 取消勾选, 自动补全不区分大小写
- Code Completion: Parameter Info, 三个都勾选，显示完成的参数提醒
- Editor Tabs: 取消勾选 Show tabs in one row, 多行显示tab

#### Font

- Font：Hack: https://sourcefoundry.org/hack/
- Font: Hack, 12, 1.2
- fallback font: 微软雅黑，备用字体，显示中文

#### Color Scheme

- save as ...tom
- General - Text - Default Text：Background #F2F2F2, 编辑区背景色

#### Code Style

- Java: Code Generation: 取消勾选 Line comment at first column, 单行注释的两个斜杠跟随在代码的头部

#### Inspections

- Serialization issues: 勾选 Serializable class without 'serialVersionUID', 在已经继承了 Serializable 接口的类名上，提示生成serialVersionUID

#### File encodings

- Global encoding: UTF-8
- Project encoding: UTF-8
- Default encoding for properties files: UTF-8
- 勾选 Transparent native-to-ascii conversion

### Build, Execution, Deployment

#### Compiler

- 勾选 Build project automatically（自动编译）
- 按 ctrl+alt+shift+/，选择Registry，勾选 compiler.automake.allow.when.app.running（自动编译）

### 常用快捷键

| 快捷键           | 介绍                                                         |
| ----- | ------------------------------------------------------------ |
| Ctrl + E         | 显示最近打开的文件记录列表                                   |
| Ctrl + N         | 根据输入的 **类名** 查找类文件                               |
| Ctrl + Q         | 光标所在的变量 / 类名 / 方法名等上面（也可以在提示补充的时候按），显示文档内容 |
| Ctrl + P         | 方法参数提示显示                                             |
| Ctrl + H         | 显示当前类的层次结构                                         |
| Alt + Enter      | IntelliJ IDEA 根据光标所在问题，提供快速修复选择，光标放在的位置不同提示的结果也不同 |
| Shift + 左键单击 | 在打开的文件名上按此快捷键，可以关闭当前打开文件             |
| Shift + 滚轮前后滚动 | 当前文件的横向滚动轴滚动 |
| Ctrl + Alt + L | 格式化代码，可以对当前文件和整个包目录使用 |
| Ctrl + Alt + O | 优化导入的类，可以对当前文件和整个包目录使用 |
| Ctrl + Alt + I | 光标所在行 或 选中部分进行自动代码缩进，有点类似格式化 |
| Ctrl + Alt + T | 对选中的代码弹出环绕选项弹出层 |
| Ctrl + Shift + U | 对选中的代码进行大 / 小写轮流转换 |
| Ctrl + Shift + Enter | 自动结束代码，行末自动添加分号 |
| Ctrl + Shift + 前方向键 | 光标放在方法名/行上，将方法/行移动到上一个方法/行前面 |
| Ctrl + Shift + 后方向键 | 光标放在方法名/行上，将方法/行移动到下一个方法/行前面 |

### 插件

| 名称                           | 介绍                                           |
| ------------------------------ | ---------------------------------------------- |
| Alibaba Java Coding Guidelines | 阿里巴巴出的代码规范检查插件                   |
| CodeGlance                     | 在编辑代码最右侧，显示一块代码小地图           |
| MybatisX                       | mybatis 框架辅助                               |
| Lombok Plugin                  | Lombok 功能辅助插件                            |
| .ignore                        | 各类版本控制忽略文件生成工具                   |
| HotSwapAgent                   | 热加载                                         |
| Statistic                      | 代码统计                                       |
| String Manipulation            | 字符串格式风格快捷转换：大小写、驼峰、连接串等 |
| RestfulTookit                  | 一套 RESTful 服务开发辅助工具集                |
| Grep Console                   | 控制台配色                                     |

