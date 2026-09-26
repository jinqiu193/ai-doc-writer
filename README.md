# AI文档智写

> AI智能识别截图，一键生成文档，支持多格式导出的 Chrome 浏览器扩展

## 功能特性

- 📸 **智能截图识别** - 一键截取屏幕内容，AI 自动识别文字、表格和图片
- 📝 **文档生成** - 基于识别结果自动生成结构化文档
- 📊 **多格式导出** - 支持 Word (.docx)、PPT (.pptx)、Markdown 等多种格式导出
- 🎯 **内置提示词模板** - 涵盖业务流程、产品需求、技术分析、医疗文档等多个领域
- 🔧 **侧边栏操作** - 集成在浏览器侧边栏，操作便捷

## 安装说明

### 方式一：加载已解压的扩展程序

1. 下载或克隆本仓库到本地
2. 打开 Chrome 浏览器，访问 `chrome://extensions`
3. 开启右上角的 **"开发者模式"**
4. 点击 **"加载已解压的扩展程序"**
5. 选择本项目文件夹
6. 安装完成后，可在 `chrome://extensions` 页面找到扩展

## 使用方法

1. 点击浏览器工具栏中的扩展图标，打开侧边栏
2. 使用截图功能截取需要识别的内容
3. AI 自动识别并生成文档
4. 选择需要的格式导出文档

## 项目结构

```
├── manifest.json          # 扩展配置文件
├── editor.html            # 文档编辑器页面
├── settings.html          # 设置页面
├── sidepanel.html         # 侧边栏页面
├── bundles/               # 打包后的 JS 文件
│   ├── content.min.js
│   ├── editor.min.js
│   ├── service-worker.min.js
│   └── ...
├── images/                # 扩展图标
├── prompts/               # 提示词模板
├── _locales/              # 国际化文件
└── HOW_TO_INSTALL.txt     # 安装说明
```

## 技术栈

- Chrome Extension Manifest V3
- JavaScript
- HTML/CSS

## 许可证

MIT License
