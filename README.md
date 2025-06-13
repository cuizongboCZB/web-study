# 全栈编程


## 🧱 一、HTML：网页结构

关键词总览：结构标签 + 表单 + 嵌套

	•	<!DOCTYPE html>：声明 HTML5 文档
	•	<html>, <head>, <body>：网页三大结构
	•	<title>：网页标题
	•	<h1> ~ <h6>：标题
	•	<p>：段落
	•	<a href="">：超链接
	•	<img src="" alt="">：图片
	•	<ul>, <ol>, <li>：列表
	•	<div>, <span>：布局容器、内联容器
	•	<form>, <input>, <textarea>, <button>：表单基础
	•	<label>, <select>, <option>：表单高级元素
	•	target="_blank"：新窗口打开链接
	•	alt：图片无法加载时的替代文本
	•	iframe, video, audio：媒体嵌入

⸻

## 🎨 二、CSS：网页样式

关键词总览：样式控制 + 布局 + 动画

	•	选择器：class、id、后代选择器、伪类（:hover、:nth-child()）
	•	样式：color、font-size、font-family、line-height
	•	布局：
	•	box model（盒模型）：margin、padding、border、content
	•	display: block、inline、inline-block、none
	•	position: static、relative、absolute、fixed、sticky
	•	flex：justify-content、align-items、flex-direction
	•	grid：grid-template-columns、gap、place-items
	•	背景：background-color、background-image
	•	尺寸：width、height、max-width、vh、vw
	•	圆角和阴影：border-radius、box-shadow
	•	动画：transition、transform、keyframes

⸻

## 🧠 三、JavaScript：网页交互

关键词总览：变量 + 条件 + 函数 + DOM

📌 基础语法

	•	变量声明：let、const、var
	•	数据类型：Number、String、Boolean、Array、Object
	•	运算符：+、-、==、===、&&、||
	•	条件判断：if、else、switch
	•	循环：for、while、forEach
	•	函数定义：function、箭头函数 () => {}

📌 DOM 操作

	•	获取元素：getElementById()、querySelector()
	•	修改内容：innerText、innerHTML
	•	修改样式：element.style
	•	操作类名：classList.add()、remove()、toggle()
	•	事件绑定：onclick、addEventListener
	•	表单操作：value、submit

📌 异步

	•	setTimeout、setInterval
	•	fetch：请求 API
	•	Promise、async/await

⸻

## 🧩 四、Vue 3：现代前端框架

关键词总览：响应式 + 组件 + 路由 + 状态

	•	创建项目：Vite + Vue CLI
	•	响应式核心：ref、reactive、watch、computed
	•	模板语法：{{}}、v-bind、v-model、v-if、v-for、v-on（@ /.）
	•	组件系统：props、emit、slots、生命周期钩子（onMounted 等）
	•	状态管理：Pinia（代替 Vuex）
	•	路由管理：Vue Router（页面跳转）
	•	表单双向绑定：v-model
	•	条件与列表渲染：v-if、v-for

⸻

## 🛠 五、Node.js + Express：后端入门

关键词总览：API + 路由 + 中间件 + 请求响应

	•	Node.js 基础语法：模块化、文件操作、HTTP 模块
	•	Express 框架：
	•	创建服务：express()
	•	路由定义：app.get()、app.post()
	•	参数获取：req.params、req.query、req.body
	•	返回响应：res.send()、res.json()
	•	中间件：app.use()、错误处理
	•	跨域处理：cors 中间件
	•	连接数据库：MongoDB + mongoose

⸻

## 🧮 六、MongoDB：数据库

关键词总览：集合 + 文档 + 操作语句

	•	数据结构：集合（Collection）+ 文档（Document）
	•	常用命令：
	•	find()、insertOne()、updateOne()、deleteOne()
	•	mongoose 使用：
	•	定义 Schema
	•	创建模型
	•	执行查询和插入

⸻

## 🧪 七、工具链与部署

关键词总览：版本控制 + 部署平台

	•	Git 基础：init、clone、commit、push、.gitignore
	•	GitHub：创建仓库，托管代码
	•	Postman：测试接口
	•	前端部署平台：
	•	Vercel、Netlify、GitHub Pages
	•	后端部署平台：
	•	Render、Railway、Fly.io

⸻

💡 补充：实用开发技能
	•	响应式设计：媒体查询（Media Query）
	•	图标与 UI 库：FontAwesome、Tailwind CSS、Element Plus
	•	接口调试：Chrome 开发者工具 → Network、Console、Elements
	•	跨端适配：移动端、PC端兼容性处理
	•	安全基础：输入校验、跨站防护（XSS）

⸻

## ✅ 总结

> 这份关键词列表涵盖了从零基础到实战的完整路径，你可以：
	•	作为知识树来查漏补缺
	•	每完成一个阶段，回头复盘这些关键词
	•	实战时，遇到不会的概念也能迅速定位重点

