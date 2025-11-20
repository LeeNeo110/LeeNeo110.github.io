如何使用和修改？
本地测试：
	在您的电脑上新建一个文本文件，命名为 index.html。
	将上面的代码完整粘贴进去。
	双击文件，浏览器会自动打开，您就能看到一个包含假数据的个人主页。
编辑内容：
	用记事本或代码编辑器（推荐 VS Code）打开 index.html。
	找到代码下半部分的 <script> 标签内的 const myData = { ... } 区域。
	个人信息： 修改 profile 里的内容。
	图片： 将您的照片（如 me.jpg）和论文封面图放在 index.html 同一个文件夹里，然后将代码里的 https://via.placeholder.com/300 替换为文件名 me.jpg。
	论文： 在 papers 数组里复制/粘贴大括号 {...} 块来添加新论文。
如何上线（免费发布）：
	去 GitHub 注册一个账号。
	新建一个仓库（Repository），名字必须是 您的用户名.github.io（例如：您的用户名是 science-man，仓库名必须是 science-man.github.io）。
	将您编辑好的 index.html 和图片文件上传（Upload files）到这个仓库里。
	等待约 1-2 分钟，访问 https://您的用户名.github.io，您的个人主页就上线了！

信封图标： <sup>&#9993;</sup> (显示为 <sup>✉</sup>)
十字架（Dagger）： <sup>&dagger;</sup> (显示为 <sup>†</sup>)

为什么推荐这个方案？
	可控性强： 您不需要懂复杂的 CSS，只需要在 myData 里改字。
	学术友好： 已经为您设计好了“论文封面图+链接”的排版，这在普通建站工具里很难调整。
	零成本： 不需要买域名和服务器。
如果您未来觉得这个单页不够用了（需要写博客、分多页），那时再考虑迁移到 Hugo Academic，对于目前的个人展示，这个单页模板是最轻量高效的。