# 美化windows11指南(劳资没写完)

### This is the Chinese guide,**[go to English](https://github.com/I-am-XCY/Beautify-your-Windows11/blob/main/README.md)**

## 声明
1. 我并不是什么电脑专家，教程以个人角度来讲，电脑出事了的话别找我。
2. 资源应用**非本人开发**，如果因好奇导致你的电脑归西，自己兜着。
3. 本文章写的美化方法作者本人成功，如果因操作不当导致你的电脑归西，自己兜着。

## 准备工作

### 确认你的电脑配置
首先，按下win+I来打开你的设置，接着搜索“Windows 规格”，**建议直接复制此处来搜索**，查看你的windows版本确保是windows11(如果是windows10、7或8，我并不能确保你的电脑会不会出现一些问题，如果你执意要试试的话)，还有最重要的：**确保你的电脑能带得动美化程序,还有足够的磁盘存储空间和内存，运行状态良好**

### 带上你的加速器
**如果您已经有加速github的加速器了，或者你可以随时流畅的进出github，跳过这段话(算我操心了)**

首先，去[链接下载watt toolkit](https://steampp.net/)安装包(建议使用蓝奏云网盘渠道),双击运行安装包安装watt toolkit，安装之后打开软件，在左侧侧边栏找到网络加速，打开网络加速页面后在列表里把github左边的方框给勾选上，点击启用加速。

## 思考自己需要什么

### 你要改哪些东西
-  任务栏毛玻璃
-  文件资源管理器毛玻璃
-  设置的毛玻璃
-  鼠标指针
-  开始菜单毛玻璃
-  开始菜单与图标大小
-  通知中心毛玻璃
...

### 你要加哪些东西
- 桌面dock
- 任务栏dock动画
- 壁纸(此处教的是高级壁纸，**会吞你20元**)
- 桌面小组件
...

---

## 美化前置

### 下载windhawk
**本前置帮助实现的项目：**
- 任务栏毛玻璃
- 文件资源管理器毛玻璃
- 设置的毛玻璃
- 任务栏dock动画
- 开始菜单毛玻璃
- 开始菜单与图标大小
- 通知中心毛玻璃

首先，去[链接下载windhawk安装包](https://windhawk.net/)，在官网点击“downdoads”或“下载”下载windhawk安装包，双击运行安装包安装windhawk,选择你的语言根据提示进行下载。**注意: windhawk里面的插件和下载软件是依靠github来获取的所以可能要挂加速器，加速器详见准备工作**

### 下载winstep nexus
**本前置帮助实现的项目：**
- 桌面dock

首先，去[链接下载winstep nexus安装包](https://apsgocn.lanzout.com/iNekQ49hcofc)，点击“下载”下载安装包压缩文件，解压安装包压缩文件，根据提示进行下载。

### 下载wallpaper engine
**本前置帮助实现的项目：**
- 壁纸

如果你不会使用Steam,请看[此视频](https://www.bilibili.com/video/BV1giQJYrEK6/?)。然后花点小钱在商店买一个“下载wallpaper engine”，就可以使用壁纸了。**注意:本文章说明的加速器也可以加速Steam，加速器详见准备工作**

---

## **开始你的美化**
## 目录
1. 任务栏毛玻璃
2. 开始菜单与图标大小
3. 文件资源管理器毛玻璃
4. 设置的毛玻璃
5. 鼠标指针更改
6. 开始菜单毛玻璃
7. 桌面dock
8. 任务栏dock动画
9. 壁纸
10. 桌面小组件
11. 通知中心毛玻璃(与1.建议一起使用)

---
## 1. 任务栏毛玻璃

打开你刚刚下载的windhawk,**如果你的软件不说中文，点击右上角的小齿轮打开设置,在设置页面的第一个设置来设置语言**。
然后，在搜索框里搜索“**Windows 11 Taskbar Styler**”，作者是m417z。
点击“详情”打开此插件的详情页面，点击安装>接受风险并安装
安装完毕后，在此插件的详情页面找到**高级设置**按钮并打开
在高级设置页面里找到Mod设置，复制并粘贴此代码(三击选中整行)
~~~json
{"controlStyles[0].target":"Taskbar.TaskbarFrame#TaskbarFrame","controlStyles[0].styles[1]":"HorizontalAlignment=Auto","controlStyles[0].styles[2]":"Width=Auto","controlStyles[0].styles[0]":"MaxWidth:=1920","controlStyles[0].styles[3]":"MinWidth:=1920","controlStyles[1].target":"Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid","controlStyles[1].styles[0]":"Margin=12,0,12,5","controlStyles[1].styles[1]":"BorderThickness=$BorderThickness","controlStyles[1].styles[2]":"BorderBrush:=$BorderBrush","controlStyles[1].styles[3]":"CornerRadius=$CornerRadius","controlStyles[1].styles[4]":"Background:=Transparent","controlStyles[2].target":"Rectangle#BackgroundFill","controlStyles[2].styles[0]":"Visibility=Visible","controlStyles[2].styles[1]":"Fill:=$Background","controlStyles[3].target":"Rectangle#BackgroundStroke","controlStyles[3].styles[0]":"Visibility=Collapsed","controlStyles[4].target":"Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[4].styles[0]":"Margin=4","controlStyles[4].styles[1]":"Background:=$ElementBG","controlStyles[4].styles[2]":"CornerRadius=12","controlStyles[5].target":"Grid#SystemTrayFrameGrid","controlStyles[5].styles[0]":"Margin=0,7,-250,7","controlStyles[5].styles[1]":"RenderTransform:=<TranslateTransform X=\"-645\" Y=\"-2\"/>","controlStyles[5].styles[2]":"Padding=10","controlStyles[5].styles[3]":"Background:=$ElementBG","controlStyles[5].styles[4]":"CornerRadius=12","controlStyles[6].target":"SystemTray.ChevronIconView","controlStyles[6].styles[0]":"Padding=$TrayPadding","controlStyles[6].styles[1]":"CornerRadius=10","controlStyles[7].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[7].styles[0]":"Padding=$TrayPadding","controlStyles[7].styles[1]":"CornerRadius=10","controlStyles[8].target":"SystemTray.OmniButton","controlStyles[8].styles[0]":"Padding=$TrayPadding","controlStyles[8].styles[1]":"CornerRadius=10","controlStyles[9].target":"SystemTray.CopilotIcon","controlStyles[9].styles[0]":"Padding=$TrayPadding","controlStyles[10].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid","controlStyles[10].styles[0]":"Padding=$TrayPadding","controlStyles[11].target":"SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid","controlStyles[11].styles[0]":"Padding=0","controlStyles[11].styles[1]":"CornerRadius=10","controlStyles[12].target":"SystemTray.StackListView#IconStack > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon","controlStyles[12].styles[0]":"Padding=0","controlStyles[13].target":"SystemTray.Stack#ShowDesktopStack","controlStyles[13].styles[0]":"Visibility=Visible","controlStyles[14].target":"Taskbar.Gripper#GripperControl","controlStyles[14].styles[0]":"Width=Auto","controlStyles[14].styles[1]":"MinWidth=24","controlStyles[15].target":"Windows.UI.Xaml.Controls.Grid#AugmentedEntryPointContentGrid","controlStyles[15].styles[0]":"Margin=4,0,0,0","controlStyles[15].styles[1]":"HorizontalAlignment=Left","controlStyles[16].target":"TextBlock#TimeInnerTextBlock","controlStyles[16].styles[0]":"FontSize=13","controlStyles[16].styles[1]":"FontFamily=vivo Sans EN VF","controlStyles[16].styles[2]":"Margin=0","controlStyles[16].styles[3]":"Padding=0","controlStyles[16].styles[4]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[17].target":"TextBlock#DateInnerTextBlock","controlStyles[17].styles[0]":"Visibility=Collapsed","controlStyles[17].styles[1]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"-9\" />","controlStyles[17].styles[2]":"FontSize=11","controlStyles[17].styles[3]":"FontFamily=vivo Sans EN VF","controlStyles[18].target":"TextBlock#InnerTextBlock[Text=]","controlStyles[18].styles[0]":"Text=","controlStyles[19].target":"Windows.UI.Xaml.Controls.Grid#ConfirmatorMainGrid","controlStyles[19].styles[0]":"CornerRadius=22","controlStyles[19].styles[1]":"BorderThickness=$BorderThickness","controlStyles[19].styles[2]":"BorderBrush:=$BorderBrush","controlStyles[19].styles[3]":"Background:=$Background","controlStyles[20].target":"TextBlock#SearchBoxTextBlock","controlStyles[20].styles[0]":"Text=Search This Precision","controlStyles[20].styles[1]":"FontSize=10","controlStyles[20].styles[2]":"FontFamily=vivo Sans EN VF","controlStyles[21].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent","controlStyles[21].styles[0]":"Visibility=Visible","controlStyles[22].target":"Windows.UI.Xaml.Controls.Button","controlStyles[22].styles[0]":"BorderThickness=$BorderThickness","controlStyles[23].target":"Windows.UI.Xaml.Controls.Border#OverflowFlyoutBackgroundBorder","controlStyles[23].styles[0]":"BorderThickness=$BorderThickness","controlStyles[23].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[23].styles[2]":"Background:=$Background","controlStyles[23].styles[3]":"CornerRadius=$CornerRadius","controlStyles[24].target":"Windows.UI.Xaml.Controls.Grid#ModalRootGrid > Windows.UI.Xaml.Controls.Border#BackgroundElement","controlStyles[24].styles[0]":"BorderThickness=$BorderThickness","controlStyles[24].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[24].styles[2]":"Background:=$Background","controlStyles[24].styles[3]":"CornerRadius=20","controlStyles[25].target":"WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement#VirtualDesktopBar","controlStyles[25].styles[0]":"Width=1000","controlStyles[25].styles[1]":"Visibility=Collapsed","controlStyles[25].styles[2]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"60\" />","controlStyles[25].styles[3]":"CornerRadius=$CornerRadius","controlStyles[26].target":"Windows.UI.Xaml.Controls.Border#BackgroundDimmingLayer","controlStyles[26].styles[0]":"Background:=$Background","controlStyles[27].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Windows.UI.Xaml.Controls.Border#BackgroundElement","controlStyles[27].styles[0]":"CornerRadius=10","controlStyles[28].target":"Taskbar.TaskListButton#TaskListButton","controlStyles[28].styles[0]":"CornerRadius=10","controlStyles[29].target":"Windows.UI.Xaml.Controls.Border#SnapBarBorder","controlStyles[29].styles[0]":"Background:=$Background","controlStyles[29].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[29].styles[2]":"CornerRadius=$CornerRadius","controlStyles[29].styles[3]":"BorderThickness=$BorderThickness","controlStyles[29].styles[4]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"10\" />","controlStyles[29].styles[5]":"Margin=0,0,0,-10","controlStyles[30].target":"Windows.UI.Xaml.Controls.Border#SnapPickerBorder","controlStyles[30].styles[0]":"Background:=$Background","controlStyles[30].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[30].styles[2]":"CornerRadius=$CornerRadius","controlStyles[30].styles[3]":"BorderThickness=$BorderThickness","controlStyles[31].target":"Windows.UI.Xaml.Controls.Border#SearchPillBackgroundElement","controlStyles[31].styles[0]":"BorderBrush:=$ElementBorderBrush","controlStyles[31].styles[1]":"CornerRadius=$ElementCornerRadius","controlStyles[31].styles[2]":"BorderThickness=$ElementBorderThickness","controlStyles[31].styles[3]":"Margin=0","controlStyles[32].target":"Taskbar.TaskbarExtensionElement","controlStyles[32].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[33].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[33].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[34].target":"Windows.UI.Xaml.Controls.ToolTip > Windows.UI.Xaml.Controls.ContentPresenter#LayoutRoot","controlStyles[34].styles[0]":"Background:=$Background","controlStyles[34].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[34].styles[2]":"BorderThickness:=$BorderThickness","controlStyles[34].styles[3]":"CornerRadius=12","controlStyles[35].target":"SearchUx.SearchUI.SearchButtonControl","controlStyles[35].styles[0]":"Width=130","controlStyles[35].styles[1]":"Margin=-1,7,-1,7","controlStyles[36].target":"WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement > Windows.UI.Xaml.Controls.Grid#GridElement > Windows.UI.Xaml.Controls.Border#VirtualDesktopSwitcherBackground","controlStyles[36].styles[0]":"Background:=$Background","controlStyles[36].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[36].styles[2]":"BorderThickness=$BorderThickness","controlStyles[36].styles[3]":"CornerRadius=$CornerRadius","styleConstants[0]":"Background=<WindhawkBlur BlurAmount=\"15\" TintColor=\"{ThemeResource GlassTint}\"/>","styleConstants[1]":"BorderBrush2=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"0.0\" /><GradientStop Color=\"{ThemeResource SystemChromeLowColor}\" Offset=\"0.25\" /><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"1\" /></LinearGradientBrush>","styleConstants[2]":"BorderThickness=0.3,1,0.3,0.3","styleConstants[3]":"CornerRadius=15","styleConstants[4]":"BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>","styleConstants[5]":"Background2=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.3\" FallbackColor=\"{ThemeResource SystemChromeAltHighColor}\" />","styleConstants[6]":"TrayPadding=2","styleConstants[7]":"ElementBG=<SolidColorBrush Color=\"{ThemeResource ElementTint}\" Opacity=\"0.3\" />","styleConstants[8]":"ElementBorderThickness=0.3,0.3,0.3,1","styleConstants[9]":"ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>","styleConstants[10]":"ElementCornerRadius=12","resourceVariables[0].variableKey":"GlassTint@Dark","resourceVariables[0].value":"#10808080","resourceVariables[1].variableKey":"GlassTint@Light","resourceVariables[1].value":"#4D000000","resourceVariables[2].variableKey":"ElementTint@Dark","resourceVariables[2].value":"{ThemeResource SystemChromeAltHighColor}","resourceVariables[3].variableKey":"ElementTint@Light","resourceVariables[3].value":"#000000","controlStyles[4].styles[3]":"HorizontalAlignment=Left","controlStyles[5].styles[5]":"VerticalAlignment=Left"}
~~~
若你觉得长短不合适或需要调整时，将此代码发送给AI(费用自理)
对AI说：
~~~
这是windhawk win11 taskbar styler 的高级设置液态玻璃效果代码，我需要(你的要求)，不丢失液态玻璃效果：
(代码)
~~~
如果不满意就继续改，或把任务栏长度直接拉到最宽

## 2.开始菜单与图标大小

打开你刚刚下载的windhawk,**如果你的软件不说中文，点击右上角的小齿轮打开设置,在设置页面的第一个设置来设置语言**。
然后，在搜索框里搜索“**Taskbar height and icon size**”，作者是m417z。
点击“详情”打开此插件的详情页面，点击安装>接受风险并安装
安装完毕后，在此插件的详情页面找到**设置**按钮并打开设置页面
各选项翻译为：
Taskbar height  **任务栏高度**
The height, in pixels, of the taskbar (Windows 11 default: 48)
**任务栏的高度（以像素为单位）（Windows 11 默认：48）**

Icon size  **图标大小**
The size, in pixels, of icons on the taskbar (Windows 11 default: 24)
**任务栏上图标的尺寸（以像素为单位）（Windows 11 默认值：24）**

Taskbar button width  **任务栏按钮宽度**
The width, in pixels, of the taskbar buttons (Windows 11 default: 44)
**任务栏按钮的宽度（以像素为单位）（Windows 11 默认值：44）**

Small icon size  **小图标尺寸**
The size, in pixels, of small icons on the taskbar (Windows 11 default: 16)
**任务栏上小图标的尺寸（以像素为单位）（Windows 11 默认值：16）**
Used in newer Windows 11 builds with support for small taskbar icons (around July 2025)
**用于较新的 Windows 11 版本，支持小任务栏图标（约 2025 年 7 月）。**

Small taskbar button width  **任务栏按钮宽度较小**
The width, in pixels, of the small taskbar buttons (Windows 11 default: 32)
**小任务栏按钮的宽度（以像素为单位）（Windows 11 默认：32）**
Used in newer Windows 11 builds with support for small taskbar icons (around July 2025)
**用于较新的 Windows 11 版本，支持小任务栏图标（约 2025 年 7 月）。**

在设置页面里调整你所需的的数值。

## 3. 文件资源管理器毛玻璃

打开你刚刚下载的windhawk,**如果你的软件不说中文，点击右上角的小齿轮打开设置,在设置页面的第一个设置来设置语言**。
然后，在搜索框里搜索“**Windows 11 File Explorer Styler**”，作者是m417z。
点击“详情”打开此插件的详情页面，点击安装>接受风险并安装
安装完毕后，在此插件的详情页面找到**设置**按钮并打开设置页面
在“Theme”下的选择栏选择“**Translucent Explorer11**”

## 4. 设置的毛玻璃

打开你刚刚下载的windhawk,**如果你的软件不说中文，点击右上角的小齿轮打开设置,在设置页面的第一个设置来设置语言**。
然后，在搜索框里搜索“**Windows 11 Settings Styler**”，作者是m417z。
点击“详情”打开此插件的详情页面，点击安装>接受风险并安装
安装完毕后，在此插件的详情页面找到**设置**按钮并打开设置页面
在“Theme”下的选择栏选择“**Translucent Settings11**”

## 5. 鼠标指针更改



## 6. 开始菜单毛玻璃



## 7. 桌面dock

打开下载的“winstep nexus”，此时在桌面上会出现一个dock栏，右键任意图标>Nexus>首选项，进行设置。

**猜你在问：任务栏怎么自动隐藏**
Win+I打开设置>搜索“**任务栏设置**”>任务栏行为>勾选自动隐藏任务栏

## 8. 任务栏dock动画



## 9. 壁纸



## 10. 桌面小组件



## 11. 通知中心毛玻璃


