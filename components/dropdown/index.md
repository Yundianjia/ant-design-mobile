---
category: Components
chinese: 下拉菜单
type: 导航
english: Dropdown
---

## 如何使用
顶部下拉菜单


## API

#### static show(content: React.Element, options: Object):

`options`可选项：

- maskClosable (bool) - 点击蒙层是否允许关闭，默认允许
- transitionName (string) 自定义显示隐藏变换动画
- maskTransitionName (string) 自定义遮罩层变换动画

#### static hide(): 关闭 Dropdown

#### static newInstance():
有些情况下，页面需要多处出现 Dropdown ，或在 Dropdown 里再产生 Dropdown。

返回 Dropdown 实例对象。对象包括：

- show (function) - 同 static show
- hide (function) - 同 static hide