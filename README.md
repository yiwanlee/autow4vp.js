# Autow4vp.js

## 概述

Autow4vp.js （Auto Width For Viewport）是用于在移动端页面开发中精准还原UI设计图与移动端适配的解决方案。原理是通过设置viewport中的width为指定宽度（比如750px），然后与窗口宽度计算出缩放比例，并设置viewport中的scale的值。

使用最方便的地方在于你可以直接使用设计图的px来编写css。

它可能不是那么适用于先进前端，但是在我们快速移动端（微信之类的）开发上已经使用了很长时间。PS.我们其实都是一堆后端开发

## 如何使用

你只需要在head中引用 [Autow4vp.js](https://github.com/yiwanlee/autow4vp.git) 即可，它会自动执行。使用简单，即插即用。

[Autow4vp.js](https://github.com/yiwanlee/autow4vp.git) 默认定宽为750，如果你的设计图宽度为其他尺寸，你也可以在script元素上通过属性vww来设置指定的宽度。

```html
//默认定宽750
<script src="js/autow4vp.min.js"></script>

//通过script元素添加属性 vww 自定义viewport width的定宽
<script src="js/autow4vp.min.js" vww="750"></script>
```

### 属性

* #### vww 定宽

	建议是UI设计图的宽度

```html
//通过script元素添加属性 vww 设置
<script src="js/autow4vp.min.js" vww="750"></script>
```

### 贡献

如果你有好的意见或建议，欢迎给我们提issue或pull request。

### License
The MIT License(http://opensource.org/licenses/MIT)

请自由地享受和参与开源
