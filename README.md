# Kindle 电子书转换器

一款面向中文 TXT 小说的 Windows 桌面工具，可导出适合 Kindle 阅读的 AZW3 和 MOBI 电子书。V1.1 起也支持 EPUB 直接转换。

## 下载与使用

仓库提供最新源码包 `KindleTxtConverter-source-1.1.0rc2.zip`，包含应用源码、构建脚本和验证脚本；便携版可按 `scripts/build_single_file.py` 在本地构建。上一版便携包仍可从 [1.0.0rc8 预发行版](https://github.com/Tintinding/kindle-txt-converter/releases/tag/v1.0.0rc8) 下载。

构建出的单文件 ZIP 完整解压到可写文件夹，双击 Kindle电子书转换器.exe，导入 TXT 或 EPUB 并选择输出格式。启动时需要稍候。

## 功能

- 识别常见中文文本编码，支持手动选择编码。
- 预览清理建议，逐项确认删除并恢复，保留原始 TXT。
- 自动识别章节，支持人工调整目录。
- 设置书名、作者、简介和封面，支持批量转换。
- 支持 EPUB 输入，保留原书排版、插图和内嵌目录。
- 默认导出 AZW3，可选择 MOBI，生成后由用户自行传送到 Kindle。
- 浅色书卷风界面，保留「书籍信息 / 清理预览 / 章节目录」三个标签页。

## 当前状态

当前候选版本为 1.1.0rc2，面向 Windows 10/11 64 位。单文件便携包在开发机隔离环境完成 AZW3、MOBI 和 EPUB 转换检查，正常退出后临时运行目录清理通过；干净 Windows 实机与 EPUB 的 Paperwhite 3 试读仍待验证。第三方组件公开分发材料仍在核对。

## 源码

`KindleTxtConverter-source-1.1.0rc2.zip` 包含应用源码、构建脚本、测试、规则、文档和第三方许可记录。项目开发使用 Python 3.14.10、PySide6 Essentials 6.12.0 和 Calibre 9.18.0。

`KindleTxtConverter-source-1.0.0rc8.zip` 为上一版源码包，保留备查。

## 许可

本项目自身源码的公开许可尚未选定。第三方组件遵循各自的许可，记录见源码包中的 docs/third-party-licenses.md。
