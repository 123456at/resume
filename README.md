# Reveal.js 简历演示文稿

这是一个使用 Reveal.js 创建的简历演示文稿项目。通过 Markdown 编写内容，轻松创建漂亮的幻灯片式简历。

## 功能特点

- 基于 Reveal.js 的现代化演示文稿
- 使用 Markdown 简化内容编写
- 响应式设计，适配不同设备
- 自定义主题和样式
- 垂直和水平幻灯片导航

## 安装与使用

1. 克隆或下载本项目
2. 安装依赖

```bash
npm install
```

3. 在本地运行

```bash
npx http-server
```

4. 打开浏览器访问 `http://localhost:8080` 查看演示文稿

## 自定义内容

- 编辑 `resume.md` 文件来更新您的简历内容
- 修改 `css/custom.css` 来自定义样式
- 如需添加个人照片，请放置于 `assets` 目录下并更新 Markdown 中的引用

## Markdown 语法说明

- 使用 `---` 分隔水平幻灯片
- 使用 `--` 分隔垂直幻灯片（嵌套在当前水平幻灯片下）
- 使用标准 Markdown 语法编写内容
- 可以在 Markdown 中嵌入 HTML 来实现更复杂的布局

## 导出为 PDF

要将演示文稿导出为 PDF，请按照以下步骤操作：

1. 在浏览器中打开演示文稿
2. 添加 `?print-pdf` 到 URL 末尾，例如：`http://localhost:8080?print-pdf`
3. 使用浏览器的打印功能（Ctrl+P 或 Cmd+P）
4. 选择"另存为 PDF"选项

## 许可证

MIT 