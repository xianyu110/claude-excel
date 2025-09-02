# 📊 Excel文档分析器

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-在线访问-blue)](https://xianyu110.github.io/claude-excel-/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

一个功能强大的在线Excel文档分析工具，能够解析Excel文件并提取数据供Claude等AI模型分析。支持多种数据格式输出，一键复制到剪贴板。

## ✨ 功能特性

### 🎯 核心功能
- 📁 **智能上传**: 支持拖拽或点击上传Excel文件（.xlsx, .xls格式）
- 📊 **自动分析**: 快速分析文件基本信息（大小、工作表数量、修改时间等）
- 👁️ **内容预览**: 工作表内容实时预览，支持大数据表格
- 🔄 **多格式输出**:
  - JSON格式 - 适合程序处理
  - CSV格式 - 适合数据导入
  - Markdown表格 - 适合文档展示

### 🎨 用户体验
- 📄 **一键复制**: 提取的数据可以直接复制到剪贴板
- 🎭 **现代化UI**: 采用渐变背景和现代化设计风格
- 📱 **响应式设计**: 完美适配桌面端和移动端
- ⚡ **实时处理**: 所有操作都在浏览器本地完成，无需等待

### 🔒 隐私安全
- 🏠 **本地处理**: 所有文件处理都在浏览器本地进行
- 🚫 **无上传**: 不会上传任何文件到服务器
- 🔐 **数据安全**: 分析完成后数据不会被存储或传输

## 🚀 在线使用

### 直接访问
点击下方链接开始使用：
**🌐 [https://xianyu110.github.io/claude-excel-/](https://xianyu110.github.io/claude-excel-/)**

### 使用步骤
1. **打开页面**: 访问上面的链接进入分析器
2. **上传文件**: 点击"选择文件"按钮或直接拖拽Excel文件到上传区域
3. **等待分析**: 系统自动分析文件结构和内容
4. **查看结果**: 查看文件基本信息和工作表预览
5. **选择格式**: 根据需要选择数据提取格式（JSON/CSV/Markdown）
6. **复制数据**: 点击"复制到剪贴板"按钮
7. **AI分析**: 将复制的数据粘贴给Claude或其他AI工具进行深入分析

## 💻 本地运行

### 方法一：直接打开
```bash
# 下载项目文件
git clone https://github.com/xianyu110/claude-excel-.git
cd claude-excel-

# 在浏览器中打开
# Windows: 双击 index.html
# macOS: 在浏览器中打开 index.html
# Linux: 在浏览器中打开 index.html
```

### 方法二：使用本地服务器（推荐）
```bash
# 安装Node.js后运行
npx live-server

# 或使用Python
python -m http.server 8000

# 或使用PHP
php -S localhost:8000
```

## 🛠️ 技术栈

- **前端框架**: HTML5 + CSS3 + JavaScript (ES6+)
- **Excel解析**: [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs) - 业界领先的Excel处理库
- **样式设计**: 现代化响应式设计，无需额外框架
- **部署平台**: GitHub Pages - 免费静态网站托管

## 📁 项目结构

```
claude-excel-/
├── index.html          # 主页面文件（包含完整功能）
├── README.md           # 项目说明文档
└── .git/              # Git版本控制
```

## 🌐 部署到GitHub Pages

本项目已经部署到GitHub Pages，你可以通过以下方式部署自己的版本：

### 自动部署（推荐）
1. **Fork本仓库**
2. **进入仓库设置** → **Pages**
3. **选择分支**：`main` 分支 `/root` 目录
4. **保存设置**，等待自动部署完成

### 手动部署
```bash
# 1. 创建新仓库
# 2. 克隆到本地
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# 3. 复制项目文件
cp -r /path/to/claude-excel-/* ./

# 4. 提交并推送
git add .
git commit -m "Deploy Excel Analyzer"
git push origin main

# 5. 启用GitHub Pages（见上方步骤）
```

## 📊 浏览器兼容性

| 浏览器 | 最低版本 | 推荐版本 |
|--------|----------|----------|
| Chrome | 70+ | 最新版 |
| Firefox | 65+ | 最新版 |
| Safari | 12+ | 最新版 |
| Edge | 79+ | 最新版 |
| iOS Safari | 12+ | 最新版 |
| Chrome Mobile | 70+ | 最新版 |

## 🔧 开发说明

### 环境要求
- 现代浏览器支持ES6+
- 无需Node.js环境（纯静态页面）

### 自定义修改
- 直接编辑`index.html`文件
- 修改CSS样式自定义界面
- 添加新的数据导出格式
- 扩展功能模块

## 📝 更新日志

### v1.0.0 (2025-01-XX)
- ✅ 初始版本发布
- ✅ 支持Excel文件上传和解析
- ✅ 实现多格式数据导出
- ✅ 响应式UI设计
- ✅ GitHub Pages部署

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进这个工具！

### 贡献步骤
1. Fork本仓库
2. 创建特性分支：`git checkout -b feature/amazing-feature`
3. 提交更改：`git commit -m 'Add amazing feature'`
4. 推送分支：`git push origin feature/amazing-feature`
5. 创建Pull Request

## 📄 许可证

本项目采用 **MIT License** 开源许可证。

## 🙏 致谢

- [SheetJS](https://github.com/SheetJS/sheetjs) - 强大的Excel处理库
- [GitHub Pages](https://pages.github.com/) - 免费的静态网站托管服务

## 📞 联系方式

- **项目主页**: [https://github.com/xianyu110/claude-excel-](https://github.com/xianyu110/claude-excel-)
- **在线使用**: [https://xianyu110.github.io/claude-excel-/](https://xianyu110.github.io/claude-excel-/)

---

<div align="center">

**如果您觉得这个工具对您有帮助，请给项目一个 ⭐ Star！**

Made with ❤️ for Excel users and AI enthusiasts

</div>
