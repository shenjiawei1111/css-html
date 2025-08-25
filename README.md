# CSS + HTML 学习日志

**日期**：[2025-08-25]

## 学习内容总结
今天主要学习了 CSS 和 HTML 的基础内容，通过编写实际代码来加深理解。以下是我今天的学习收获：

### CSS 布局学习

#### 1. 圣杯结构
学习了经典的圣杯布局（Holy Grail Layout），这是一种常见的三栏布局，左右两侧栏固定宽度，中间栏自适应宽度。实现圣杯布局主要借助 `float` 和 `margin` 属性，同时需要处理负边距和 `position: relative` 来调整元素位置。这种布局在早期的网页设计中非常流行，适合构建需要突出中间内容的页面结构。

#### 2. Flex 布局
深入学习了 CSS Flexbox（弹性盒布局模型）。Flex 布局提供了一种更加灵活的方式来排列、对齐和分配容器内的子元素空间。掌握了 `display: flex` 属性开启弹性容器，以及常用的属性如 `flex-direction`、`justify-content`、`align-items` 和 `flex-wrap` 等。Flex 布局可以轻松实现水平和垂直居中、自适应布局等，大大简化了布局代码。

#### 3. Grid 布局
接触了 CSS Grid（网格布局），这是一种二维布局系统，能够同时处理行和列。通过 `display: grid` 创建网格容器，使用 `grid-template-columns` 和 `grid-template-rows` 定义网格的列和行。Grid 布局可以实现复杂的网页布局，例如多列不等宽布局、嵌套网格等，并且可以使用 `grid-area` 和 `grid-template-areas` 来更直观地定义布局结构。

## 代码实践
今天使用 Flex 布局和 Grid 布局编写了一个响应式的卡片列表页面，同时尝试用圣杯结构实现了一个简单的页面框架。以下是部分代码片段：
