# pagingPlugins 陪伴是最长情的告白  @陪白
pagingPlugins是一个简单基于jquery的响应式分页显示插件。

- 官网: http://accompanyconfession.online（作者）
### 说明
- 本插件在调用方法创建对象的初始化的时候，会根据css进行适当的删减，后通过js执行，从而达到适应屏幕，据作者测试，屏幕最小宽度为370px,超过此大小将出现布局混乱。
- 在html页面中引入pagingPlugins.min.css和pagingPlugins.min.js,前提是已经引入了jquery，pagingPlugins.min.css分页插件的样式（不可修改），pagingPlugins.min.js是核心代码，控制这整个插件的初始化等等操作。
- 在主页添加$("元素选择").paging();完成初始化。
- 本插件可以自动根据屏幕进行自适应。
### 参数
- total:总页，必须给值，虽然不给不报错，但是插件将按照本身默认的总页进行初始化（总页默认值:150）。
- showCount:显示条数，不给就默认（每页显示条数的默认值:10）。
- color:点击按钮的颜色（默认:aqua）,如需要css hover样式，请选择元素自行添加。
- doSomethingFun:当点击每一个按钮的时候执行的函数，详见demo（参数:currentPage:当前页;showCount:展示条数）。
### 方法
- refresh():通常有删除操作时，使用此方法，此方法会重新构建整个插件的dom，以及参数初始化值得改变

> 如需源码进行修改请联系本人。

> 如果有幸赏脸，欢迎加本人qq讨论交流前端知识与后端知识，大家一起学习，一起进步

> qq:1391548667
 
                



