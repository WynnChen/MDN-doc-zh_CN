# MDN 文档简体中文翻译

本项目为翻译 MDN 文档所使用的 OmegaT 项目文件。

## 使用规则

### 源文件的建立与命名

源文件需要自行建立，命名规则如下：按照欲翻译页面的 slug 命名，使用 .html 后缀。例如：

-	页面：https://developer.mozilla.org/en-US/docs/Web/CSS
	文件：source/Web/css.html
-	页面：https://developer.mozilla.org/en-US/docs/Web/Events/webglcontextrestored
	文件：source/Web/Events/webglcontextrestored.html
-	页面：https://developer.mozilla.org/en-US/docs/MDN/Contribute/Guidelines/Writing_style_guide
	文件 source/MDN/Contribute/guidelines/Writing_style_guide.html

### 源文件的内容

源文件的内容按如下方式取得：

1. 查看欲翻译页面的 en_US 语言版本
2. 点击 edit 按钮进入编辑界面
3. 点击所见即所得编辑器的 源码 按钮
4. 编辑器中出现的源码做为源文件的内容

注意：不要在 MDN 页面的简体中文（或其他语言）的翻译界面上点击左侧英文版本的 查看源代码 来获取内容，这个位置显示的源代码与编辑器内的源代码有一些小差异，后继会导致问题。

### 翻译完成后的发布

如果需要将翻译好的内容发布回 MDN：

1. 生成已译文件
2. 用纯文本编辑器打开 target 目录下相应的已译文件，复制全部内容
3. 在 MDN 相应页面，查看简体中文版本，点击 编辑 按钮
4. 右侧所见即所得编辑器中点击 源码 按钮
5. 清空原有内容，粘贴复制的已译内容
6. 预览，检查无误后提交
7. 记得改页面的中文标题
8. 恰当加 tag

### 术语表

随翻译进度维护好术语表。

### 样式指南

翻译时请遵守《样式指南》的规则。

《样式指南》见 style_guide.md。


