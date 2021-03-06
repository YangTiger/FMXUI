﻿FMXUI  (YangYxd)

【当前版本】
  2018.01.11.001

【主要更改】
 - -----------------------------------
 - 2018.01.11
 * 优化和ScrollView相关组件滚动时的问题
 * 修复 GridView 启用 DragOneWay （单向滚动）时的BUG 
 - -----------------------------------
 * 修复BUG
 - -----------------------------------
 - 2018.01.08
 - -----------------------------------
 * 修复BUG
 + 设计器增加Copy Background, Copy Drawable等功能菜单
 - -----------------------------------
 - 2017.12.29
 - -----------------------------------
 * 优化日历组件，增加水平划动效果
 - -----------------------------------
 - 2017.12.25
 - -----------------------------------
 * 修复Bug（感谢报告：闲花漫云）
 * 优化代码
 * 圣诞快乐！
 - -----------------------------------
 - 2017.12.22
 - -----------------------------------
 + 全面支持 SVG 图像。在Drawable和Background各项中，增加 SVGImage 属性。
 - -----------------------------------
 - 2017.12.12
 - -----------------------------------
 * 修复 TCalendarView BUG（感谢报告：益佳易）
 - -----------------------------------
 - 2017.12.08
 - -----------------------------------
 * 增加 TCalendarView 日历组件 
 - -----------------------------------
 - 2017.12.04
 - -----------------------------------
 + 增加 UI.Calendar 和 UI.Calendar.Data 单元，后续将增加日历控件
 - -----------------------------------
 - 2017.11.10
 - -----------------------------------
 * 修复ListView多列时，滚动后显示错乱的问题（感谢：好人一生平安路）
 - -----------------------------------
 - 2017.07.27
 - -----------------------------------
 + 增加 TVertScrollView, THorzScrollView 垂直和水平滚动视图组件，更平滑的滚动，支持非移动平台鼠标拖动滚动
 * 修复一些BUG
 - -----------------------------------
 - 2017.07.25
 - -----------------------------------
 * 修复已知BUg (感谢：好人一生平安路） 
 - -----------------------------------
 - 2017.07.14
 - -----------------------------------
 * 修复 10.2 东京版中 Release 模式编译器优化 out 参数导致的问题
 - -----------------------------------
 - 2017.07.13
 - -----------------------------------
 * 修复 ListView 已知BUG
 - -----------------------------------
 - 2017.07.05
 - -----------------------------------
 * TextView 等 HtmlText 属性优化，增加超链接支持，增加 OnLinkClick 超链接事件
 - -----------------------------------
 - 2017.07.04
 - -----------------------------------
 * TextView、ButtonView 等组件增加属性 HtmlText，允许通过html代码实现更加丰富的显示效果
 - -----------------------------------
 - 2017.07.02
 - -----------------------------------
 * 优化 ListView 下拉刷新和上拉加载更多的动画效果，更加平滑
 * 优化 ImageViewerEx 图像浏览组件手势操作
 - -----------------------------------
 - 2017.06.30
 - -----------------------------------
 * 优化 GridView
 + 增加 CameraViewer 组件 
 - -----------------------------------
 - 2017.06.29
 - -----------------------------------
 * 修复 GridView 在移动平台上的BUG，基本不卡了
 - -----------------------------------
 - 2017.06.28
 - -----------------------------------
 * 修复 GridView 在移动平台上的BUG
 * 修复 Dialog 在移动平台上不能显示消息内容的问题
 - -----------------------------------
 - 2017.06.27
 - -----------------------------------
 * 核心功能加强。所有组件的 Drawable, Background相关属性增加 Accessory 支持
 + 增加 TImageViewerEx 图像浏览组件
 - -----------------------------------
 - 2017.06.26
 - -----------------------------------
 * 优心核心代码，ListView 滚动优化
 - -----------------------------------
 - 2017.06.24
 - -----------------------------------
 + UI.GridView 单元： GridView 的 Options 属性增加 gvFixedFooter 选项，启用后在视图底部显示 Footer，显示的内容可在适配器中返回。
   同时增加 FooterStyle 属性，用于设置支持的 Footer 类型（无，求和，平均值，最大和最小）。 在DBGridView中，默认支持这几种样式。
 - -----------------------------------
 - 2017.06.22
 - -----------------------------------
 * 修复 UI.Grid 中的部分 Bug （设计器），修改固定列的数据管理
 - -----------------------------------
 - 2017.06.20
 - -----------------------------------
 + 增加 GridView, StringGridView, DBGridView 三大Grid组件，可用于显示表格和数据集（主要面向非移动平台）
   GridView 支持多行列头，列头合并，行号，筛选，复选，单选等等功能！
 * 其它单元更新，功能加强
 * UI.Dialog 的增加更多功能，可用于显示下拉列表
 - -----------------------------------
 - 2017.05.21
 - -----------------------------------
 * 全面优化ListViewEx，提升滚动平滑度，解决滚动时定位不正确，跳动等所有已知BUG，增加 DragScroll属性，让非移动平台也能支持划动滚动操作。
 * 其它已知BUG修复
 - -----------------------------------
 - 2017.05.15
 - -----------------------------------
 + 增加 TShareImageList 组件，利用它可以实现跨 Frame, Form 共用 ImageList
 * 优化 RelativeLayout 的Layout属性中相对定位组件选择功能，排除不能使用的组件
 + 增加 UI.SizeForm 单元
 - -----------------------------------
 - 2017.05.13
 - -----------------------------------
 + TTextSettings 增加 Opacity 属性，这样可以让组件只改变文字的透明度
 * ListView 优化，并将一些私有方法和属性公开，以便更加灵活的使用
 * 修改 10.1.2 版本的 FMX.Canvas.D2D.pas 补丁文件，之前的会影响文本框的光标
 + 增加 10.1.2 版本的 FMX.Forms.pas 补丁文件，解决Win平台下无边框窗体不能showHint的问题
 - -----------------------------------
 - 2017.05.10
 - -----------------------------------
 + 增加TImageView Demo
 + UI.ListView增加分组列表功能
 - -----------------------------------
 - 2017.05.08
 - -----------------------------------
 * ListViewEx 已知BUG修复
 - -----------------------------------
 - 2017.05.07 
 - -----------------------------------
 * 修复05.06版本改动引起的ListViewEx滚动问题。
 * 修复非移动平台ListViewEX有时候拖动滚动块滚动不到底部的问题
 * 增加TDrawableBrush组件，可用于存放图像数据，然后用代码在运行时作为图像源
 - -----------------------------------
 - 2017.05.06 
 - -----------------------------------
 + ListViewEx 增加多列支持
 + ListViewEx 增加 AddHeaderView, AddFooterView 方法，添加额外的View到列表头部或底部
 * 优化 ListViewEx 在移动平台滚动处理，修复旧版本有时下拉不了的情况
 - -----------------------------------
 - 2017.05.03
 - -----------------------------------
 * 修改绘制状态的优先级，Check状态调整为优先于Focus
 + 增加 D10.1.2 补丁文件 FMX.Canvas.D2D.pas
 * 修复Win平台部分电脑上组件左边会多出一条半透明线条的BUG，解决办法是添加补丁文件 FMX.Canvas.D2D.pas
 - -----------------------------------
 - 2017.04.22 
 - -----------------------------------
 + 增加Demo: 边栏菜单
 * UI.Dialog 增加左右边栏菜单功能 (感谢: L.L.Qing)
 * UI.Standard 中 TextView 及其派生组件增加 Hint, ShowHint 属性
 - -----------------------------------
 - 2017.04.16 
 - -----------------------------------
 + 增加Demo: Dialog自定义View的用法
 * 修复ListViewEx下拉刷新后回弹太多的BUG
 * 修复Frame关闭后，等待对话框完成时会产生的一个BUG
 * 修复网友'好人一生平安路'发现的BUG（感谢 好人一生平安路）
 * 修复Android 5.0 及以上版本有虚拟功能键时，底部被虚拟功能键遮住的问题
 - -----------------------------------
 - 2017.01.18 (可能是年前最后一个版本，祝大家春节愉快)
 - -----------------------------------
 * 优化 TRingView 组件并修复已知Bug
 + 增加 TMultiPathView , 可实现各种复杂的多重路径显示 (感谢 swish)
 - -----------------------------------
 - 2017.01.16
 - -----------------------------------
 * 修复 Delphi 10 Seattle 无效编译 Android 的问题
 - -----------------------------------
 - 2017.01.14
 - -----------------------------------
 + 增加 TRingView 组件（各种空心图形效果，感谢 swish）
 * 修改 TProgressView 组件为圆环时的绘制方式
 - -----------------------------------
 - 2017.01.11
 - -----------------------------------
 * 修改 TextView 的 Checked 有设置时，绘制 Drawable 时优先使用 Checked 状态
 * 解决 Android 中设置状态栏颜色（沉浸式）无效的问题(只兼容SDK版本大于21的安卓设备)
 - -----------------------------------
 - 2017.01.07
 - -----------------------------------
 + 增加一个分栏页面的 Demo
 * UI.Frame 改进，支持在子控件中显示隐藏Frame时指定动画效果
 * UI.Frame 修改 DoCreate 触发的时机为设置 Parent 之后，避免由于本身没有初始化完成导致的问题
 * UI.Base 修改 TViewBorderStyle，将之前的LineBottom效果改为LineEdit，去除LineSmapie，同时增加LineLeft,LineTop,LineRight,RectBitmap样式
 - -----------------------------------
 - 2017.01.06
 - -----------------------------------
 + 增加 TBadgeView 组件 (用于显示未读消息的提示小红点)
 - -----------------------------------
 - 2017.01.05
 - -----------------------------------
 + 增加 TImageView 组件
 * 修复 TGridsLayout 存在的已知Bug，增加 SpringBorder 属性
 - -----------------------------------
 - 2017.01.04
 - -----------------------------------
 * UI.Frame 已经bug修复（感谢：漠北）
 - -----------------------------------
 - 2016.12.29
 - -----------------------------------
 * UI.Frame 增加移入移出动画效果（感谢：漠北）
 * 整理Demo
 * 修复其它已知bug
 - -----------------------------------
 - 2016.12.28
 - -----------------------------------
 * 修复 Action 无效的问题
 * 修复 TGridsLayout 列高后设置不能保存的问题
 - -----------------------------------
 - 2016.12.26
 - -----------------------------------
 + 增加 TGridsLayout 格式布局组件
 - -----------------------------------
 - 2016.12.23
 - -----------------------------------
 * 核心优化：TViewBorder支持渐变、图像等
 * TProgressView 组件支持 Kind （水平、垂直、圆环，参考 ProgressViewDemo）
 + 增加 UI.Utils 单元
 - -----------------------------------
 - 2016.12.17 (重要更新)
 - -----------------------------------
 * 修复 ListView 滚动时位置错乱和特别情况下引起闪退的问题
 - -----------------------------------
 - 2016.12.15
 - -----------------------------------
 * ListViewEx 增加下拉刷新和上拉加载更多的支持
 + UI.Frame 增加 DelayExecute 延时执行任务方法
 * UI.Frame ShowFrame 时，解决与 UI.Dialog 冲突的问题
 + 增加Demo ListView
 * 支持沉侵式状态栏。使用 UI.Frame 中 SetDefaultBackColor 设置默认背景色，SetDefaultStatusColor 设置状态条颜色
 * 优化 TextView 自动大小算法
 * EditView 解决 Android平台 MaxLength 无效问题
 * 其它已知BUG修复
 - -----------------------------------
 - 2016.12.11
 - -----------------------------------
 * 修复 ListViewEx 列表为空时的会出现的Bug
 * 优化核心代码
 - -----------------------------------
 - 2016.12.09
 - -----------------------------------
 * 优化核心代码，提升性能
 * 修复 TRelativeLayout 布局中相对定位的BUG
 - -----------------------------------
 - 2016.12.05
 - -----------------------------------
 * 优化核心代码，减少内存占用，提升性能
 * EditView 修复不能粘贴和设置键盘类型无效的bug
 + 增加 TProgressView 进度条组件
 - -----------------------------------
 - 2016.11.28
 - -----------------------------------
 * UI.ListView 修复部分已知bug.
 * UI.Dialog 修复列表对话框显示不正常的问题
 * UI.Base 修复按钮圆角边框显示不好看的问题
 - -----------------------------------
 - 2016.09.28
 - -----------------------------------
 * 原 UI.ListView 单元改名为 UI.ListviewEx ，功能保持不变
 + 增加新的 UI.ListView 单元， TListViewEx， 使用数据适配器的虚拟化列表组件
 + 增加 UI.Utils.ArrayEx 单元，一个扩展的 TArryEx 类，感谢武稀松
 * 其它优化
 - -----------------------------------
 - 2016.09.19
 - -----------------------------------
 + UI.Frame 增加切换动画支持，目前只实现了淡入淡出
 - -----------------------------------
 - 2016.09.18
 - -----------------------------------
 + 增加9宫格绘图设计器
 - -----------------------------------
 - 2016.09.16
 - -----------------------------------
 * Background 正式支持9宫格绘图
 + 增加 Dialog Demo
 - -----------------------------------
 - 2016.09.10
 - -----------------------------------
 + 增加 UI.Async 单元，方便的异步任务处理封装
 + 增加 UI.Dialog 单元，实现 AlertDialog, ProgressDialog 对话框类，支持各种常用的对话框
 + 增加 UI.ListView 单元，TListView 扩展实现，增加一些 Appearance，支持 Footer 点击事件
 + 增加 UI.Toast 系列单元，自动消失提示组件实现，Android 平台将调用原生 Toast
 + 增加 UI.Reg 单元，将各单元中需要注册的组件归类到此注册
 * 修复 UI.Base 单元中各个类的已知 Bug
 * 修复 UI.Standard 单元中所有已知 Bug
 * 优化 UI.Frame 单元
 - -----------------------------------
 - 2016.08.24
 - -----------------------------------
 + 增加 UI.Edit 单元，增加 TEditView 类
 * 将Demo工程移至单独文件夹下
 * 修复大量已知bug
 - -----------------------------------
 - 2016.08.22
 - -----------------------------------
 + 增加 UI.Frame 单元，增加 TFrameView 类，实现了多个 Frame 切换管理功能
 * 修复布局组件的已知BUG，布局更加灵活方便
 - -----------------------------------
 - 2016.08.19
 - -----------------------------------
 + 增加 TButtonView 
 + TTextView 增加 Drawable 属性，支持 TimageList
 * TTextView TextSetting 文字颜色
 * 其它修改
 