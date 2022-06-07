## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

<img src="https://gitlab.com/imingx/picgo/raw/main/2022/202205051640484.png" align="right" width="20%">

This is the `PaperDaily` Project.

you can explore below: 

- 📄 **Documents: [repo](https://github.com/SE-mcdb/SE2022_doc)**
- 🕊 Resources: [repo](https://github.com/SE-mcdb/SE2022_source)
- 🐳 Backend Code: [repo](https://github.com/SE-mcdb/SE2022_Backend)

| 🦋 FRONTEND |  🪹 CODE                                                     | 🍿 DEPLOYMENT                                        | 🔗 LINK  |
| ------- | ---- | ------- | ------- |
| uni-app |   [repo](https://github.com/SE-mcdb/SE2022_Frontend_App)   |   [App](https://github.com/SE-mcdb/App)   |- [`apk`](https://github.com/SE-mcdb/SE2022_Frontend_App/releases)<br/>- [`spoc.uno`](http://spoc.uno) |
| manager | [repo](https://github.com/SE-mcdb/SE2022_Frontend_Manager) | [Manager](https://github.com/SE-mcdb/Manager) | [`m.spoc.uno`](http://m.spoc.uno) |
| web <em>(unused)</em>     | [repo](https://github.com/SE-mcdb/SE2022_Frontend_Web)     | [Web](https://github.com/SE-mcdb/Web) | ~[`w.spoc.uno`](http://w.spoc.uno)~ |

<details> <summary><h6>Git Commit Guidelines</h6></summary>

参见：[Angular提交信息规范](https://zj-git-guide.readthedocs.io/zh_CN/latest/message/Angular%E6%8F%90%E4%BA%A4%E4%BF%A1%E6%81%AF%E8%A7%84%E8%8C%83/)

格式如下：

```
-m"<type>(<scope>): <subject>
空行
<body>
空行
<footer>"
```

### 设置

提交信息至少包含类型(`type`)和主题(`subject`)，其他如作用域(`scope`)、正文(`body`)和页脚(`footer`)是可选的。

`type` 需要指定为下面其中一个：

1. `build`：对构建系统或者外部依赖项进行了修改
2. `docs`：对文档进行了修改
3. `feat`：增加新的功能
4. `fix`：修复`bug`
5. `pref`：提高性能的代码更改
6. `refactor`：既不是修复bug也不是添加特征的代码重构
7. `style`：不影响代码含义的修改，比如空格、格式化、缺失的分号等
8. `test`：增加测试或者矫正已存在的测试

`subject` 有以下准则：

1. 使用命令式和现在时态
2. 不要大写首字母
3. 不在末尾添加句号   

`scope` 是标识更改内容的位置。

`body` 是详细描述本次commit的内容。
 
`footer` 用于声明不兼容变动和关闭issue。

### 例子

```
git commit -m"docs: README里增加commit规范

包括<scope>，<type>等内容"

git commit -m"docs(README): 增加commit规范"
git commit -m"docs: 文档增加commit规范"
```

</details>
