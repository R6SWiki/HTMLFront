# tailwindcssfiles
本站的css有部分是通过TailwindCSS实现的，`style.css`是本站的tailwind核心文件。

[了解TailwindCSS](https://Tailwindcss.com)

## 使用方法


这里例举最简单的安装TailwindCSS和使用步骤，可根据需要参考：


1. 以最基本的方法安装TailwindCSS：使用终端输入以下命令并回车：
	1. `npm install -D tailwindcss`
	2. `npx tailwindcss init`
2. 将`tailwind.config.js`放在项目根目录下。
3. 将`style.css`放在根目录下的`src`目录下，没有这个目录就创建一个。
4. 在终端输入npx tailwindcss -i ./src/style.css -o ./dist/common.css --watch

之后common.css会自动更新，你可以使用wikitext插件上传，这个`style.css`已经附带了页面信息标签头。
