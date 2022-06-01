## 说明

- 一个 `vscode` 的 `css` 代码提示插件
- 支持的页面：`vue`、`html`

## 使用教程

#### 选择器

- 呼出关键字：`:link` 

  - 选择所有未被访问的链接

  - Snipped 代码

    ```javascript
    "body": [":link"]
    ```

- 呼出关键字：`:link` 

  - 选择所有已被访问的链接

  - Snipped 代码

    ```javascript
    "body": [":link"]
    ```

- 呼出关键字：`:hover` 

  - 选择鼠标指针位于其上的链接

  - Snipped 代码

    ```javascript
    "body": [":hover"]
    ```

- 呼出关键字：`:active` 

  - 选择活动链接（鼠标按下未弹起的链接）

  - Snipped 代码

    ```javascript
    "body": [":active"]
    ```

- 呼出关键字：`:focus` 

  - focus伪类选择器，光标(焦点)进去表单时,显示的效果，光标离开恢复默认。

  - Snipped 代码

    ```javascript
    "body": [":focus"]
    ```

- 呼出关键字：`[x]` 

  - 选择具有x属性的标签

  - Snipped 代码

    ```javascript
    "body": ["[x]"]
    ```

- 呼出关键字：`[x=\"x属性的属性值z\"]` 

  - 选择具有x属性且属性值等于z的标签

  - Snipped 代码

    ```javascript
    "body": ["[x=\"x属性的属性值z\"]"]
    ```

- 呼出关键字：`[x=\"x属性的属性值z\"]` 

  - 选择具有x属性且属性值等于z的标签

  - Snipped 代码

    ```javascript
    "body": ["[x=\"x属性的属性值z\"]"]
    ```

- 呼出关键字：`[x*=\"x属性的属性值z\"]` 

  - 选择具有x属性且属性值中含有z的元素

  - Snipped 代码

    ```javascript
    "body": ["[x*=\"x属性的属性值z\"]"]
    ```

- 呼出关键字：`:before` 

  - 在元素内部的前面插入内容，创建的伪元素属于行内元素。

  - Snipped 代码

    ```javascript
    "body": [":before {", "  content: \"内容\";", "}"]
    ```

- 呼出关键字：`:after` 

  - 在元素内部的后面插入内容，创建的伪元素属于行内元素。

  - Snipped 代码

    ```javascript
    "body": [":after {", "  content: \"内容\";", "}"]
    ```

- 呼出关键字：`:first-letter` 

  - 选择该元素内容的第一个字符

  - Snipped 代码

    ```javascript
    "body": [":first-letter"]
    ```

- 呼出关键字：`:first-line` 

  - 选择每个元素内容的首行

  - Snipped 代码

    ```javascript
    "body": [":first-line"]
    ```

- 呼出关键字：`:first-child` 

  - 匹配父元素中的第一个子元素

  - Snipped 代码

    ```javascript
    "body": [":first-child"]
    ```

- 呼出关键字：`:first-child` 

  - 匹配父元素中的第一个子元素

  - Snipped 代码

    ```javascript
    "body": [":first-child"]
    ```

- 呼出关键字：`:last-child` 

  - 匹配父元素中最后一个元素

  - Snipped 代码

    ```javascript
    "body": [":last-child"]
    ```

- 呼出关键字：`:nth-child(n)` 

  - 匹配父元素中的第n个元素

  - Snipped 代码

    ```javascript
    "body": [":nth-child(n)"]
    ```

- 呼出关键字：`:first-of-type` 

  - 指定元素的第一个

  - Snipped 代码

    ```javascript
    "body": [":first-of-type"]
    ```

- 呼出关键字：`:last-of-type` 

  - 指定元素的最后一个

  - Snipped 代码

    ```javascript
    "body": [":last-of-type"]
    ```

- 呼出关键字：`:nth-of-type(n)` 

  - 指定元素的第n个

  - Snipped 代码

    ```javascript
    "body": [":nth-of-type(n)"]
    ```

- 呼出关键字：`!important` 

  - 样式权重无穷大

  - Snipped 代码

    ```javascript
    "body": ["!important"]
    ```

#### 显示模式转换

- 呼出关键字：`display:block` 

  - 转换为块级元素

  - Snipped 代码

    ```javascript
    "body": ["display:block"]
    ```

- 呼出关键字：`display:inline;` 

  - 转换为行内元素

  - Snipped 代码

    ```javascript
    "body": ["display:inline;"]
    ```

- 呼出关键字：`display:inline-block;` 

  - 转换为行内块元素

  - Snipped 代码

    ```javascript
    "body": ["display:inline-block;"]
    ```

#### 宽度和高度

- 呼出关键字：`width` 

  - 定义宽度

  - Snipped 代码

    ```javascript
     "body": ["width: $1px;"]
    ```

- 呼出关键字：`height` 

  - 定义高度

  - Snipped 代码

    ```javascript
     "body": ["height: $1px;"]
    ```

- 呼出关键字：`height` 

  - 自适应高度

  - Snipped 代码

    ```javascript
    "body": ["height: auto;"]
    ```

- 呼出关键字：`max-width` 

  - 最大宽度

  - Snipped 代码

    ```javascript
    "body": ["max-width: $1px;"]
    ```

- 呼出关键字：`max-height` 

  - 最大高度

  - Snipped 代码

    ```javascript
    "body": ["max-height: $1px;"]
    ```

- 呼出关键字：`min-width` 

  - 最小宽度

  - Snipped 代码

    ```javascript
    "body": ["min-width: $1px;"]
    ```

- 呼出关键字：`min-height` 

  - 最小高度

  - Snipped 代码

    ```javascript
    "body": ["min-width: $1px;"]
    ```

#### 定位

- 呼出关键字：`position: static;` 

  - 静态定位

  - Snipped 代码

    ```javascript
    "body": ["position: static;", "top: 0px;", "left: 0px;"]
    ```

- 呼出关键字：`position: relative;` 

  - 相对定位

  - Snipped 代码

    ```javascript
    "body": ["position: relative;", "top: 0px;", "left: 0px;"]
    ```

- 呼出关键字：`position: absolute;` 

  - 绝对定位

  - Snipped 代码

    ```javascript
    "body": ["position: absolute;", "top: 0px;", "left: 0px;"]
    ```

- 呼出关键字：`position: fixed;` 

  - 固定定位

  - Snipped 代码

    ```javascript
    "body": ["position: fixed;", "top: 0px;", "left: 0px;"]
    ```

#### 边框

- 呼出关键字：`border-color` 

  - 边框颜色

  - Snipped 代码

    ```javascript
    "body": ["/* transparent属性值为透明 */", "border-color: $1;"]
    ```

- 呼出关键字：`border-width` 

  - 边框高度

  - Snipped 代码

    ```javascript
    "body": ["border-width: $1;"]
    ```

- 呼出关键字：`border-style` 

  - 边框样式

  - Snipped 代码

    ```javascript
    "body": [
          "/* nome无边框/hidden隐藏边框/dotted点线/dashed虚线/solid实线/double双线边框/groove凹槽边框/ridge垄状边框/ */",
          "border-width: ${1|nome,hidden,dotted,dashed,solid,double,groove,ridge|};"
        ]
    ```

- 呼出关键字：`border` 

  - 边框复合写法

  - Snipped 代码

    ```javascript
    "body": ["border: #$1 $0px solid"]
    ```

- 呼出关键字：`border-top` 

  - 上边框复合写法

  - Snipped 代码

    ```javascript
    "body": ["border-top: #$1 $0px solid"]
    ```

- 呼出关键字：`border-bottom` 

  - 下边框复合写法

  - Snipped 代码

    ```javascript
    "body": ["border-bottom: #$1 $0px solid"]
    ```

- 呼出关键字：`border-left` 

  - 左边框复合写法

  - Snipped 代码

    ```javascript
    "body": ["border-left: #$1 $0px solid"]
    ```

- 呼出关键字：`border-right` 

  - 右边框复合写法

  - Snipped 代码

    ```javascript
    "body": ["border-right: #$1 $0px solid"]
    ```

- 呼出关键字：`border-radius` 

  - 圆角边框

  - Snipped 代码

    ```javascript
    "body": ["border-radius: 50%"]
    ```

- 呼出关键字：`border-top-left-radius` 

  - 左上角圆角边框

  - Snipped 代码

    ```javascript
     "body": ["border-top-left-radius: 50%"]
    ```

- 呼出关键字：`border-top-right-radius` 

  - 右上角圆角边框

  - Snipped 代码

    ```javascript
    "body": ["border-top-right-radius: 50%"]
    ```

- 呼出关键字：`border-bottom-right-radius` 

  - 右下角圆角边框

  - Snipped 代码

    ```javascript
    "body": ["border-bottom-right-radius: 50%"]
    ```

- 呼出关键字：`border-bottom-left-radius` 

  - 左下角圆角边框

  - Snipped 代码

    ```javascript
    "body": ["border-bottom-left-radius: 50%"]
    ```

- 呼出关键字：`border-image-source` 

  - 边框图片路径

  - Snipped 代码

    ```javascript
    "body": ["border-image-source: url($1);"]
    ```

- 呼出关键字：`border-image-slice` 

  - 边框图片内偏移

  - Snipped 代码

    ```javascript
    "body": ["border-image-slice: $1;"]
    ```

- 呼出关键字：`border-image-width` 

  - 边框图片宽度

  - Snipped 代码

    ```javascript
    "body": ["border-image-width: $1px;"]
    ```

- 呼出关键字：`border-image-repeat` 

  - 边框图片平铺样式

  - Snipped 代码

    ```javascript
     "body": ["border-image-repeat:  ${1|repeat,round,stretch|};"]
    ```

#### 轮廓

- 呼出关键字：`outline` 

  - 轮廓复合写法

  - Snipped 代码

    ```javascript
    "body": ["outline: #ccc 1px style;"]
    ```

- 呼出关键字：`outline-top` 

  - 上轮廓复合写法

  - Snipped 代码

    ```javascript
    "body": ["outline-top: #ccc 1px style;"]
    ```

- 呼出关键字：`outline-buttom` 

  - 下轮廓复合写法

  - Snipped 代码

    ```javascript
    "body": ["outline-buttom: #ccc 1px style;"]
    ```

- 呼出关键字：`outline-left` 

  - 左轮廓复合写法

  - Snipped 代码

    ```javascript
    "body": ["outline-left: #ccc 1px style;"]
    ```

- 呼出关键字：`outline-right` 

  - 右轮廓复合写法

  - Snipped 代码

    ```javascript
    "body": ["outline-right: #ccc 1px style;"]
    ```

#### 内边距

- 呼出关键字：`padding` 

  - 内边距复合写法

  - Snipped 代码

    ```javascript
    "body": [
          " /* ,只写一个属性值默认应用四个距离。两个值应用上下和左右。三个值则第一个为上，第二个为左右，第三个为下。四个值则为上右下左 */",
          "padding: $1;"
        ]
    ```

- 呼出关键字：`padding-top` 

  - 内边距与顶部拉开距离

  - Snipped 代码

    ```javascript
    "body": ["padding-top: $1px;"]
    ```

- 呼出关键字：`padding-right` 

  - 内边距与右边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["padding-right: $1px;"]
    ```

- 呼出关键字：`padding-left` 

  - 内边距与左边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["padding-left: $1px;"]
    ```

- 呼出关键字：`padding-buttom` 

  - 内边距与下边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["padding-buttom: $1px;"]
    ```

#### 外边距

- 呼出关键字：`margin` 

  - 外边距复合写法

  - Snipped 代码

    ```javascript
    "body": [
          " /* ,只写一个属性值默认应用四个距离。两个值应用上下和左右。三个值则第一个为上，第二个为左右，第三个为下。四个值则为上右下左 */",
          "margin: $1;"
        ]
    ```

- 呼出关键字：`margin-top` 

  - 外边距与顶部拉开距离

  - Snipped 代码

    ```javascript
    "body": ["margin-top: $1px;"]
    ```

- 呼出关键字：`margin-right` 

  - 外边距与右边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["margin-right: $1px;"]
    ```

- 呼出关键字：`margin-left` 

  - 外边距与左边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["margin-left: $1px;"]
    ```

- 呼出关键字：`margin-buttom` 

  - 外边距与下边拉开距离

  - Snipped 代码

    ```javascript
    "body": ["margin-buttom: $1px;"]
    ```

#### 浮动

- 呼出关键字：`float` 

  - 浮动

  - Snipped 代码

    ```javascript
    "body": ["margin: ${1|none,left,right|};"]
    ```

- 呼出关键字：`float清除浮动给父元素添加` 

  - 双伪元素清除浮动

  - Snipped 代码

    ```javascript
    "body": [
          ".clearfix:before,",
          ".clearfix:after {",
          "  content: \"\";",
          "display: table;",
          "",
          ".clearfix:after {",
          "  clear: both;",
          "}",
          "",
          ".clearfix {",
          "  *zoom: 1;",
          "}"
        ]
    ```

#### 背景

- 呼出关键字：`background-color` 

  - 背景颜色

  - Snipped 代码

    ```javascript
    "body": ["background-color: $1;"]
    ```

- 呼出关键字：`background-image` 

  - 背景图片

  - Snipped 代码

    ```javascript
    "body": ["background-color: ${1|none,url()|};"]
    ```

- 呼出关键字：`background-repeat` 

  - 背景图片平铺

  - Snipped 代码

    ```javascript
     "body": ["background-repeat: ${1|repeat,no-repeat,repeat-x,repeat-y|};"]
    ```

- 呼出关键字：`background-position` 

  - 背景图象位置

  - Snipped 代码

    ```javascript
    "body": ["background-position: $1;"]
    ```

- 呼出关键字：`background-attachment` 

  - 背景图象固定

  - Snipped 代码

    ```javascript
    "body": ["background-attachment: ${1|scroll,fixed|};"]
    ```

- 呼出关键字：`background-size` 

  - 背景图象大小

  - Snipped 代码

    ```javascript
    "body": ["background-attachment: ${1|px,%,cover,contain|};"]
    ```

- 呼出关键字：`background` 

  - 背景复合写法

  - Snipped 代码

    ```javascript
    "body": ["background: #ccc url() no-repeat scroll left top;"]
    ```

- 呼出关键字：`background-image` 

  - 背景颜色线性渐变(css3)

  - Snipped 代码

    ```javascript
    "body": ["background-image: linear-gradient($1, $0);"]
    ```

#### 表单

- 呼出关键字：`bd~修改表单value属性值颜色` 

  - 修改表单value属性值颜色

  - Snipped 代码

    ```javascript
    "body": ["input[value] {", "  color: rgb(228, 240, 161);", "}"]
    ```

- 呼出关键字：`bd~去掉光标进入表单显示默认轮廓` 

  - 去掉光标进入表单显示默认轮廓

  - Snipped 代码

    ```javascript
    "body": ["outline: none;"]
    ```

- 呼出关键字：`bd~输入框鼠标焦点颜色` 

  - 输入框鼠标焦点颜色

  - Snipped 代码

    ```javascript
    "body": ["caret-color: aquamarine;"]
    ```

- 呼出关键字：`bd~防止表单文本域拖拽` 

  - 防止表单文本域拖拽

  - Snipped 代码

    ```javascript
    "body": ["resize: none;"]
    ```

#### 表格初始化

- 呼出关键字：`bg~表格初始化` 

  - 表格初始化

  - Snipped 代码

    ```javascript
    "body": [
          "table {",
          "  /* 合并表格边框 */",
          "  border-collapse: collapse;",
          "  border-color: ccc;",
          "  border: 1px #ccc solid;",
          "}",
          "th,",
          "td {",
          "  border: 1px #ccc solid;",
          "}"
        ]
    ```

#### 列表

- 呼出关键字：`bg~表格初始化` 

  - 去掉列表符号

  - Snipped 代码

    ```javascript
    "body": ["list-style:none;"]
    ```

#### 行内元素和行内块元素的垂直对齐方式

- 呼出关键字：`vertical`  `hn~默认放置在行内块的基线上`

  - 默认放置在行内块的基线上

  - Snipped 代码

    ```javascript
    "body": ["vertical-align: baseline;"]
    ```

- 呼出关键字：`vertical`  `hn~把行内元素行高与行内块元素的顶端对齐`

  - 把行内元素行高与行内块元素的顶端对齐

  - Snipped 代码

    ```javascript
    "body": ["vertical-align: top;"]
    ```

- 呼出关键字：`vertical`  `hn~行内元素在行内块元素高度内垂直居中`

  - 行内元素在行内块元素高度内垂直居中

  - Snipped 代码

    ```javascript
    "body": ["vertical-align: middle;"]
    ```

- 呼出关键字：`vertical`  `hn~把行内元素行高与行内块元素的低端对齐`

  - 把行内元素行高与行内块元素的低端对齐

  - Snipped 代码

    ```javascript
    "body": ["vertical-align: bottom;"]
    ```

#### 鼠标经过元素光标形状改变

- 呼出关键字：`cursor: default;`  `sb~鼠标经过元素光标形状为默认的`

  - 鼠标经过元素光标形状为默认的

  - Snipped 代码

    ```javascript
    "body": ["vertical-align: baseline;"]
    ```

- 呼出关键字：`cursor: pointer;`  `sb~鼠标经过元素光标形状为小手的`

  - 鼠标经过元素光标形状为小手的

  - Snipped 代码

    ```javascript
    "body": ["cursor: pointer;"]
    ```

- 呼出关键字：`cursor: move;`  `sb~鼠标经过元素光标形状为移动`

  - 鼠标经过元素光标形状为移动

  - Snipped 代码

    ```javascript
    "body": ["cursor: move;"]
    ```

- 呼出关键字：`cursor: text;`  `sb~鼠标经过元素光标形状为文本`

  - 鼠标经过元素光标形状为文本

  - Snipped 代码

    ```javascript
    "body": ["cursor: text;"]
    ```

- 呼出关键字：`cursor: not-allowed;`  `sb~鼠标经过元素光标形状为禁止`

  - 鼠标经过元素光标形状为禁止

  - Snipped 代码

    ```javascript
    "body": ["cursor: not-allowed;"]
    ```

#### 元素的显示与隐藏

- 呼出关键字：`display:none;`  `yc~隐藏元素并脱离标准流`

  - 隐藏元素并脱离标准流

  - Snipped 代码

    ```javascript
    "body": ["display:none;"]
    ```

- 呼出关键字：`visibility:hidden;`  `yc~隐藏元素并脱离标准流`

  - 隐藏元素不脱离标准流

  - Snipped 代码

    ```javascript
    "body": ["visibility:hidden;"]
    ```

- 呼出关键字：`display:block;`  `xs~显示脱离标准流的元素`

  - 显示脱离标准流的元素

  - Snipped 代码

    ```javascript
    "body": ["display:block;"]
    ```

- 呼出关键字：`visibility: visible;`  `xs~显示脱离标准流的元素`

  - 显示不脱离标准流的元素

  - Snipped 代码

    ```javascript
     "body": ["visibility: visible;"]
    ```

#### 元素内容溢出操作

- 呼出关键字：`overflow:visible;`  `yc~不剪切内容也不添加滚动条`

  - 不剪切内容也不添加滚动条

  - Snipped 代码

    ```javascript
     "body": ["overflow:visible;"]
    ```

- 呼出关键字：`overflow:hiddem;`  `yc~不显示超过对象尺寸的内容，超出的部分隐藏掉。`

  - 不显示超过对象尺寸的内容，超出的部分隐藏掉。

  - Snipped 代码

    ```javascript
     "body": ["overflow:hiddem;"]
    ```

- 呼出关键字：`overflow:scroll;`  `yc~不管超出内容与否，总是显示滚动条。`

  - 不管超出内容与否，总是显示滚动条。

  - Snipped 代码

    ```javascript
    "body": ["overflow:scroll;"]
    ```

- 呼出关键字：`overflow:auto;`  `yc~超出自定显示滚动条，不超出不显示滚动条。`

  - 超出自定显示滚动条，不超出不显示滚动条。

  - Snipped 代码

    ```javascript
    "body": ["overflow:auto;"]
    ```

- 呼出关键字：`overflow-y`  `yc~上下超出部分`

  - 上下超出部分

  - Snipped 代码

    ```javascript
    "body": ["overflow-y"]
    ```

- 呼出关键字：`overflow-x`  `yc~左右超出部分`

  - 左右超出部分

  - Snipped 代码

    ```javascript
    "body": ["overflow-x"]
    ```

#### 滚动条实现

- 呼出关键字：`gdt~滚动条实现` 

  - 上下超出部分

  - Snipped 代码

    ```javascript
    "body": [
          " div {",
          "  width: 100px;",
          "  height: 100px;",
          "  background-color: rgb(87, 119, 207);",
          "  /* 设置内容超出元素显示滚动条并隐藏超出内容 */",
          "  overflow: auto;",
          "}",
          "div::-webkit-scrollbar {",
          "  /*滚动条整体样式*/",
          "  /*高宽分别对应横竖滚动条的尺寸*/",
          "  width: 2px;",
          "  height: 1px;",
          "}",
          "div::-webkit-scrollbar-thumb {",
          "  /*滚动条里面小方块样式*/",
          "  border-radius: 10px;",
          "  box-shadow: inset 0 0 5px rgba(97, 184, 179, 0.1);",
          "  background: #78b4b4;",
          "}",
          "div::-webkit-scrollbar-track {",
          "  /*滚动条里面轨道的样式*/",
          "  box-shadow: inset 0 0 5px rgba(87, 175, 187, 0.1);",
          "  border-radius: 10px;",
          "  background: #ededed;",
          "}"
        ]
    ```

#### 字体

- 呼出关键字：`font-family`  `zt~设置字体类型`

  - 设置字体类型

  - Snipped 代码

    ```javascript
    "body": ["font-family：'Microsoft YaHei', 'Microsoft YaHei';"]
    ```

- 呼出关键字：`font`  `zt~引入字体并设置字体类型`

  - 引入字体并设置字体类型

  - Snipped 代码

    ```javascript
    "body": [
          " @font-face {",
          "  font-family: 创客贴金刚体;",
          "  src: url(../创客贴金刚体.otf);",
          "}",
          "",
          "div {",
          "  font-family: 创客贴金刚体;",
          "}"
        ]
    ```

- 呼出关键字：`font-size`  `zt~字体大小`

  - 字体大小

  - Snipped 代码

    ```javascript
    "body": ["font-size: $1px ;"]
    ```

- 呼出关键字：`font-weight`  `zt~字体粗细`

  - 字体粗细

  - Snipped 代码

    ```javascript
    "body": ["font-weight: ${1|bold,700,nomber,400|};"]
    ```

- 呼出关键字：`font-style`  `zt~字体样式`

  - 字体样式

  - Snipped 代码

    ```javascript
    "body": ["font-style: ${1|normal,italic|};"]
    ```

- 呼出关键字：`line-height`  `zt~字体行高`

  - 字体行高

  - Snipped 代码

    ```javascript
    "body": ["line-height: $1px;"]
    ```

- 呼出关键字：`letter-spacing`  `zt~字体间隔`

  - 字体间隔

  - Snipped 代码

    ```javascript
    "body": ["letter-spacing: $1px;"]
    ```

- 呼出关键字：`text-transform`  `zt~字符串中的字母大小写切换`

  - 字符串中的字母大小写切换

  - Snipped 代码

    ```javascript
    "body": ["text-transform: ${1|none,uppercase,lowercase,capitalize|};"]
    ```

- 呼出关键字：`font`  `zt~复合写法`

  - 复合写法

  - Snipped 代码

    ```javascript
    "body": [
          "/* 字体样式 字体粗细 文字大小属性值(必须保留)/文本行高属性值 字体类型 */",
          "font: $1;"
        ]
    ```

- 呼出关键字：`text-align`  `zt~字体水平对齐`

  - 字体水平对齐

  - Snipped 代码

    ```javascript
    "body": ["text-align: ${1|left,right,center|};"]
    ```

- 呼出关键字：`text-decoration`  `zt~文本装饰`

  - 文本装饰

  - Snipped 代码

    ```javascript
    "body": ["text-decoration: ${1|none,underline,overline,line-through|};"]
    ```

- 呼出关键字：`text-indent`  `zt~首行文本缩进`

  - 首行文本缩进

  - Snipped 代码

    ```javascript
     "body": ["text-indent: ${1|em,xp,%|};"]
    ```

- 呼出关键字：`zt~实现单行文本溢出显示省略号` 

  - 实现单行文本溢出显示省略号

  - Snipped 代码

    ```javascript
    "body": [
          "white-space: nowrap;",
          "overflow: hidden;",
          "text-overflow: ellipsis;"
        ]
    ```

- 呼出关键字：`zt~实现多行文本溢出显示省略号` 

  - 实现多行文本溢出显示省略号

  - Snipped 代码

    ```javascript
    "body": [
          "overflow:hidden;",
          "text-overflow: ellipsis;",
          "display: -webkit-box;",
          "-webkit-line-clamp: 2;",
          "-webkit-box-orient: vertical;"
        ]
    ```

- 呼出关键字：`word-wrap`  `zt~英文字符强制换行` 

  - 英文字符强制换行

  - Snipped 代码

    ```javascript
    "body": ["word-wrap: break-word;"]
    ```

- 呼出关键字：`writing-mode`  `zt~文字排列方式` 

  - 文字排列方式

  - Snipped 代码

    ```javascript
     "body": ["writing-mode: ${1|horizontal-tb,vertical-rl|};"]
    ```

#### 私有浏览器前缀

- 呼出关键字：`-moz-` 

  - firefox浏览器私有属性

  - Snipped 代码

    ```javascript
    "body": ["-moz-"]
    ```

- 呼出关键字：`-ms-` 

  - 代表ie浏览器私有属性

  - Snipped 代码

    ```javascript
    "body": ["-ms-"]
    ```

- 呼出关键字：`-webkit-` 

  - 代表safari，chrome私有属性

  - Snipped 代码

    ```javascript
    "body": ["-webkit-"]
    ```

- 呼出关键字：`-o-` 

  - 代表Opera私有属性

  - Snipped 代码

    ```javascript
    "body": ["-o-"]
    ```

#### 元素模糊(css3)

- 呼出关键字：`filter:blur`  `ys~元素模糊(css3)` 

  - 元素模糊(css3)

  - Snipped 代码

    ```javascript
    "body": ["filter:blur($1px);"]
    ```

#### 元素透明度(css3)

- 呼出关键字：`opacity`  `ys~元素透明度(css3)` 

  - 元素模糊(css3)

  - Snipped 代码

    ```javascript
    "body": ["opacity: $1%;"]
    ```

#### 阴影

- 呼出关键字：`box-shadow`  `yy~块级元素阴影(css3)` 

  - 块级元素阴影(css3)

  - Snipped 代码

    ```javascript
    "body": [
          "/* 第一个参数：单位xp必须有水平阴影位置允许负值 */",
          "/* 第二个参数：单位xp必须有垂直阴影的位置允许负值 */",
          "/* 第三个参数：单位xp可选模糊距离 */",
          "/* 第四个参数：颜色可选阴影颜色 */",
          "/* 第五个参数：inset可选将外部阴影改为内部阴影默认为外部阴影 */",
          "box-shadow: $1;"
        ]
    ```

- 呼出关键字：`text-shadow`  `yy~文字阴影(css3)` 

  - 文字阴影(css3)

  - Snipped 代码

    ```javascript
    "body": [
          "/* 第一个参数：单位xp必须有水平阴影位置允许负值 */",
          "/* 第二个参数：单位xp必须有垂直阴影的位置允许负值 */",
          "/* 第三个参数：单位xp可选模糊距离 */",
          "/* 第四个参数：颜色可选阴影颜色 */",
          "/* 第五个参数：inset可选将外部阴影改为内部阴影默认为外部阴影 */",
          "text-shadow: $1;"
        ]
    ```

#### 盒子模型

- 呼出关键字：`box-shadow`  `hz~传统的盒子模型` 

  - 传统的盒子模型

  - Snipped 代码

    ```javascript
    "body": ["box-sizing:content-box;"]
    ```

- 呼出关键字：`box-shadow`  `hz~css3盒子模型` 

  - css3盒子模型

  - Snipped 代码

    ```javascript
    "body": ["box-sizing:border-box;"]
    ```

#### 动画

- 呼出关键字： `dh~简单动画过渡(css3)` 

  - Snipped 代码

    ```javascript
    "body": [
          "div:hover {",
          "  transition: 要过渡的属性所有的属性都变化过渡填all",
          "    花费时间单位是秒s，必须写单位",
          "    运动曲线默认是ease逐渐慢下来可以忽略/linear匀速/ease-out加速/ease-in-out先加速后减速",
          "    何时开始单位是秒必须写单位 默认是0s，可以忽略;",
          "}"
        ]
    ```
  
- 呼出关键字：`dh~高级动画过渡(css3)` 

  - Snipped 代码

    ```javascript
    "body": [
          "div {",
          "  width: 100px;",
          "  height: 200px;",
          "  background-color: #000;",
          "  /* 使用动画，move是自己定义的动画名称 */",
          "  animation-name: move;",
          "  /* 持续时间单位秒s */",
          "  animation-duration: 1s;",
          "  /* cubic-bezier(n,n,n,n) 在 cubic-bezier 函数中定义自己的值。可能的值是 0 至 1 之间的数值。 */",
          "  /* 速度曲线,默认值为ease动画以低速开始，然后加快，在结束前变慢。 */",
          "  /* linear规定以相同速度开始至结束的过渡效果（等于 cubic-bezier(0,0,1,1) */",
          "  /* ease默认规定慢速开始，然后变快，然后慢速结束的过渡效果（cubic-bezier(0.25,0.1,0.25,1)）。 */",
          "  /* ease-in定以慢速开始的过渡效果（等于 cubic-bezier(0.42,0,1,1)）。 */",
          "  /* ease-out规定以慢速结束的过渡效果（等于 cubic-bezier(0,0,0.58,1)）。 */",
          "  /* ease-in-out规定以慢速开始和结束的过渡效果（等于 cubic-bezier(0.42,0,0.58,1)）。 */",
          "  /* cubic-bezier(*n*,*n*,*n*,*n*)在 cubic-bezier 函数中定义自己的值。可能的值是 0 至 1 之间的数值。 */",
          "/* steps(1,start或end)在动画时间内的变化次数，有两个参数第一个参数指定函数的间隔数，该参数是一个正整数（大于 0）。 第二个参数是可选的，表示动画是从时间段的开头连续还是末尾连续。 */",
          "animation-timing-function: ease;",
          "/* 规定动画何时开始，默认是0 */",
          "animation-delay: 0;",
          "/* 规定动画被播放的次数，默认是1，还有infinite无限循环的意思 */",
          "animation-iteration-count: 1;",
          "/* 规定动画是否在下一周期逆向播放，默认是\"normal\"不逆播放，\"alternate\"逆播放 */",
          "animation-direction: normal;",
          "/* 规定动画是否正在运行或暂停。默认是\"running\"运行，\"paused\"暂停 */",
          "animation-play-state: running;",
          "/* 规定动画结束后状态，保持在结束的位置状态forwards或者默认是回到起始位置状态backwards */",
          "animation-fill-mode: backwards;",
          "}",
          "/* move是动画名称，可以自己定义 */",
          "/* 0%和100%可以用关键词\"from\"和\"to\"代替 */",
          "@keyframes move {",
          "  /* 开始状态 */",
          "  0% {",
          "  height: 200px;",
          "  transform: translateX(0px);",
          "}",
          "/* 结束状态 */",
          "100% {",
          "  height: 100px;",
          "  transform: translateX(100px);",
          "}",
          "}"
        ]
    ```

#### 2D转换(css3)

- 呼出关键字： `2d转换(css3)~移动元素` 

  - Snipped 代码

    ```javascript
    "body": ["transform:translate(${1:x轴},${0:y轴});"]
    ```

- 呼出关键字： `2d转换(css3)~元素旋转` 

  - Snipped 代码

    ```javascript
    "body": [
          "/* 数值为正时是顺时针旋转，deg表示度数。 */",
          "transform: rotate(45deg);"
        ]
    ```

- 呼出关键字： `2d转换(css3)~元素缩放` 

  - Snipped 代码

    ```javascript
    "body": [
          "/* 宽和高都放大了2倍,只写一个参数同步宽和高，小数代表缩放 */",
          "/* transform-origin: left bottom; 左下角缩放/放大 */",
          "/* sform-tranorigin: right bottom; 右下角缩放/放大 */",
          "/* transform-origin: left top; 左上角缩放/放大 */",
          "/* transform-origin: right top; 右上角缩放/放大 */",
          "transform:scale(2,2);"
        ]
    ```

- 呼出关键字： `2d转换(css3)~综合写法` 

  - Snipped 代码

    ```javascript
    "body": ["transform: translate()  rotate()   scale();"]
    ```

#### 3D转换(css3)

- 呼出关键字：`3d转换(css3)~1-移动` 

  - Snipped 代码

    ```javascript
    "body": [
          "/* 其中x，y，z分别指要移动的轴的方向距离 */",
          "/* transform:translatez(100px); 仅仅是在z轴上移动(一般用px单位)，往外面是正值，往里面是负值。*/",
          "/* transform:translatey(100px); 仅仅是在y轴上移动，下面是正值，上面是负值。*/",
          "/* transform:translatex(100px); 仅仅是在x轴上移动，右边正值，左边负值。*/",
          "transform:translate3d(x,y,z);"
        ]
    ```
  
- 呼出关键字：`3d转换(css3)~2.透视(写在父盒子上)` 

  - Snipped 代码

    ```javascript
    "body": ["perspective: 500px;"]
    ```
  
- 呼出关键字：`3d转换(css3)~3.呈现(写在父盒子上)` 

  - Snipped 代码

    ```javascript
    "body": [
          "/* 默认子元素不开启3d立体空间 transform-style: flat; */",
          "transform-style: preserve-3d;"
        ]
    ```
  
- 呼出关键字：`3d转换(css3)~4.旋转` 

  - Snipped 代码

    ```javascript
    "body": [
          "/* 围绕y轴旋转180度，正值为向右方向旋转，负值为向左 transform: rotatey(180deg); */",
          "/* 围绕z轴旋转180度，正值时向右边平面旋转，负值为向左 transform: rotatez(180deg); */",
          "/* 自定义轴旋转 */",
          "/* 第一个参数为x轴, 1表示沿着x轴旋转 */",
          "/* 第二个参数为y轴, 0表示没有沿着y轴旋转 */",
          "/* 第三个参数为z轴, 0表示没有沿着z轴旋转 */",
          "/* 如果同时有多个1就表示与交叉轴的角度旋转 */",
          "/* transform: rotate3d(1,0,0,180deg); */",
          "/* 还可以不同轴设置不同的旋转角度 */",
          "/* transform: rotatey(80deg) rotatex(1180deg); */",
          "/* 围绕x轴旋转180度，正值为向上方向旋转，负值为向下方向旋转。 */",
          "transform: rotatex(180deg);"
        ]
    ```

#### flex弹性布局(css3)

- 呼出关键字：`flex~1.给父元素添加容器`

  - Snipped 代码

    ```javascript
    "body": ["display: flex;"]
    ```
  
- 呼出关键字：`flex~2.给父元素添加子元素排列方向属性`

  - Snipped 代码

    ```javascript
     "body": [
          "/* 默认为row元素从左到右开始排列 / row-reverse元素从右到左开始排列 / column元素从上到下排列 / column-reverse元素从下到上开始排列 */",
          "flex-direction: $1;"
        ]
    ```
  
- 呼出关键字：`flex~3.给父元素添加子元素主轴方向上的排列方式属性`

  - Snipped 代码

    ```javascript
    "body": [
          "/* flex-start默认值第一个子元素靠左开始向右排列 / flex-end最后的子元素靠右开始向左开始排列 / center子元素挨到一起，居中对齐。 / space-around左右留点小空间再平分剩余空间 / space-between先两边贴边 再平分剩余空间 */",
          "justify-content: $1;"
        ]
    ```
  
- 呼出关键字：`flex~4.给父元素添加子元素是否换行属性`

  - Snipped 代码

    ```javascript
    "body": ["/* nowrap默认值不换行 wrap换行 */", "flex-wrap: $1;"]
    ```
  
- 呼出关键字：`flex~5.给父元素添加子元素侧轴方向上的排列方式属性(单行)`

  - Snipped 代码

    ```javascript
     "body": [
          "/* flex-start默认值从上到下 / flex-end从下到上 / center挤在一起居中 / stretch拉伸 */",
          "align-items: $1;"
        ]
    ```
  
- 呼出关键字：`flex~6.给父元素添加子元素侧轴方向上的排列方式属性(多行)`

  - Snipped 代码

    ```javascript
    "body": [
          "/* flex-start默认值在侧轴的头部开始排列 / flex-end在侧轴的尾部开始排列 / center在侧轴中间显示 / space-around子项在侧轴平分剩余空间 / space-between子项在侧轴先分布在两头，再平分剩余空间 / stretch设置子项元素高度平分父元素高度 */",
          "align-content: $1;"
        ]
    ```
  
- 呼出关键字：`flex~7.给子元素添加宽度相关的属性`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 默认值为0，设置为1表示平分父元素主轴宽度，或填充剩余空间。 */",
          "/* flex-grow: 1; */",
          "/* 设置主轴上子元素的宽度 */",
          "/* flex-basis: 20px; */",
          "/* 默认值为1，当子元素大小超过父元素时，会平均分配宽度，不会溢出父盒子。 */",
          "/* 如果值为0，不会平均分配宽度，会溢出父盒子，显示原宽度。 */",
          "/* flex-shrink: 1; */",
          "/* flex为以上三个的简写属性，第一个参数为flex-grow，第二个参数为flex-shrink，第三个参数为flex-basis */",
          "flex: $1;"
        ]
    ```
  
- 呼出关键字：`flex~8.给子元素添加排列顺序的属性`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 默认为0，填1则表示把当前子元素插入到后面一位。 */",
          "order: 1;"
        ]
    ```
  
- 呼出关键字：`flex~9.给侧轴方向上的子元素添加排列方式属性`

  - Snipped 代码

    ```javascript
    "body": [
          "/* flex-start默认值从上到下 / flex-end从下到上 / center挤在一起居中 / stretch拉伸 */",
          "align-self: $1;"
        ]
    ```

#### grid网格布局(css3)

- 呼出关键字：`grid~1.使父元素成为网格容器`

  - Snipped 代码

    ```javascript
    "body": ["/* 或者display: inline-grid; */", "display: grid;"]
    ```
  
- 呼出关键字：`grid~2.给父元素添加grid-template-columns设置列数`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 默认值为auto表示只有1列 */",
          "/* 默认值为auto auto表示有2列 */",
          "/* 默认值为auto可以是px指定每列的宽度 */",
          "grid-template-columns: auto;"
        ]
    ```
  
- 呼出关键字：`grid~3.给父元素添加grid-template-rows设置每行的高度`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 默认值为auto表示每行高度平均分配 */",
          "/* 默认值为100px 110px 120px表示设置第一行高度为100px，第二行高度为110px，第三行高度为120px。 */",
          "grid-template-rows: auto;"
        ]
    ```
  
- 呼出关键字：`grid~4.给父元素添加grid-row-gap设置这些元素行的间隔`

  - Snipped 代码

    ```javascript
    "body": ["grid-row-gap: 10px;"]
    ```
  
- 呼出关键字：`grid~5.给父元素添加grid-column-gap设置这些元素列的间隔`

  - Snipped 代码

    ```javascript
    "body": ["grid-column-gap: 10px;"]
    ```
  
- 呼出关键字：`grid~6.子元素更换位置`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 哪个元素要更换到哪个位置，就给这个元素添加。 */",
          "/* grid-row: 1 / 2;原位置子元素的行线 */",
          "grid-row: 1 / 2;",
          "/* grid-column: 1 / 3;原位置子元素的列线 */",
          "grid-column: 1 / 3;"
        ]
    ```
  
- 呼出关键字：`grid~7.设置某个子元素横跨多个子元素的宽度或高度`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 哪个元素要更换到哪个位置，就给这个元素添加。 */",
          "/* grid-row: 1 / 2;跨原位置子元素的行线 */",
          "grid-row: 1 / 2;",
          "/* grid-column: 1 / 3;跨原位置子元素的列线 */",
          "grid-column: 1 / 3;"
        ]
    ```
  
- 呼出关键字：`grid~8.给父元素添加子元素的垂直对齐方式`

  - Snipped 代码

    ```javascript
     "body": [
          "/* align-content: normal 默认为垂直对齐方式为顶部或 align-content: stretch */",
          "/* align-content: center; 默认为垂直对齐方式为居中 */",
          "/* align-content: space-between; 默认为垂直对齐方式先两端对齐再垂直居中 */",
          "/* align-content: space-around; 默认为垂直对齐方式先两端留点小空间再平均分配剩余空间 */",
          "/* align-content: space-evenly; 默认为垂直对齐方式平均分配剩余空间 */",
          "align-content: normal;"
        ]
    ```
  
- 呼出关键字：`grid~9.给父元素添加子元素的水平对齐方式`

  - Snipped 代码

    ```javascript
    "body": [
          "/* justify-content: normal; 默认为水平对齐方式为左边或 align-content: start */",
          "/* justify-content: center; 默认为水平对齐方式为居中 */",
          "/* justify-content: end; 默认为水平对齐方式为右对齐 */",
          "/* justify-content: space-between; 默认为水平对齐方式为先两端对齐再平分剩余空间 */",
          "/* justify-content: space-around; 默认为水平对齐方式为先两端留点小空间再平分剩余空间 */",
          "/* justify-content: space-evenly; 默认为水平对齐方式为平分剩余空间 */",
          "justify-content: normal;"
        ]
    ```
  
- 呼出关键字：`grid~10.实现网格布局最便捷方法`

  - Snipped 代码

    ```javascript
    "body": [
          "/* 步骤一：给父盒子开启网格布局容器 */",
          "/* display: grid; */",
          "/* 步骤二：给父盒子添加确定好布局骨架的属性 */",
          "/* grid-template-areas: */",
          "/*   \"yi  er san\" */",
          "/*   \"yi  si si\"; */",
          "/*  步骤三：给子元素填写骨架名 */",
          "/*  grid-area: yi; */"
        ]
    ```

