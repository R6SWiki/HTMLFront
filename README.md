# tailwindcssfiles
本站的css有部分是通过TailwindCSS实现的，`style.css`是本站的tailwind核心文件。

##内容说明
`src`目录下有一些模板的设计方案，还有若干插图文件。不过插图文件可能已经不是很需要了。

## 使用方法


这里例举最简单的安装TailwindCSS和使用步骤，可根据需要参考：


1. 以最基本的方法安装TailwindCSS：使用在vscode项目中打开终端输入按顺序输入以下命令并回车：
	1. `npm install -D tailwindcss`
	2. `npx tailwindcss init`
2. 将`tailwind.config.js`放在项目根目录下。将`style.css`放在根目录下的`src`目录下。在这里如果下载整个项目，那么这些文件已经放在该放的地方了。
3. 在终端输入`npx tailwindcss -i ./src/style.css -o ./dist/common.css --watch`并回车。

之后在`dist`下的`common.css`文件会自动根据`style.css`文件的改动而更新，你可以使用`Wikitext`3.4版本插件上传，这个`style.css`已经附带了页面信息标签头。

## 扩展


[了解TailwindCSS](https://Tailwindcss.com) ｜ [了解Wikitext插件的使用方法](https://www.huijiwiki.com/p/21136) ｜ [Wikitext插件](https://marketplace.visualstudio.com/items?itemName=RoweWilsonFrederiskHolme.wikitext)
