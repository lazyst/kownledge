# HTML标签

## MDN文档
[MDN官网](https://developer.mozilla.org/)

### 图片
```html
<img
	src=""
	alt=""
/>
```
图片不加载时显示 `alt` 的内容

### 音频
```html 
<audio
	src=""
	controls
></audio>
```
`controls`
属性显示播放控件

### 视频
```html
<video
	src=""
	controls
	></video>
```
`controls`
属性显示播放控件

### 输入标签
```html
<input placeholder="">

<input type="range">

<input type="number" min="1" max="10">

<input type="date" min="2018-02-10">

<textarea>Hey</textarea>
<!-- textarea 默认可以调整大小 -->
```
配合使用的标签 `<label>`
```html
<label>
	<input type="radio" name="sport" />⚽
</label>
<label>
	<input type="radio" name="sport">🏀
</label>
```
多项选择
```html
<select>
	<option>🥤</option>
	<option>🍉</option>
	<option>🎂</option>
</select>
```
为 `<input>` 设置提示选项
```html
<input list="countries" />
<datalist id="countries">
	<option>Greece</option>
	<option>United Kingdom</option>
	<option>United States</option>
</datalist>
```

### 文本标签
```html
<!-- 长引用 -->
<blockquote cite="链接">
	<p>内容</p>
</blockquote>

<!-- 短引用 -->
<cite>小王子</cite>
<q>字符串是不可变量</q>

<!-- 代码块 -->
<code>const</code>

<pre><code>
	const add = (a, b) => a + b;
	const multiply = (a, b) => a *b;
</pre></code>

<!-- 标注重点 -->
<!-- 含义重点常用 -->
<strong>风险评估</strong> 

<!-- 语气重点常用 -->
<em>cute</em>
```

### 内容划分
```html
<!-- 头部 -->
<header></header>
<!-- 内容 -->
<main>
	<article></article>
</main>
<!-- 底部,页脚 -->
<footer></footer>
<!-- 侧边栏 -->
<aside></aside>
```

### HTML语义化
+ HTML中的元素、属性及属性值都拥有某些含义
+ 开发者应该遵循语义来编写HTML
	+ 有序列表用ol；无序列表用ul
	+ lang属性表示内容索使用的语言

语义化给谁看
+ 开发者 - 修改、维护页面
+ 浏览器 - 展示页面
+ 搜索引擎 - 提取关键词、排序
+ 屏幕阅读器 - 给盲人读页面内容

为什么要语义化
+ 代码可读性
+ 可维护性
+ 搜索引擎优化
+ 提升无障碍性

如何做到语义化
+ 了解每个标签和属性的含义
+ 思考什么标签最适合描述这个内容
+ 不适用可视化工具生成代码








