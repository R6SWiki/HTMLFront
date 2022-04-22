# HTML前端文件
本站的css有部分是通过TailwindCSS实现的，`style.css`是本站的tailwind核心文件。

## 内容
`src`目录下除了css文件外还有一些模板的设计方案，以及若干插图文件`image`。不过插图文件可能已经不需要了。
目前设计方案（`html`文件）：
武器ib：`src\infobox-weapon.html`
特勤干员首页设计：`src\oper.html`
武器信息悬浮卡：`src\weaponinfo-card.html`

## 使用方法


这里例举最简单的安装TailwindCSS和使用步骤，可根据需要参考：


1. 以最基本的方法安装TailwindCSS（如果已安装跳过）：使用在vscode项目中打开终端输入按顺序输入以下命令并回车：
	`npm install -D tailwindcss`
2. 确保`tailwind.config.js`和`src/style.css`已经在工作区目录下。如果你git了整个项目，那么这些文件已经放在该放的地方了。
3. 在终端输入`npx tailwindcss -i ./src/style.css -o ./dist/common.css --watch`并回车。

之后src下的`style.css`和一众`html`布局设计文件都在修改样式类的时候，`dist`下的`common.css`文件会自动更改，工作完成后，你可以使用`Wikitext3.4`插件上传`common.css`文件，这个`style.css`已经附带了页面信息标签头。
## 注意事项
在不确认后果、不明确自身目的的情况下，不要随便删除和改动已经写入的内容。当然如果问题发生了，撤，都可以撤。

如果你不确认后果和目的，不要删除`src`目录下的`html`文件，因为TailwindCSS依赖它来生成样式表。

## 扩展
[了解TailwindCSS](https://Tailwindcss.com) ｜ [了解Wikitext插件的使用方法](https://www.huijiwiki.com/p/21136) ｜ [Wikitext插件](https://marketplace.visualstudio.com/items?itemName=RoweWilsonFrederiskHolme.wikitext)

