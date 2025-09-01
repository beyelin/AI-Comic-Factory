<div align="center">
  <h1>🎨 AI Comic Factory</h1>
  <p>使用 AI 技术创建精美漫画的智能工厂</p>
  
  <img src="https://img.shields.io/badge/React-19.1.1-blue?style=for-the-badge&logo=react" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-5.8.2-blue?style=for-the-badge&logo=typescript" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-6.2.0-646CFF?style=for-the-badge&logo=vite" alt="Vite">
  <img src="https://img.shields.io/badge/Google_Gemini-AI-orange?style=for-the-badge&logo=google" alt="Google Gemini">
  
  <br>
  
  <a href="https://ai-comic-factory-seven.vercel.app/">🚀 在线演示</a> |
  <a href="#功能特性">✨ 功能特性</a> |
  <a href="#快速开始">🏃‍♂️ 快速开始</a> |
  <a href="#使用说明">📖 使用说明</a>
</div>

---

## 📖 项目介绍

AI Comic Factory 是一个基于 Google Gemini AI 的智能漫画生成工具。用户只需输入故事主题和角色描述，AI 就能自动生成完整的漫画故事，包括情节、对话和精美的插图。项目采用现代化的 React + TypeScript 技术栈，提供流畅的用户体验和专业的漫画阅读界面。

## ✨ 功能特性

### 🤖 AI 智能生成
- **故事创作**: 基于用户输入自动生成完整漫画故事情节
- **角色设计**: 智能创建符合故事的角色形象和对话
- **图像生成**: 使用 Google Gemini AI 生成高质量漫画插图

### 🎨 多样化风格
- **动漫风格**: 经典日式动漫画风
- **美式漫画**: 超级英雄风格漫画
- **水彩风格**: 柔和艺术水彩效果
- **像素艺术**: 复古像素游戏风格
- **油画风格**: 经典油画艺术效果

### 📚 优质阅读体验
- **3D 翻页动画**: 真实书本翻页效果
- **响应式设计**: 完美适配各种设备屏幕
- **键盘导航**: 支持方向键翻页操作
- **优化排版**: 专业的漫画页面布局

### ⚡ 技术特色
- **现代化架构**: React 19 + TypeScript + Vite
- **快速部署**: 一键部署到 Vercel
- **环境配置**: 简单的 API 密钥配置
- **性能优化**: 图像懒加载和缓存机制

## 🚀 在线演示

访问我们的在线演示：[https://ai-comic-factory-seven.vercel.app/](https://ai-comic-factory-seven.vercel.app/)

> 注意：演示版本可能需要您自己配置 Google Gemini API 密钥

## 🏃‍♂️ 快速开始

### 📋 环境要求

- **Node.js**: 18.0.0 或更高版本
- **npm**: 8.0.0 或更高版本
- **Google Gemini API Key**: [获取 API 密钥](https://makersuite.google.com/app/apikey)

### 🔧 安装步骤

1. **克隆项目**
   ```bash
   git clone https://github.com/your-username/ai-comic-factory.git
   cd ai-comic-factory
   ```

2. **安装依赖**
   ```bash
   npm install
   ```

3. **配置环境变量**
   
   创建 `.env.local` 文件并添加您的 API 密钥：
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```
   
   > 💡 **获取 API 密钥**: 访问 [Google AI Studio](https://makersuite.google.com/app/apikey) 创建免费的 Gemini API 密钥

4. **启动开发服务器**
   ```bash
   npm run dev
   ```

5. **访问应用**
   
   打开浏览器访问 `http://localhost:5173`

### 🏗️ 构建部署

```bash
# 构建生产版本
npm run build

# 预览构建结果
npm run preview
```

## 📖 使用说明

### 🎯 创建漫画

1. **输入故事主题**
   - 在主题输入框中描述您想要的故事类型
   - 例如："一个关于太空探险的科幻故事"

2. **描述主要角色**
   - 详细描述故事的主要角色
   - 例如："勇敢的宇航员艾米，聪明的机器人助手"

3. **选择艺术风格**
   - 从 5 种预设风格中选择您喜欢的画风
   - 每种风格都有独特的视觉效果

4. **生成漫画**
   - 点击"生成漫画"按钮
   - AI 将自动创建 6 页完整的漫画故事

### 📱 阅读体验

- **翻页操作**: 点击页面边缘或使用键盘方向键
- **全屏阅读**: 支持全屏模式获得更好的阅读体验
- **响应式布局**: 自动适配手机、平板和桌面设备

## 🛠️ 技术栈

### 前端技术
- **React 19**: 最新的 React 框架
- **TypeScript**: 类型安全的 JavaScript
- **Vite**: 快速的构建工具
- **CSS3**: 现代化样式和动画

### AI 服务
- **Google Gemini**: 文本和图像生成
- **Gemini Pro**: 故事创作和角色设计
- **Imagen**: 高质量图像生成

### 部署平台
- **Vercel**: 无服务器部署平台
- **GitHub**: 代码托管和版本控制

## 📁 项目结构

```
ai-comic-factory/
├── src/
│   ├── components/          # React 组件
│   │   ├── ComicBook.tsx   # 漫画书组件
│   │   └── ComicGeneratorForm.tsx  # 生成表单
│   ├── services/           # 服务层
│   │   └── geminiService.ts # Gemini AI 服务
│   ├── types/              # TypeScript 类型定义
│   │   └── index.ts
│   ├── App.tsx             # 主应用组件
│   └── main.tsx            # 应用入口
├── public/                 # 静态资源
├── .env.local             # 环境变量配置
├── package.json           # 项目配置
├── vite.config.ts         # Vite 配置
└── README.md              # 项目说明
```

## 🔧 API 配置

### Google Gemini API

1. **获取 API 密钥**
   - 访问 [Google AI Studio](https://makersuite.google.com/app/apikey)
   - 使用 Google 账号登录
   - 创建新的 API 密钥

2. **配置环境变量**
   ```env
   # .env.local
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

3. **API 限制**
   - 免费版本有每日请求限制
   - 建议升级到付费版本以获得更好的体验

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 🐛 报告问题

如果您发现了 bug 或有功能建议：

1. 查看 [Issues](https://github.com/your-username/ai-comic-factory/issues) 确认问题未被报告
2. 创建新的 Issue 并详细描述问题
3. 提供复现步骤和环境信息

### 💻 代码贡献

1. **Fork 项目**
   ```bash
   git clone https://github.com/your-username/ai-comic-factory.git
   ```

2. **创建功能分支**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **提交更改**
   ```bash
   git commit -m 'Add some amazing feature'
   ```

4. **推送分支**
   ```bash
   git push origin feature/amazing-feature
   ```

5. **创建 Pull Request**

### 📝 代码规范

- 使用 TypeScript 进行类型检查
- 遵循 ESLint 代码规范
- 添加适当的注释和文档
- 确保所有测试通过

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [Google Gemini](https://gemini.google.com/) - 提供强大的 AI 能力
- [React](https://reactjs.org/) - 优秀的前端框架
- [Vite](https://vitejs.dev/) - 快速的构建工具
- [Vercel](https://vercel.com/) - 优秀的部署平台

## 📞 联系我们

- **项目主页**: [GitHub Repository](https://github.com/your-username/ai-comic-factory)
- **在线演示**: [Live Demo](https://ai-comic-factory-seven.vercel.app/)
- **问题反馈**: [Issues](https://github.com/your-username/ai-comic-factory/issues)

---

<div align="center">
  <p>如果这个项目对您有帮助，请给我们一个 ⭐️ Star！</p>
  <p>Made with ❤️ by AI Comic Factory Team</p>
</div>
