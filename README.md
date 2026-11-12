# Kindle 电子书转换器

一款面向中文 TXT 小说的 Windows 桌面工具，可导出适合 Kindle 阅读的 AZW3 和 MOBI 电子书。

## 下载与使用

[下载 Windows 64 位便携候选版 1.0.0rc8](https://github.com/Tintinding/kindle-txt-converter/releases/tag/v1.0.0rc8)。下载 ZIP 后完整解压到可写文件夹，双击 Kindle电子书转换器.exe，导入 TXT 并选择输出格式。启动时需要稍候。

## 功能

- 识别常见中文文本编码，支持手动选择编码。
- 预览清理建议，逐项确认删除并恢复，保留原始 TXT。
- 自动识别章节，支持人工调整目录。
- 设置书名、作者、简介和封面，支持批量转换。
- 默认导出 AZW3，可选择 MOBI，生成后由用户自行传送到 Kindle。

## 当前状态

当前候选版本为 1.0.0rc8，面向 Windows 10/11 64 位。便携包在开发机完成双格式转换检查，两种格式已获用户确认可在 Kindle Paperwhite 3 试读。便携包已作为预发行版提供下载，第三方组件公开分发材料仍在核对。

## 源码

仓库中的源码压缩包包含应用源码、构建脚本、规则、合成测试样例和第三方许可记录。项目开发使用 Python 3.14.10、PySide6 Essentials 6.12.0 和 Calibre 9.18.0。

## 许可

本项目自身源码的公开许可尚未选定。第三方组件遵循各自的许可，记录见源码包中的 docs/third-party-licenses.md。
