# weui css 代码梳理

> 目标，分析 weui 的结构，理解 weui 的设计

> 便于扩展、学习和理解 weui 的设计

## 目录结构
* style
	* base 基础
		* mixin 混合
		* variable 变量
	* icon 图标
	* widget 部件、组件
		* `weui-agree` 同意与否
		* `weui-animate` 动画
		* `weui-button` 按钮
		* `weui-cell` 列表视图
		* `weui-flex` flex 布局
		* `weui-footer` 底部
		* `weui-loading` 加载提示
		* `weui-media-box` 多媒体视图（图文组合、文字组合）
		* `weui-page` 文章、段落
		* `weui-panel` 布局容器
		* `weui-picker` 选择器
		* `weui-progress` 进度 
		* `weui-searchbar` 搜索栏
		* `weui-slider` 滑块
		* `weui-tab` 标签
		* `weui-tips` tip 提示
		
## 层级规范
* Popout

	> 弹出层，作为内容层和导航层的补充，用于承载弹窗通知、操作菜单、菜单、成功或加载中等状态的Toast，表单报错提示等弹出内容。
* Mask

	> 蒙层，配合Popout层使用，用于锁定内容层和导航层操作，不单独使用。
* Navigation

	> 导航层，位于内容层之上，在用户滑动内容层时可保持位置不动，通常用于承载导航栏等需要固定在页面的元素。
* Content

	> 内容层，承载页面主要内容。
		
## 字体规范	
......
	
## 命名规范

> 前缀、后缀 进行语义化组合使用

### 常用前缀
* `weui-icon-` 图标
* `weui-agree-` 同意（审批、复选框等意思）
* `weui-animate-` 动画
* `weui-btn-` 按钮
* `weui-switch` 开关

### 常用后缀
* `__hd` 头部 head
* `__bd` 身体、中间部分 body
* `__ft` 脚、底部 foot
* `__btn` 按钮，可触摸点击
* `__item` 项(flex 布局）
* `__title` 标题
* `__checkbox` 复选框
* `_disabled` 禁用
* `_plain` 线形、镂空
* `_primary` 常规、默认
* `_access` 可访问，可点击
* `_link` 超链接
### 结构化

## 邻老板对 weui 的扩展
### 按钮

### 字号

### 部件、组件
#### 图文组合

## 邻老板样式开发规范