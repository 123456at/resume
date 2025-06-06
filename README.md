# AI简历生成器

一个现代化的Web应用程序，帮助用户轻松创建和管理专业简历。

![简历生成器预览](resume-generator/src/logo.svg)

## 项目简介

AI简历生成器是一个基于React和TypeScript的Web应用，为求职者提供了一个便捷的工具来创建、编辑和管理专业简历。通过直观的用户界面和丰富的模板选择，用户可以快速生成高质量的简历，提升求职竞争力。

## 核心功能

- **用户账户系统**：注册、登录和账户管理
- **多样化简历模板**：提供多种专业设计的简历模板
- **简历编辑器**：直观的表单界面，轻松填写个人信息、教育背景、工作经验和技能
- **实时预览**：即时查看简历效果，所见即所得
- **PDF导出**：一键导出高质量PDF文件
- **简历管理**：保存多份简历并随时编辑

## 技术栈

- **前端框架**：React 19.1.0 + TypeScript
- **状态管理**：React Hooks
- **样式处理**：CSS模块化
- **PDF生成**：html2pdf.js
- **数据存储**：本地存储 + 后端API（计划中）

## 安装与使用

1. 克隆仓库
```bash
git clone https://github.com/您的用户名/您的仓库名.git
cd 您的仓库名/resume-generator
```

2. 安装依赖
```bash
npm install
```

3. 启动开发服务器
```bash
npm start
```

4. 构建生产版本
```bash
npm run build
```

## 项目结构

```
resume-generator/
├── public/             # 静态资源
├── src/                # 源代码
│   ├── components/     # React组件
│   │   ├── AuthModal.tsx       # 认证模态框
│   │   ├── HomePage.tsx        # 首页组件
│   │   ├── Login.tsx           # 登录组件
│   │   ├── Register.tsx        # 注册组件
│   │   ├── ResumeForm.tsx      # 简历表单组件
│   │   ├── ResumeList.tsx      # 简历列表组件
│   │   ├── ResumePreview.tsx   # 简历预览组件
│   │   └── TemplateSelector.tsx # 模板选择组件
│   ├── services/       # 服务
│   ├── types/          # TypeScript类型定义
│   ├── App.tsx         # 应用主组件
│   └── index.tsx       # 入口文件
└── package.json        # 项目配置
```

## 功能展示

1. **用户登录/注册**：安全的用户认证系统
2. **模板选择**：多种专业设计的简历模板
3. **简历编辑**：直观的表单界面，分类填写个人信息
4. **实时预览**：即时查看简历效果
5. **导出PDF**：高质量PDF文件导出

## 未来规划

- **AI辅助填写**：智能推荐内容和措辞
- **行业模板**：针对特定行业的专业模板
- **多语言支持**：国际化简历生成
- **简历分析**：提供改进建议和评分
- **ATS优化**：确保通过简历筛选系统

## 贡献指南

欢迎贡献代码、报告问题或提出新功能建议。请遵循以下步骤：

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交您的更改 (`git commit -m '添加一些特性'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开一个 Pull Request

## 许可证

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件 
